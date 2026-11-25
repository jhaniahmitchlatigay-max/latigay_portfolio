# Personal Portfolio Website

A responsive personal portfolio built for the CIT 240 Final Capstone Portfolio Assignment using HTML5, CSS3, and vanilla JavaScript.

## Features
- Semantic HTML sections: header, nav, main, section, article, and footer
- Responsive layout using CSS Grid, Flexbox, and media queries
- Mobile navigation menu
- Smooth scrolling
- Skills matrix and three featured project cards
- Open Source and Capstone Showcase
- Contact section and social profile links

## Project Structure
```text
portfolio/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    └── (add your profile photo and project screenshots here)
```

## How to Customize
1. Open `index.html`.
2. Replace `Your Name`, the biography, education, and career goal with your information.
3. Replace the GitHub, LinkedIn, and email placeholders with your real links.
4. Add your profile photo and project screenshots inside the `assets` folder. Update the relevant HTML sections to display those images.
5. Replace sample project descriptions and repository/demo links with your actual projects.
6. Review the skills list and remove any technologies you have not used.

## Run Locally
Open `index.html` in a web browser. For development, you may use the Live Server extension in Visual Studio Code.

## Deploy with GitHub Pages
1. Create a **public** GitHub repository. For a user site, name it `YOUR-USERNAME.github.io`; for a project site, a name such as `portfolio` is fine.
2. Open a terminal in this project folder and run:
   ```bash
   git init
   git add .
   git commit -m "feat: initial portfolio build"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git
   git push -u origin main
   ```
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for the deployment to finish. Open the GitHub Pages URL shown in the Pages settings.

## Before Submission
- [ ] Replace all personal information placeholders.
- [ ] Add a profile photo and at least three real project screenshots.
- [ ] Add working GitHub source links and live demo links for the project cards.
- [ ] Confirm that your repository is public.
- [ ] Test the website on both mobile and desktop.
- [ ] Confirm that the GitHub Pages URL opens and all assets load.
