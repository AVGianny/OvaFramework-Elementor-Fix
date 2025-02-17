# Ova Framework Elementor Compatibility Fix

[![GitHub last commit](https://img.shields.io/github/last-commit/AVGianny/OvaFramework-Elementor-Fix?style=flat-square)](https://github.com/AVGianny/OvaFramework-Elementor-Fix/commits/main)
[![GitHub issues](https://img.shields.io/github/issues/AVGianny/OvaFramework-Elementor-Fix?style=flat-square)](https://github.com/AVGianny/OvaFramework-Elementor-Fix/issues)

This repository provides a fix for the **Ova Framework** to ensure compatibility with **Elementor 3.0 and later versions**. The fix addresses the deprecation of `Elementor\Scheme_Color` and replaces it with the new `Elementor\Core\Kits\Documents\Tabs\Global_Colors` system.

---

## Problem

The Ova Framework relies on `Elementor\Scheme_Color`, which was **deprecated in Elementor 2.8.0** and **removed in Elementor 3.0+**. This causes **fatal errors** when using the Ova Framework with newer versions of Elementor.

---

## Solution

This fix replaces all instances of `Elementor\Scheme_Color` with the new **Globals system** (`Elementor\Core\Kits\Documents\Tabs\Global_Colors`). The updated code ensures seamless compatibility with Elementor 3.0+.

### Key Changes:
- Replaced `Elementor\Scheme_Color::COLOR_1` with `Elementor\Core\Kits\Documents\Tabs\Global_Colors::COLOR_PRIMARY`.
- Updated affected files to use the new Globals system.

---

## How to Use

1. **Download the Fix**:
   - Clone this repository or download the ZIP file:
     ```bash
     git clone https://github.com/AVGianny/OvaFramework-Elementor-Fix.git
     ```

2. **Replace Affected Files**:
   - Replace the corresponding files in your Ova Framework installation with the updated files from this repository.

3. **Clear Cache**:
   - Clear any caching mechanisms (e.g., WordPress cache, browser cache) to ensure the changes take effect.

4. **Test Your Site**:
   - Verify that the fix works by testing your site with the latest version of Elementor.

---

## Repository Structure
OvaFramework-Elementor-Fix/
- README.md # Project documentation
- ova-menu.php # Updated menu file

## Contact

If you have any questions or need further assistance, feel free to reach out:
- **GitHub**: [@AVGianny](https://github.com/AVGianny)
- **Email**: GiannyN@proton.me
