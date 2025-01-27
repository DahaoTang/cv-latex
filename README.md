# CV Latex Template

A clean, professional CV/Resume template in LaTeX with both English and Chinese versions.

## Features

- Separate English and Chinese versions
- Clean black and white design
- Professional layout
- Custom class file for consistent styling
- Profile photo support (Chinese version)

## Structure

- `resume.cls`: Common class file for both versions
- `resume_en.tex`: English CV template
- `resume_zh.tex`: Chinese CV template
- `images/`: Directory for profile photo
- `fonts/`: Directory for Chinese fonts

## Usage

1. Install LaTeX on your system
2. Place your profile photo in the `images` folder
3. Compile using XeLaTeX:
   ```bash
   xelatex resume_en.tex  # For English version
   xelatex resume_zh.tex  # For Chinese version
   ```
