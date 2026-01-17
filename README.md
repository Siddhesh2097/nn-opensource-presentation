# My Contributions to Open-Source: From AdmiralMetabolic to dataviewR

A presentation about my open-source contributions to the AdmiralMetabolic and dataviewR packages, showcasing my journey in contributing to R package development and the pharmaceutical open-source community.

## Overview

This repository contains a Quarto revealjs presentation that walks through my experience contributing to open-source R packages, including:
- My first steps with AdmiralMetabolic
- Joining the AdmiralDevelopment team
- Contributing to dataviewR's CRAN release v1.0
- Lessons learned and how others can get started

## Prerequisites

Before rendering the presentation, you'll need:
- [Quarto](https://quarto.org/docs/get-started/) installed on your system
- R and RStudio (optional, but recommended for R users)

## How to Render the Presentation

### Using RStudio
1. Open `presentation.qmd` in RStudio
2. Click the "Render" button at the top of the editor
3. The presentation will render and open in your browser

### Using Command Line
```bash
quarto render presentation.qmd
```

## How to View the Presentation

After rendering, open `presentation.html` in your web browser. Use the arrow keys to navigate between slides:
- Right arrow or Space: Next slide
- Left arrow: Previous slide
- ESC: Overview mode

## Project Structure

```
nn-opensource-presentation/
├── README.md           # This file
├── .gitignore         # Git ignore rules
├── presentation.qmd   # Main presentation file
├── custom.css         # Custom styling
└── images/            # Folder for screenshots and logos
    └── .gitkeep
```

## Adding Images

To complete the presentation, add the following images to the `images/` folder:

### Required Logos
- `admiral-logo.png` - Admiral logo
- `dataviewr-logo.png` - dataviewR logo

### Required Screenshots
- `admiral-metabolic-vignette.png` - Screenshot of vignette work
- `dataviewr-website.png` - Screenshot of the dataviewR website
- `dataviewr-cran.png` - Screenshot showing CRAN release

**Note:** The presentation will render without these images, but placeholders will appear where images should be displayed.

## Customization Options

### Changing Colors
Edit `custom.css` to customize the color scheme and styling.

### Modifying Content
Edit `presentation.qmd` to update slides, add new content, or change the presentation structure.

### Presentation Settings
Modify the YAML header in `presentation.qmd` to change:
- Theme
- Transition effects
- Slide numbers
- And more

## License

This presentation is created for internal team sharing purposes.

## Contact

For questions or feedback, please reach out to Siddhesh Pujari.
