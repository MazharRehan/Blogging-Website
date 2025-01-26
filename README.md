# Blogging Website

This is a simple blogging website created as part of a DevOps Fundamentals assignment. The website consists of three pages:
- Home
- Blog
- Contact Us

The project uses GitHub Actions for CI/CD workflows to validate code quality and automate deployments to GitHub Pages.

## Features
- **Home Page**: Welcomes users to the blogging platform.
- **Blog Page**: Displays a list of blog posts with titles, descriptions, and links.
- **Contact Us Page**: Provides a form for users to contact the site owner.
- Responsive design and clean UI.

## Tech Stack
- **HTML**: For structuring the web pages.
- **CSS**: For styling the web pages.
- **Parcel Bundler**: For building and optimizing the website.
- **GitHub Actions**: For automating CI/CD workflows.

## CI/CD Workflows
1. **PR Validation Workflow**:
   - Lints HTML and CSS files.
   - Ensures the website builds successfully before merging pull requests.
2. **Deployment Workflow**:
   - Automatically builds and deploys the website to GitHub Pages on every push to the `develop` branch.

## Access the Hosted Website
The website is hosted on **GitHub Pages** and can be accessed at the following link:

[Hosted Blogging Website](https://mazharrehan.github.io/Blogging-Website/)



## Folder Structure
    ```
    Blogging-Website/
    ├── src/
    │   ├── home.html
    │   ├── blog.html
    │   ├── contact-us.html
    ├── styles/
    │   ├── home.css
    │   ├── blog.css
    │   ├── contact-us.css
    ├── .github/
    │   ├── workflows/
    │       ├── pr-validation.yaml
    │       ├── deploy-development.yaml
    ├── package.json
    ├── .gitignore
    ├── README.md
    ```
    
## How to Run Locally
1. Clone the repository:
    ```bash
    git clone https://github.com/<MazharRehan>/Blogging-Website.git
    ```
2. Navigate to the project directory
    ```bash
    cd Blogging-Website
    ```
3. Install dependencies
    ```bash
    npm install
    ```
4. Run the development server
    ```bash
    npx parcel src/index.html
    ```
5. Open in the browser
    ```bash
    http://localhost:1234
    ```

## License
    This project is licensed under the ISC License.
