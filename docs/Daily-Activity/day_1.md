# 1. Activity of Day 1: Main introduction of Modeling and Fabrication Techniques.

# Foundations of Modeling and Fabrication.

## introduction to modeling and Fabrication
Foundation of modeling and Fabrication, why modeling and fabrication Matters, design-to-fabrication steps or cintinuum which are Design, Model, Prototype, Fabricate and Evaluate. Digital Fabrication Paradigms like Hybrid Fabrication Paradigm where it combines Subtractive and Addictive Fabrication paradigms.

### 1. Building Documentation website using MkDocs Materials

#### A. Install Prerequisites
Install Python version 3.8 or later. • Install MkDocs and the Material theme using pip. "pip install mkdocs mkdocs-material"

#### B. Create a New MkDocs Project
Create a new documentation project and move into the project directory. mkdocs new my-docs "cd my-docs"

#### C. Enable the Material Theme
Edit the mkdocs.yml configuration file to enable the Material theme. "site_name: Project Documentation theme: name: material"

#### D. Write Documentation Content
All documentation pages are written in Markdown. • Place Markdown files inside the docs/ directory. docs/ index.md introduction.md hardware.md software.md

#### E. Configure Navigation
Define site navigation in mkdocs.yml to organize pages. nav: - Home: index.md - Introduction: introduction.md - Hardware Design: hardware.md - Software Design: software.md

#### F. Preview the Website Locally
Run the development server to preview changes in real time. "mkdocs serve"

#### G. Enable Material Features (Optional)
features:

1. navigation.tabs
2. navigation.top
3. search.suggest
4. content.code.copy

#### H. Add Recommended Markdown Extensions
markdown_extensions:

1. admonition
2. toc: permalink: true
3. pymdownx.superfences
4. pymdownx.highlight

#### I. Build the Static Website
Generate the static site files. "mkdocs build"

#### J. Deploy the Documentation Website
Deploy to GitHub Pages using MkDocs built-in support. • Alternatively deploy to Netlify, Vercel, or a local server. "mkdocs gh-deploy"

## Takehome
to be Able to create a website page via Github Page that documents every activity done in every work performed during this Lessons.


