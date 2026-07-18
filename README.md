# StudentHub - College Academic Portal
A premium, modern, and highly accessible student intranet portal developed as a college front-end design practical.
StudentHub showcases the integration of **Semantic HTML5** elements and **CSS3** layout designs with **WCAG-compliant accessibility guidelines (A11y)**, providing a polished interface suitable for grading by university faculty.
---
## 🚀 Key Features
* **Glassmorphic Aesthetic**: Designed with a high-end dark blue, purple, and vibrant indigo color palette featuring semi-transparent cards, smooth transitions, and ambient glows.
* **Semantic Structure**: Built without excessive `<div>` wrapping, using HTML5 semantic elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`.
* **Strict Accessibility (A11y)**:
  * Includes a skip-to-main-content keyboard shortcut.
  * Clear visual focus indicators (`outline`) for keyboard navigation.
  * Complete ARIA roles, landmarks, and alt tags for screen readers.
  * Screen-reader friendly table scopes and form labels.
* **CSS-Only Responsive Menu**: A pure HTML+CSS collapsible hamburger menu using the checkbox hack (no JavaScript dependencies).
* **Pure HTML Collapsible Accordion**: Interactive accordion lists using `<details>` and `<summary>` styling.
* **Responsive Layouts**: Designed to adapt dynamically to Desktop, Tablet, and Mobile viewport resolutions using CSS Flexbox and Grid.
---
## 📁 Directory Structure
```text
StudentHub/
├── index.html         # Home page (Hero, News highlights, counters)
├── about.html         # Portal Background, Mission, Vision, and Dev Team
├── register.html      # Accessible student registration form
├── login.html         # Credentials sign-in layout
├── dashboard.html     # Academic workspace (Schedules, lists, courses)
├── events.html        # Campus events catalog with search filtering
├── profile.html       # Portfolio, skills badges, and certificates
├── contact.html       # Campus address, details directory, and maps
├── admin.html         # Portal moderation statistics and notice board
├── faq.html           # Accordion style support questions
├── feedback.html      # Portal feedback, star ratings, and review form
├── css/
│   └── style.css      # Consolidated stylesheet with root variables
└── images/
    ├── logo.png       # Minimalist brand logo
    ├── hero.jpg       # Students campus background
    ├── student.jpg    # Student avatar photo
    └── banner.jpg     # Abstract tech banner for announcements
```
---
## 🛠️ Technology Stack Used
* **Structure**: Semantic HTML5 markup
* **Styling**: Native CSS3 (Variables, Flexbox, Grid, Media Queries, Keyframe Animations)
* **Iconography**: Font Awesome (v6 Free CDN integration)
* **Typography**: Poppins (Google Fonts import)
---
## 💻 Running the Project Locally
No compilation, servers, or database setups are required. 
1. Clone or download this directory to your machine.
2. Locate the [index.html](index.html) file in the root directory.
3. Double-click [index.html](index.html) to run it directly inside your web browser (Chrome, Edge, Firefox, or Safari).
4. Navigate across all 11 pages using the header links or footer services map.
---
## 🌐 Deploying to GitHub Pages
This static repository is fully compatible with free hosting on **GitHub Pages**:
1. Upload this project folder to a new repository on your GitHub account.
2. Open the repository's **Settings** tab.
3. Click on **Pages** in the left navigation sidebar.
4. Set the build source to **Deploy from a branch** and choose the `main` (or `master`) branch.
5. Click **Save**. Within a few minutes, GitHub will publish a live link to showcase your portal.
