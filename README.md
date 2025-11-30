# 🌟 Tran Minh Son - Personal Website Portfolio

This repository contains the source code for the personal website of **Tran Minh Son**, a **Creative Coder**. The site is a central hub to view his profile, skills, and featured projects.

---

## 🚀 Key Features

* **Core Pages:** About page, contact page, index page, and project page.
* **Navigation:** Consistent navbar linking to all main pages.
* **Styling:** Uses external CSS (`assets/styles.css`).
* **Refresh:** All pages are set to automatically refresh every **3 seconds** (`<meta http-equiv="refresh" content="3">`).

---

## 🛠️ Technology Stack & Skills

### Core Technologies

The website is built using fundamental web technologies:
* **HTML5**
* **CSS** (linked via `assets/styles.css`)

### Technical Skills Highlighted

| Category | Skills |
| :--- | :--- |
| **Frontend** | HTML5, CSS3  |
| **Backend/DB** | Python, Node.js, MySQL, MongoDB |
| **Tools** | Git |

---

## 🏗️ Featured Projects

The **Projects** page showcases the following work:

### 1. E-commerce Website
* **Description:** Full-featured online store with user auth, shopping cart, and payment integration.
* **Technologies:** HTML, CSS, JavaScript, **Node.js, MongoDB**.
* **Key Features:** Responsive design, user login, searchable product catalog.

### 2. Recipe Finder App
* **Description:** A user-friendly mobile app for finding recipes quickly.
* **Technologies:** HTML, CSS, JavaScript, Node.js, MongoDB, Git, **Python**.

---

## 📝 About the Coder

**Tran Minh Son** describes himself as:

> "A person who loves building amazing web experiences with clean code and creative solutions."

He enjoys listening to music, sight-seeing walks, and relaxing.

---

## 📞 Contact Information

The contact page includes a form (backend integration required for submission) and direct details:

* **Email:** `sont9830@gmail.com`
* **Phone:** `0916619890`
* **Location:** `Hanoi`
* **Copyright:** `© ALL OF THE RIGHTS RESERVED`

---

###  Explaining the website structure and testing instructions.
File/Folder	Purpose	Description
index.html	Homepage	The main entry point with a brief introduction.
about.html	Profile Page	Details the coder's profile, interests, and technical skills.
projects.html	Portfolio Page	Showcases featured projects (E-commerce site, Recipe App).
contact.html	Contact Page	Provides a contact form and direct contact details.
favicon.png	Site Icon	The small icon displayed in browser tabs.
assets/styles.css	Styling	Contains all the CSS rules for the entire website's presentation.

Follow these steps to ensure the website is functioning correctly after deployment or when viewed locally
1. Local Setup Check
Clone the Repository: Ensure the project files are successfully downloaded to your local machine.
2. Local Setup Check
Clone the Repository: Ensure the project files are successfully downloaded to your local machine.
3. Local Setup Check
Clone the Repository: Ensure the project files are successfully downloaded to your local machine.

2. Navigation & Link Testing
Test all navigation links to ensure smooth travel between the four main pages
Click "About" in the navbar.Page loads about.html.
Click "Project" in the navbar.Page loads projects.html.
Click "Contact" in the navbar.Page loads contact.html.
Click "Tran Minh Son" (Home) in the navbar.Page loads index.html.

3. Page Content Verification
Confirm that the primary content loads correctly on each page:

about.html: Verify the Avatar Image is visible and the Technical Skills List (HTML5, Python, React, etc.) is displayed.

projects.html: Verify details for both the E-commerce Website and Recipe Finder App are present and formatted correctly.

contact.html: Verify the Contact Form elements (NAME, EMAIL, REPLY fields, Submit button) and the Direct Contact Information (Email, Phone, Location) are visible.

4. Form Functionality (Note)
Warning: The HTML for the contact form currently lacks a functional backend script (<form action="">).

Test: When clicking the Submit button on contact.html, the browser should attempt to submit, but the data will not be processed or sent to an email unless a server-side handler (e.g., Node.js, PHP, or a service like Netlify Forms) is implemented. This is expected behaviour based on the current code.