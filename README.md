# Vinayak's Portfolio Website

This is a personal portfolio website designed to showcase my web development projects, skills, educational background, and professional resume. It's built with HTML, CSS, and a touch of JavaScript for interactivity.

## Live Demo

You can view the live version of the website here:  
**[Link to be added once hosted]**

## Description

This portfolio provides a comprehensive look at my journey in technology. It features a clean, modern, and responsive design, ensuring a good viewing experience across various devices. Key sections include a welcoming home page, an "About Me" section detailing skills, education, and resume, a project showcase, and easy ways to get in contact.

## Features

* **Home Section:** Engaging welcome message with "Learn about Me" and "Hire Me" call-to-action buttons.
* **About Me Section:**
    * Interactive cards linking to dedicated pages for Skills, Education & Certifications, Resume, and Projects.
    * Visually appealing reflection effect on the section title.
* **Contact Section:**
    * Direct links to LinkedIn, GitHub, and Email.
    * Stylish, glowing social media buttons.
* **"Hire Me" Modal:** A pop-up modal activated by the "Hire Me" button, providing quick contact options.
* **Responsive Design:** Adapts to different screen sizes for optimal viewing on desktops, tablets, and mobile phones.
* **Smooth Scrolling:** Enhances navigation between sections.
* **Dynamic Content:** The current year in the footer is automatically updated using JavaScript.
* **SEO & Social Sharing:** Includes meta tags for search engine optimization and social media previews (Open Graph).

## Technologies Used

* **HTML5:** For the structure and content of the website.
* **CSS3:** For styling, layout (including Flexbox), gradients, transitions, and animations.
* **JavaScript:** For dynamic functionalities like the "Hire Me" modal and updating the year in the footer.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Project Structure

```
My-Portfolio-Website/
├── Portfolio-Website/
│   ├── assets/
│   │   ├── [images, icons, PDFs, SVGs, etc.]
│   ├── css/
│   │   ├── common.css
│   │   ├── education-certifications.css
│   │   ├── home.css
│   │   ├── projects.css
│   │   ├── resume.css
│   │   └── skills.css
│   └── index/
│       ├── home.html
│       ├── education-certifications.html
│       ├── projects.html
│       ├── resume.html
│       └── skills.html
├── LICENSE.md
└── README.md
```

**Details:**

- **Portfolio-Website/**: Main project folder containing all website source files.
    - **assets/**: Static assets such as:
        - Images (e.g., `logo.png`, `preview.png`, `favicon.ico`)
        - Icons (SVG/PNG)
        - PDFs (e.g., `Vinayak_Mishra_Resume.pdf`)
    - **css/**: All CSS files for styling different sections and pages.
        - `common.css`: Shared/global styles.
        - `education-certifications.css`: Styles for the Education & Certifications page.
        - `home.css`: Styles for the Home page.
        - `projects.css`: Styles for the Projects page.
        - `resume.css`: Styles for the Resume page.
        - `skills.css`: Styles for the Skills page.
    - **index/**: All main HTML files for each section.
        - `home.html`: Main landing page (Home).
        - `education-certifications.html`: Education & Certifications page (shows your academic background and certifications).
        - `projects.html`: Projects showcase page (shows projects you have created).
        - `resume.html`: Resume page (links to or downloads your resume PDF).
        - `skills.html`: Skills overview page (lists your technical and soft skills).
- **LICENSE.md**: License file.
- **README.md**: This documentation file.

## Setup

To view the website locally:

1. Clone this repository or download the files.
2. Navigate to the `My-Portfolio-Website/Portfolio-Website/` directory.
3. Open `index/home.html` in your preferred web browser.

## Customization

* **Personal Information:** Update your details in `Portfolio-Website/index/home.html` and the respective HTML files within the `Portfolio-Website/index/` directory.
* **Meta Tags:**
    * In `Portfolio-Website/index/home.html`, replace the placeholder `og:url` with your live portfolio URL.
    * Replace the placeholder `og:image` with a URL to an actual preview image for your portfolio.
* **Styling:** Modify the CSS files in `Portfolio-Website/css/` (`common.css`, `projects.css`, `skills.css`, etc.) to change the appearance.
* **Contact Links:** Update the `href` attributes in the contact section and the "Hire Me" modal in `Portfolio-Website/index/home.html` with your actual social media and email links.
* **Resume PDF:** Place your resume PDF in an appropriate location (e.g., `Portfolio-Website/index/` or a dedicated `assets/` folder) and ensure the link in `Portfolio-Website/index/resume.html` points to the correct file name.

---

Feel free to further adjust the structure or add more details according to you!
If you have any feed back feel free to reach out to me.
