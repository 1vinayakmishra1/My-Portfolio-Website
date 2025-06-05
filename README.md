# Vinayak's Portfolio Website

This is a personal portfolio website designed to showcase my web development projects, skills, educational background, and professional resume. It's built with HTML, CSS, and a touch of JavaScript for interactivity.

## Live Demo

You can view the live version of the website here:  
**[I will add the link after hosting it.]**

## Description

This portfolio provides a comprehensive look at my journey in technology. It features a clean, modern, and responsive design, ensuring a good viewing experience across various devices. Key sections include a welcoming home page, an "About Me" section detailing skills, education, and resume, a project showcase, and easy ways to get in contact.

## Features

* **Home Section:** Engaging welcome message with "Learn about Me" and "Hire Me" call-to-action buttons.
* **About Me Section:**
    * Interactive cards linking to dedicated pages for Skills, Education & Certifications, Resume, and Projects.
    * Visually appealing reflection effect on the section title.
* **Contact Section:**
    * Direct links to LinkedIn (Direct Contact), GitHub (Portfolio), and Email (Direct Contact).
    * Stylish, glowing social media buttons.
* **"Hire Me" Modal:** A pop-up modal activated by the "Hire Me" button, providing quick contact options.
* **Responsive Design:** Adapts to different screen sizes for optimal viewing on desktops, tablets, and mobile phones.
* **Smooth Scrolling:** Enhances navigation between sections.
* **Dynamic Content:** The current year in the footer is automatically updated using JavaScript.
* **SEO & Social Sharing:** Includes meta tags for search engine optimization and social media previews (Open Graph).

## Technologies I Used

* **HTML5:** For the structure and content of the website.
* **CSS3:** For styling, layout (including Flexbox), gradients, transitions, and animations.
* **JavaScript:** For dynamic functionalities like the "Hire Me" modal and updating the year in the footer.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Project Structure

```
My-Portfolio-Website/
├── assets/                        # Static assets: images, icons, PDFs, etc.
├── ../css/                           # All CSS files for styling different sections and pages
│   ├── common.css
│   ├── education-certifications.css
│   ├── home.css
│   ├── projects.css
│   ├── resume.css
│   └── skills.css
├── index.html                     # Home page (main landing page)
├── education-certifications.html  # Education & Certifications page
├── projects.html                  # Projects showcase page
├── resume.html                    # Resume page (links to/downloads your resume PDF)
├── skills.html                    # Skills overview page
├── .gitignore
├── .gitattributes
├── LICENSE                        # License file
└── README.md                      # This documentation file
```

**Details:**

- **assets/**: Static assets such as:
    - Images (e.g., `logo.png`, `preview.png`, `favicon.ico`)
    - Icons (SVG/PNG)
    - PDFs (e.g., `Vinayak_Mishra_Resume.pdf`)
- **../css/**: All CSS files for styling different sections and pages.
- **index.html**: Main landing page (Home).
- **education-certifications.html**: Education & Certifications page (shows your academic background and certifications).
- **projects.html**: Projects showcase page (shows projects you have created).
- **resume.html**: Resume page (links to or downloads your resume PDF).
- **skills.html**: Skills overview page (lists your technical and soft skills).
- **LICENSE**: License file.
- **README.md**: This documentation file.

## Setup

To view the website locally:

1. Clone this repository or download the files.
2. Open `index.html` in your preferred web browser.

## Hosting on GitHub Pages

1. Ensure all your HTML, CSS, and asset files are at the root of your repository (as shown above).
2. Go to your repository's **Settings** > **Pages**.
3. Under "Source", select the `main` branch and `/ (root)` folder.
4. Save and wait a few minutes for your site to be published.
5. Your portfolio will be live at `https://your-username.github.io/your-repo-name/`.

## Customization

* **Personal Information:** Update your details in `index.html` and the respective HTML files.
* **Meta Tags:**
    * In `index.html`, replace the placeholder `og:url` with your live portfolio URL.
    * Replace the placeholder `og:image` with a URL to an actual preview image for your portfolio.
* **Styling:** Modify the CSS files in `../css/` (`common.css`, `projects.css`, `skills.css`, etc.) to change the appearance.
* **Contact Links:** Update the `href` attributes in the contact section and the "Hire Me" modal in `index.html` with your actual social media and email links.
* **Resume PDF:** Place your resume PDF in the `assets/` folder and ensure the link in `resume.html` points to the correct file name.

---

Feel free to further adjust the structure or add more details according to your needs!  
If you have any feedback, feel free to reach out to me.