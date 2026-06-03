```markdown
# Project Title: 14 Life Below Water 🌊

## Table of Contents
1.  [Introduction](#introduction)
2.  [Project Overview & Purpose](#project-overview--purpose)
3.  [Team Members & Roles](#team-members--roles)
4.  [Key Features](#key-features)
5.  [Technology Stack](#technology-stack)
6.  [Getting Started (Local Setup)](#getting-started-local-setup)
7.  [Project Structure](#project-structure)
8.  [Page Breakdown](#page-breakdown)
9.  [Challenges & Learnings](#challenges--learnings)
10. [Future Enhancements](#future-enhancements)
11. [License](#license)

---

## Introduction

Welcome to **14 Life Below Water**, a collaborative web development project created to raise awareness about Sustainable Development Goal 14 (SDG 14) - Life Below Water. This website serves as an educational platform to highlight the critical importance of marine conservation, the threats facing our oceans, and the innovative solutions we can all adopt to protect this vital resource.

The project was completed as a first-year university web development coursework, demonstrating fundamental front-end development skills, collaborative version control, and user-centered design.

## Project Overview & Purpose

The primary goal of this website is to **educate, engage, and inspire action** for ocean conservation. It aims to provide clear, accessible information on:

- The crucial role oceans play in global climate, biodiversity, and human livelihoods.
- The major threats to marine ecosystems, such as plastic pollution, overfishing, and coral bleaching.
- Sustainable practices and innovative technologies that can help restore ocean health.
- Concrete opportunities for individuals to get involved, from volunteering to providing feedback.

The ultimate message is one of hope and action: by working together, we can ensure a sustainable future for our blue planet.

## Team Members & Roles

This project was developed by a team of four students, each responsible for specific pages and functionalities.

| Student Name | Role (Student #) | UOW ID      | Key Responsibilities                                                                                             |
| :----------- | :--------------- | :---------- | :--------------------------------------------------------------------------------------------------------------- |
| **Sasindu Anjula**   | Student 1         | w2119786    | Splash Screen, Volunteer Page, Content Page 1, Page Editor & Validation for assigned pages.                      |
| **Nimuthu Lakdina**  | Student 2         | w2119779    | Home Page, Table Page, Content Page 2, Page Editor & Validation for assigned pages.                              |
| **Wathmi Kodippili** | Student 3         | w2120588    | Feedback Form, Team Page, Content Page 3, Page Editor & Validation for assigned pages.                           |
| **Dasuni Navodya**   | Student 4         | w2119785    | User Profile Page, Sitemap Page, Content Page 4, Page Editor & Validation for assigned pages.                    |

## Key Features

- **Splash Screen:** An animated landing page with a team introduction that automatically redirects to the home page.
- **Responsive Navigation:** A consistent header and footer across all pages for seamless user experience.
- **Dynamic Content Pages:** Four detailed content sections (`content_ST1.html` to `content_ST4.html`) that are loaded into a central frame on the main `content.html` page, complete with a sidebar for easy navigation.
- **Interactive Volunteer Hub:** A page listing volunteer opportunities with hover-effect cards, user ratings, a star-based review section, and a feedback form.
- **Data-Rich Table:** A styled HTML table presenting key metrics for various marine conservation efforts.
- **Team Roster:** A "Team" page with member photos and hidden information that appears on hover.
- **User Feedback System:** A comprehensive feedback form with validation for user input, including text fields, radio buttons, checkboxes, and a star-rating widget.
- **Personalized Profile:** A user profile page with a three-panel layout, skill bars, a weekly availability table, and a contact form.
- **Site Map:** A graphical, button-based sitemap for easy navigation of all project pages.
- **Visual Polish:** Consistent use of a background video (muted and looping) to create an immersive ocean theme, along with subtle CSS transitions and hover effects.

## Technology Stack

- **HTML5:** For structuring all web pages.
- **CSS3:** For styling, layout (Flexbox, Grid), animations, and responsive design. A global `style.css` file is used for core styles, with page-specific styles embedded.
- **Google Fonts:** Used to import the 'Poppins' font family for a modern and clean typography.
- **Local Media:** All images and videos are stored locally in the `images/` and `videos/` directories.

## Getting Started (Local Setup)

To view and run this project on your local machine, follow these simple steps:

1.  **Clone the Repository:**
    ```bash
    git clone <your-repository-url>
    ```
2.  **Navigate to the Project Directory:**
    ```bash
    cd <repository-name>
    ```
3.  **Open the Homepage:**
    The easiest way to view the website is to open the `home.html` file directly in your web browser.
    - **Option A (Recommended):** Use a local development server. If you have Python installed, you can run:
        ```bash
        # Python 3
        python -m http.server 8000
        ```
        Then open your browser and go to `http://localhost:8000`.
    - **Option B:** Simply double-click the `home.html` or `index.html` file. Note that some advanced features might be restricted due to browser security policies (CORS), but the core functionality will work.

