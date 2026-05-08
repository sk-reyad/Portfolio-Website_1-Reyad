# Portfolio Website 1 Reyad

# Modern Personal Portfolio Website

A sleek, fully responsive, and interactive personal portfolio website designed to showcase personal identity, academic background, skills, experience, services, creative works, and contact information in one clean digital space.

This project is built using **HTML**, **CSS**, and **Vanilla JavaScript**. It features a modern dark theme, red accent color, interactive About tabs, responsive layouts, smooth hover animations, portfolio image overlays, a mobile side menu, and contact form integration.

**Live Demo:** [Vercel Deployment](https://portfolio-website-1-reyad.vercel.app/)

**Source Code:** [GitHub Repository](https://github.com/sk-reyad/Portfolio-Website_1-Reyad)

**Alternative Demo:** [GitHub Pages](https://sk-reyad.github.io/Portfolio-Website_1-Reyad/)

---

## Overview

**Portfolio Website 1 Reyad** is a personal portfolio website created to professionally introduce **SK Reyad Ali** as a Computer Science student, frontend learner, IT professional, graphic designer, social media manager, and digital marketing enthusiast.

The website presents important personal and professional information through a structured one-page layout. It includes a hero section, About Me section, Skills/Experience/Education tabs, Services section, Portfolio section, Contact section, social links, and a downloadable CV option.

The design follows a modern dark UI style with bold red highlights, giving the portfolio a strong visual identity. This project demonstrates practical frontend development skills such as semantic HTML structure, responsive CSS layout, CSS Grid, Flexbox, JavaScript DOM manipulation, interactive tabs, mobile navigation, hover transitions, and static website deployment.

---

## Features

* Fully responsive personal portfolio website
* Modern dark UI with red accent color
* Hero section with name, role, and location
* Smooth navigation between page sections
* Interactive About section tabs:

  * Skills
  * Experience
  * Education
* Detailed personal introduction section
* Skills list including:

  * Graphics Design
  * Social Media Managing
  * Digital Marketing
  * OOP in Java
  * Web Development
* Experience timeline connected to Red Network LTD.
* Education timeline showing academic background
* Services section with four service cards:

  * Graphics Designs
  * Social Media Managing
  * Digital Marketing
  * Web Development
* Portfolio / My Works section with creative work cards
* Image overlay effect on portfolio items
* Hover animations for services, buttons, navigation links, social icons, and portfolio cards
* Contact section with email and phone information
* Social media icon links
* Download CV button
* Contact form integration using Web3Forms
* Mobile-friendly sliding side menu
* Separate mobile header background image
* Clean footer with copyright text
* Built without frameworks or external build tools

---

## Technologies Used

* **HTML5** — for the website structure, sections, navigation, content layout, links, form, and portfolio content
* **CSS3** — for dark theme styling, responsive layout, CSS Grid, Flexbox, hover effects, transitions, media queries, and visual design
* **Vanilla JavaScript** — for interactive About tabs and mobile side-menu functionality
* **Google Fonts** — for custom typography using fonts such as Mulish and Science Gothic
* **Web3Forms** — for handling contact form submissions without a custom backend
* **Vercel** — for live website deployment
* **GitHub Pages** — as an alternative static deployment platform

---

## What I Learned

While building this project, I practiced creating a complete personal portfolio website from scratch using only HTML, CSS, and JavaScript.

I learned how to organize a webpage into meaningful sections such as Home, About, Services, Portfolio, and Contact. This helped me understand how a real personal website should guide visitors from introduction to skills, then to work samples and contact options.

The About section helped me practice JavaScript-based tab switching. Instead of displaying all information at once, the website separates Skills, Experience, and Education into clickable tabs. This improved my understanding of DOM selection, class manipulation, and interactive content display.

I also practiced responsive web design. The website uses CSS media queries to adjust the layout for smaller screens. On mobile devices, the regular navigation is replaced with a sliding side menu, which helped me understand how responsive navigation systems work.

The Services and Portfolio sections helped me improve my use of CSS Grid, card layouts, hover effects, transitions, and image overlays. These design patterns are commonly used in modern portfolio and agency websites, so building them manually strengthened my frontend layout skills.

The contact form integration helped me understand how a static frontend website can still collect form submissions using a third-party service like Web3Forms. This is useful because it allows the project to have practical contact functionality without needing a custom backend server.

Overall, this project helped me build confidence in turning a personal brand idea into a complete, responsive, and interactive web portfolio.

---

## Project Structure

```text
Portfolio-Website_1-Reyad/
│
├── assets/
│   ├── header.jpg
│   ├── phoneheader.jpg
│   ├── logo / icons / portfolio images
│   └── other visual assets
│
├── index.html
├── style.css
├── script.js
└── README.md
```

### `index.html`

This file contains the main structure of the portfolio website. It includes the navigation menu, hero section, About section, Skills/Experience/Education tab content, Services section, Portfolio section, contact information, contact form, social links, CV download link, and footer.

### `style.css`

This file controls the complete visual design of the website. It includes the dark background theme, red accent color, typography, layout spacing, navigation styling, responsive grid systems, service cards, portfolio overlays, contact form styling, button effects, hover animations, and mobile responsiveness.

### `script.js`

This file handles the interactive behavior of the website. It includes the JavaScript logic for switching About tabs and opening or closing the mobile side menu.

### `assets/`

This folder stores the images and icons used throughout the website, including the desktop header image, mobile header image, logo, service icons, portfolio images, contact icons, and social media icons.

---

## How It Works

The website is built as a single-page portfolio. The navigation links take users to different sections of the same page, such as Home, About, Services, Portfolio, and Contact.

The hero section introduces the owner of the portfolio with a strong first impression. It displays the name, role, and location over a custom background image.

The About section contains a personal introduction and an interactive tab system. By clicking **Skills**, **Experience**, or **Education**, JavaScript removes the active class from the previous tab and applies it to the selected tab. This changes the visible content without reloading the page.

The Services section uses a responsive CSS Grid layout. Each service is displayed as a card with icons, title, description, and a Learn More link. When a user hovers over a service card, the card changes background color and moves upward slightly, creating a modern interactive effect.

The Portfolio section also uses a grid layout. Each work item contains an image and an overlay layer. When the user hovers over a portfolio item, the image slightly zooms in and the overlay appears with project information and a link icon.

The Contact section includes email, phone number, social links, a CV download button, and a contact form. The form is connected with Web3Forms, allowing visitors to send messages without requiring a custom backend.

For smaller screens, the website uses a mobile side menu. JavaScript changes the right position of the menu to show or hide it, creating a sliding navigation effect.

---

## Key Sections

### Hero Section

The hero section creates the first impression of the website. It includes the name **Reyad**, the role **Computer Science Student**, and the location **Bangladesh**. A custom background image is used to make the section visually strong.

### About Me Section

The About section introduces Reyad as a BSc Computer Science student at BRAC University with interests in technology, innovation, problem-solving, software development, and future career growth.

It also includes three interactive content areas:

* **Skills**
* **Experience**
* **Education**

### Services Section

The Services section presents the areas of work and interest:

* Graphics Designs
* Social Media Managing
* Digital Marketing
* Web Development

Each service is displayed using a card-based layout with icons and hover animation.

### Portfolio Section

The Portfolio section highlights sample creative works such as:

* Package Rate Design
* Social Media Post Design
* Awareness Post Design

Each portfolio item uses an image overlay effect to make the project presentation more engaging.

### Contact Section

The Contact section gives visitors a direct way to reach out. It includes email, phone number, social icons, CV download option, and a contact form.

---

## Design Highlights

The design focuses on a modern personal-branding style.

Key design choices include:

* Dark navy background color
* Strong red accent color
* Large bold section headings
* Red highlight inside heading text
* Smooth underline animation on navigation links
* Card-based Services section
* Image-based Portfolio section
* Hover overlay effect for work items
* Smooth button hover transitions
* Responsive CSS Grid layouts
* Mobile-specific header image
* Sliding mobile navigation menu
* Clean spacing and readable typography

---

## Responsive Design

The website is designed to work across different screen sizes.

On desktop, the layout uses wider spacing, horizontal navigation, side-by-side About columns, service grids, portfolio grids, and a two-column contact layout.

On mobile screens, the website adjusts by:

* Using a mobile header image
* Reducing hero text size
* Showing a hamburger menu
* Opening navigation as a side menu
* Stacking About columns vertically
* Adjusting tab spacing
* Stacking contact content into one column
* Reducing footer text size

This makes the website more comfortable to view on phones and smaller devices.

---

## Setup and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/sk-reyad/Portfolio-Website_1-Reyad.git
```

### 2. Navigate to the Project Folder

```bash
cd Portfolio-Website_1-Reyad
```

### 3. Open the Website

Open the `index.html` file in any modern web browser.

No installation, package manager, build tool, or server setup is required because the project is built with plain HTML, CSS, and JavaScript.

---

## Deployment

This project is suitable for static hosting platforms because it does not require a backend server.

Current deployment links:

* **Vercel Live Demo:** [https://portfolio-website-1-reyad.vercel.app/](https://portfolio-website-1-reyad.vercel.app/)
* **GitHub Pages Demo:** [https://sk-reyad.github.io/Portfolio-Website_1-Reyad/](https://sk-reyad.github.io/Portfolio-Website_1-Reyad/)
* **GitHub Repository:** [https://github.com/sk-reyad/Portfolio-Website_1-Reyad](https://github.com/sk-reyad/Portfolio-Website_1-Reyad)

---

## Browser Support

This website works best in modern browsers such as:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

Because the project uses standard HTML, CSS, and Vanilla JavaScript, it should work smoothly on most modern desktop and mobile browsers.

---

## Current Limitations

* Some service and portfolio descriptions still use placeholder text and can be replaced with final project-specific descriptions.
* The website is currently static, so portfolio items must be updated manually in the HTML file.
* The contact form depends on Web3Forms for message submission.
* The mobile menu works well, but accessibility can be improved with ARIA labels and better keyboard support.
* The portfolio section can be expanded with more real project details, technologies used, and live links.

---

## Future Improvements

Possible future improvements include:

* Replace placeholder service descriptions with final professional content
* Add more real web development projects to the Portfolio section
* Add project live demo and source code links inside each portfolio card
* Improve accessibility with ARIA labels and keyboard navigation support
* Add a dark/light theme toggle
* Add form validation and success/error message feedback
* Add animation on scroll for smoother section appearance
* Add a dedicated Projects section for GitHub repositories
* Add a testimonial or client feedback section
* Improve SEO using meta tags, Open Graph tags, and structured page descriptions
* Add a downloadable PDF resume stored directly inside the project
* Add active navigation highlighting while scrolling

---

## Want a Website Like This?

This website template is fully customizable. Whether you are a developer, designer, freelancer, student, or business owner, every piece of information, color, image, section, and layout can be customized to fit your personal brand or business needs.

If you are interested in purchasing a custom version of this website, I am available for freelance work.

Get in touch with me to start your project:

* **Email:** [skreyad2016@gmail.com](mailto:skreyad2016@gmail.com)
* **WhatsApp:** [+880 1955 448893](http://wa.me/+8801955448893)
* **LinkedIn:** [SK Reyad Ali](http://www.linkedin.com/in/sk-reyad)
* **Behance:** [My Design Portfolio](https://www.behance.net/skreyad1)
* **GitHub:** [@sk-reyad](http://github.com/sk-reyad)

---

## Author

**SK Reyad Ali**

---

## Contact

* Email: [skreyad2016@gmail.com](mailto:skreyad2016@gmail.com)
* LinkedIn: [https://www.linkedin.com/in/sk-reyad/](https://www.linkedin.com/in/sk-reyad/)
