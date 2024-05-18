# hugo-mock-landing-page-autodeployed

CIS 3500 HW2 Part II

This repository hosts a mock landing page built with Hugo that is automatically deployed to GitHub Pages using GitHub Actions. The site can be found at https://anirudhb123.github.io/hugo-mock-landing-page-autodeployed/. 

## Workflow Description

The workflow defined in this repository automates the process of building and deploying the Hugo static website to GitHub Pages. The  order of the workflow is defined below:

1. **Check Out Source Repository**: This step checks out the source repository, including any submodules.
2. **Initialize Hugo Environment**: This step sets up the Hugo environment with the specified version and flags.
3. **Compile Hugo Static Files**: This step compiles the Hugo static files, including drafts, for deployment.
4. **Publish to GitHub Pages**: This step publishes the compiled static files to the `gh-pages` branch, allowing you to visit the website on Github Pages and see any changes you've made. 

Each time code is pushed to the `main` branch, this workflow will be triggered. 
