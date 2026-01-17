# Open-Source Presentation Repository Setup

## Project Overview
Create a Github Repository and a presentation "My Contributions to Open-Source: From AdmiralMetabolic to dataviewR" using Quarto revealjs format.

## Tasks to Complete
 
### 1. GitHub Repository Creation
- Create a new GitHub repository named `nn-opensource-presentation`
- Initialize with a README.md that includes:
  - Project title
  - Brief description: "A presentation about my open-source contributions to AdmiralMetabolic and dataviewR packages"
  - Instructions on how to render the presentation
  - Prerequisites (Quarto installation)
- Add a `.gitignore` file suitable for R/Quarto projects

### 2. Project Structure
Create the following directory structure:
```
opensource-presentation/
├── README.md
├── .gitignore
├── presentation.qmd
├── custom.css
└── images/
    └── .gitkeep
```

### 3. Quarto Presentation File (`presentation.qmd`)
Create a Quarto revealjs presentation with the following specifications:

**YAML Configuration:**
- Title: "My Contributions to Open-Source"
- Subtitle: "From AdmiralMetabolic to dataviewR"
- Author: Siddhesh Pujari	
- Format: revealjs
- Theme: default
- Font size: 12px
- Slide numbers: enabled
- CSS: custom.css
- Transitions: none (both transition and background-transition)

**Presentation Content:**
Include all slides from the presentation outline I provided covering:
1. Introduction - What we'll cover today
2. How it all started (Mid-2024)
3. AdmiralMetabolic: My first steps
   - What is AdmiralMetabolic
   - My contributions (vignettes, documentation, code review)
   - What I learned
4. Joining the AdmiralDevelopment Team
   - Transition phase
   - Focus on unit testing
5. Contributing to dataviewR
   - The project
   - My role (website, documentation, examples, articles)
   - Result: CRAN release v1.0
6. What I learned along the way
   - Technical skills
   - Soft skills
10. How YOU can get started

**Special Instructions for Slides:**
- Split longer slides into multiple slides for better pacing
- Use `{.smaller}` class for the "Common Concerns" slide
- I will be showing the package website and do most of the talking there so give URLs to each package first slide and make it clickable
- Use appropriate markdown formatting (bold, italic, lists)

### 4. Custom CSS File (`custom.css`)
Create a custom CSS file with:
- Arial/Helvetica font family for body text
- Arial/Helvetica bold for headings (h1, h2, h3)
- Professional, clean styling suitable for a technical presentation

### 5. README.md Content
Include in the README:
- Project title and description
- How to render the presentation:
  - Using RStudio
  - Using command line with `quarto render presentation.qmd`
- How to view the presentation:
  - Open the generated HTML file in a browser
- Prerequisites:
  - Quarto installation link
  - Mention that screenshots and logos need to be added to the `images/` folder
- Section for adding screenshots:
  - List what screenshots are needed
  - Where they should be placed

### 6. .gitignore File
Create a comprehensive .gitignore for:
- R/RStudio files (*.Rproj, .Rhistory, .RData, etc.)
- Quarto output files (presentation_files/, .quarto/, etc.)
- System files (.DS_Store, Thumbs.db)
- Keep the images folder structure but ignore large files

## Additional Requirements

### File Organization
- All files should be in the root directory except images
- Images folder should have a `.gitkeep` file to preserve the directory structure
- Use relative paths for all image references

### Code Quality
- Use proper YAML formatting with correct indentation
- Ensure markdown syntax is valid
- CSS should be properly formatted and commented

### Documentation
- Add comments in the .qmd file where user input is needed (author name, image paths)
- Include helpful notes in the README about customization options

## After Repository Creation

Once the repository is created, I will:
2. Add admiral and dataviewR logos to the images folder
3. Add screenshots of my contributions
4. Customize colors if needed
5. Test render the presentation locally

## Success Criteria
- Repository is created on GitHub and accessible
- All files are present and properly structured
- Quarto presentation renders without errors (even without images)
- README provides clear instructions
- CSS file is linked and working
- Presentation content matches the outline provided

## Notes
- This is my first time working with Quarto, so include helpful comments
- The presentation is for a total 15 minutes. 10 min from slides and 10 min demo from me showing the three package websites
- Audience has 2-15 years of experience
- Tone should be professional but conversational
- Focus on encouraging team members to explore open-source contributions