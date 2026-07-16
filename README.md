# Portfolio
A responsive, single-file personal portfolio website showcasing my skills, projects, work experience, education, and certifications — built with HTML5, CSS3, and vanilla JavaScript, featuring dark/light mode and smooth-scroll navigation.
Dhushyanth Challa — Developer Portfolio

A single-page, responsive personal portfolio website for Dhushyanth Reddy Challa, a final-year B.Tech CSE student and aspiring Full-Stack Developer / SDE. The site showcases his background, technical skills, work experience, education, certifications, and projects, with a built-in dark/light theme toggle and smooth-scrolling navigation.

Live demo: open dhushyanth-portfolio.html in any modern browser — no build step or server required.


✨ Features


Single-file build — the entire site (HTML, CSS, and JavaScript) lives in one .html file, so it's easy to host anywhere (GitHub Pages, Vercel, Netlify, or a plain static file server).
Responsive layout — adapts cleanly from desktop down to mobile, including a collapsible hamburger nav menu.
Light/Dark mode toggle — switch themes instantly via the sun/moon button in the navbar; styling is driven by CSS custom properties (:root / [data-theme="dark"]).
Smooth-scroll navigation — the navbar links (Home, About, Skills, Experience, Education, Projects, Contact) jump to their matching sections, with scroll offset so content isn't hidden behind the sticky nav.
Scroll-reveal animations — sections fade/slide into view as you scroll, powered by the IntersectionObserver API.
Structured content sections:

Hero — name, role, short bio, and call-to-action buttons (Resume, GitHub, LinkedIn)
About — profile photo and personal summary
Skills — categorized skill cards (languages, frameworks, tools, spoken languages, etc.)
Experience — timeline of internships and self-directed development work
Education — degree details plus a certifications grid (Oracle, IBM, AWS, Google Cloud, NPTEL, and more)
Projects — cards with descriptions, tech-stack tags, and links to live GitHub repositories
Contact — email, phone, location, and social links





🛠️ Tech Stack


HTML5 — semantic page structure
CSS3 — custom properties (theming), Flexbox/Grid layouts, transitions, and animations
Vanilla JavaScript — theme toggling, mobile menu, and scroll-reveal logic (no frameworks or dependencies)


📂 Project Structure

dhushyanth-portfolio.html   # Complete site — markup, styles, and scripts in a single file

🚀 Getting Started


Download / clone the file.
Open it directly — double-click dhushyanth-portfolio.html or open it in your browser.
To host it online, upload the file as-is to any static hosting provider:

GitHub Pages — push to a repo and enable Pages on the main branch.
Vercel / Netlify — drag-and-drop deploy, no configuration needed.





No package installation, build tools, or server-side code are required.

✏️ Customizing

Since everything lives in one file, updates are straightforward:

To change...Edit...Name, role, bio<header class="hero"> sectionProfile photo<div class="avatar"> in the About sectionSkills.skill-grid cards in the Skills sectionWork experience.timeline-card entries in the Experience sectionEducation & certifications.edu-grid and .cert-grid in the Education sectionProjects.project-grid cards in the Projects sectionContact info & social links.contact-grid in the Contact sectionColors / themeCSS custom properties under :root and [data-theme="dark"]

📄 License

This project is a personal portfolio belonging to Dhushyanth Reddy Challa. Feel free to reference the structure/design for your own portfolio, but please don't republish the content (name, bio, resume details) as your own.

📬 Contact


Email: dhushyanthreddychalla27@gmail.com
GitHub: github.com/dhushyanthreddychalla
LinkedIn: linkedin.com/in/dhushyanth-reddy-challa
