# My Contributions to Open-Source: From AdmiralMetabolic to dataviewR

A presentation about my open-source contributions to the AdmiralMetabolic and dataviewR packages, showcasing my journey in contributing to R package development and the pharmaceutical open-source community.

## View the Presentation

**Live Presentation:** [https://siddhesh2097.github.io/nn-opensource-presentation/](https://siddhesh2097.github.io/nn-opensource-presentation/)

The presentation is hosted on GitHub Pages and can be viewed directly in your browser.

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

### Option 1: View Online (Recommended)
Visit the live presentation at: [https://siddhesh2097.github.io/nn-opensource-presentation/](https://siddhesh2097.github.io/nn-opensource-presentation/)

### Option 2: View Locally
After rendering, open `presentation.html` in your web browser.

### Navigation
Use the arrow keys to navigate between slides:
- Right arrow or Space: Next slide
- Left arrow: Previous slide
- ESC: Overview mode

## Project Structure

```
nn-opensource-presentation/
├── README.md              # This file
├── .gitignore            # Git ignore rules
├── presentation.qmd      # Main presentation file
├── presentation.html     # Rendered presentation
├── custom.css            # Custom styling
├── images/               # Package logos
│   ├── admiral-logo.png
│   ├── metabolic-logo.png
│   └── dataviewr-logo.png
└── docs/                 # GitHub Pages deployment
    ├── index.html        # Deployed presentation
    ├── custom.css
    ├── images/
    └── presentation_files/
```

## Images

The presentation includes logos for the following packages:
- `admiral-logo.png` - Admiral logo
- `metabolic-logo.png` - AdmiralMetabolic logo
- `dataviewr-logo.png` - dataviewR logo

All images are included in the `images/` folder.

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