> **Important:** The entry point of the site is `index.html`, which is a splash screen. It automatically redirects to `home.html` after 4 seconds.

## Project Structure

The project is organized as follows:

```
.
├── images/                  # All image assets (.jpg, .jpeg, .png)
├── videos/                  # Video assets (.mp4)
├── content_ST1.html         # Content page by Student 1
├── content_ST2.html         # Content page by Student 2
├── content_ST3.html         # Content page by Student 3
├── content_ST4.html         # Content page by Student 4
├── content.html             # Main container page for all content sections
├── feedback.html            # User feedback form page
├── home.html                # Main landing/home page
├── index.html               # Initial splash screen (redirects to home.html)
├── pageEditor_ST1.html      # Page Editor & documentation for Student 1
├── pageEditor_ST2.html      # Page Editor & documentation for Student 2
├── pageEditor_ST3.html      # Page Editor & documentation for Student 3
├── pageEditor_ST4.html      # Page Editor & documentation for Student 4
├── pageEditor_validator.css # Shared CSS for editor and validator pages
├── profile.html             # User profile page
├── README.md                # This file
├── sitemap.html             # Site map page
├── style.css                # Global stylesheet for headers, footers, and core elements
├── table.html               # HTML table data page
├── team.html                # Team member introduction page
├── validation_ST1.html      # HTML/CSS validation reports for Student 1
├── validation_ST2.html      # HTML/CSS validation reports for Student 2
├── validation_ST3.html      # HTML/CSS validation reports for Student 3
├── validation_ST4.html      # HTML/CSS validation reports for Student 4
└── volunteer.html           # Volunteer opportunities page
```

## Page Breakdown

- `index.html`: The entry point. A splash screen that redirects to the homepage.
- `home.html`: The main page with the mission statement and cards linking to the four content sections.
- `content.html`: A master page that embeds `content_ST1.html`, `content_ST2.html`, `content_ST3.html`, and `content_ST4.html` using iframes. It includes a sidebar for quick navigation.
- `volunteer.html`: Lists various volunteer programs in a responsive card grid.
- `team.html`: Displays the project team members with hidden details on hover.
- `table.html`: Presents a data table on marine conservation metrics.
- `feedback.html`: A detailed form for users to submit feedback, suggestions, and ratings.
- `profile.html`: A sample user profile with bio, skills, goals, and contact form.
- `sitemap.html`: A navigational page using buttons to link to all major site sections.
- `pageEditor_ST*.html`: Each student's documentation page explaining their technical implementation, accessibility considerations, challenges, and references.
- `validation_ST*.html`: Each student's page showing W3C HTML/CSS validation screenshots for their respective pages.

## Challenges & Learnings

- **Consistent Styling & Responsiveness:** Implementing a uniform look across multiple pages developed by different team members was a key challenge. The solution was to create a shared `style.css` file and use relative units (%, vw) and Flexbox to ensure responsiveness.
- **Video Background Optimization:** Using a full-screen, looping video background on several pages (e.g., `home.html`, `volunteer.html`) risked performance issues. This was mitigated by using the `muted` and `playsinline` attributes and ensuring the video file was optimized for web use.
- **Semantic HTML & Accessibility:** The team learned to prioritize accessibility by using semantic tags (`<header>`, `<nav>`, `<main>`, `<footer>`), providing `alt` text for all images, and ensuring proper form labels. This made the site more usable for screen readers.
- **Collaborative Workflow:** Managing a project with four contributors required clear communication, defined roles (as per the table above), and a structured file system to avoid conflicts.

## Future Enhancements

- **Backend Integration:** Connect the feedback and contact forms to a server-side script to handle email submissions and store data in a database.
- **JavaScript Interactivity:** Add JavaScript for dynamic features like real-time form validation without page reload, a working star-rating system in the feedback form, and interactive maps on the volunteer page.
- **User Accounts:** Implement a login system so users can save their profile, track their volunteering history, and leave persistent reviews.
- **Content Management System (CMS):** Migrate the static content to a CMS to allow for easy updates and additions of new articles or volunteer opportunities.

## License

This project is for educational purposes as part of a university coursework. All media (images, videos) are assumed to be used with permission or for educational, non-commercial use.

---
**Created with 💙 for a healthier ocean.**
```
