# CV Latex Template

A clean, professional CV/Resume template in LaTeX with both English and Chinese versions.

## Features

- Separate English and Chinese versions
- Professional layout
- Custom class file for consistent styling
- Profile photo support

## Structure

- `style.sty`: Common class file for both versions
- `cv_chinese.tex`: English CV template
- `cv_english.tex`: Chinese CV template
- `images/`: Directory for profile photo

## Usage

1. Install LaTeX on your system
2. Place your profile photo in the `images` folder
3. Compile using XeLaTeX:
   ```bash
   xelatex cv_chinese.tex  # For English version
   xelatex cv_english.tex  # For Chinese version
   ```
