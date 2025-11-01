# Kalvium Student UI Prototype

This repository contains the front-end prototype for the Kalvium Student Portal, a centralized dashboard for students to access their academic and administrative tools.

## 🚀 Key Features

The UI is designed as a single-page application prototype, linking together core student resources:

* **Dashboard (`index.html`):** A landing page displaying student profile information (name, university, squad, course) and quick links to all Kalvium applications.
* **Livebooks (`livebooks.html`):** The course catalog, allowing students to access and track their progress in various subjects, organized by semester.
* **Dojo (`dojo.html`):** A dedicated section for coding workouts across multiple languages (C++, Python, Java, Javascript) with a belt progress system.
* **Markers (`markers.html`):** A performance dashboard displaying key metrics like Professionalism score, Course score, Coding level, and Project score.
* **Showcase (`showcase.html`):** A student profile designed to highlight skills, projects, certifications, and internship experiences.
* **My Internships (`internships.html`):** Tracks internship details, including organization, attendance, and worklogs.
* **Apply for Leave (`leave.html`):** A form for students to submit leave intimations to Program Managers and Technical Mentors.

***

## 📚 Livebooks Functionality & Navigation

This section details the functional course within the Livebooks section and how to navigate through it.

### Functional Course

Of the Livebooks listed in `livebooks.html`, only one is fully functional and linked to a detailed course page:

* **✅ Front-End Web Development - Fundamentals**

All other Livebook cards (e.g., "Introduction to Prompt Engineering," "Problem Solving Using Programming - Fundamentals") link to a placeholder URL (`#`) and will display a **"Page Not Implemented"** modal when clicked.

### Navigation Flow

The step-by-step navigation for the "Front-End Web Development - Fundamentals" course is as follows:

1.  **Course Card:** Click the **"Front-End Web Development - Fundamentals"** card on `livebooks.html`. This leads to the course details page (`fewd.html`).
2.  **Course Details (`fewd.html`):** The **"Learning Path"** tab is active by default, with **"Module I: HTML, CSS Basics"** automatically expanded.
3.  **Lesson 1.1 Choice (`fewd.html` -> `fewd-l1.html`):** Click the link for **"1.1 Course Overview & Orientation"**. This leads to the lesson choice page (`fewd-l1.html`).
4.  **Lesson Content (`fewd-l1.html` -> `fewd-l1-c.html`):** Click the large **"Lesson"** card on the choice page.
    * *Note:* The "Revision Notes" card is disabled.
5.  **Final Page (`fewd-l1-c.html`):** This page displays the full course overview content. Navigation is provided via a sticky sidebar, and the final section is a **"Quiz Time"** card.
    * *Limitation:* Clicking the link for the next lesson ("What is Frontend web development?") points back to a non-implemented lesson (1.2) on the parent page (`fewd.html`).

***

## 🛠️ Technology Stack

The UI is built using modern web development standards and popular front-end frameworks for rapid prototyping:

* **Styling Framework:** [Tailwind CSS](https://tailwindcss.com/)
* **Iconography:** [Lucide Icons](https://lucide.dev/)
* **Font:** Inter (via Google Fonts)

***

## 📂 File Structure Overview

| File | Description |
| :--- | :--- |
| `index.html` | Main Student Dashboard/Portal landing page. |
| `livebooks.html` | Course overview and semester selector. |
| `fewd.html` | Detailed view for the "Front-End Web Development - Fundamentals" course. |
| `fewd-l1.html` | Lesson 1.1 choice screen (Lesson or Revision Notes). |
| `fewd-l1-c.html` | Full content page for Lesson 1.1. |
| `dojo.html` | Coding Workouts section. |
| `markers.html` | Performance markers and scores display. |
| `showcase.html` | Student's professional profile page. |
| `internships.html` | Internship tracking page. |
| `leave.html` | The leave application form. |
| `alu.jpeg` | University logo asset. |

***

## 🚀 Getting Started (Local Setup)

To view the prototype locally, simply open the `index.html` file in your web browser. Since all styling and scripts are loaded via CDNs, no build steps are required.
