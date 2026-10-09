# 🏫 Ghazali Public School — Website & Admin Dashboard

<p align="center">
  <strong>A responsive school website and browser-based content management project for Ghazali Public School, Hathian, Mardan, Pakistan.</strong>
</p>

<p align="center">
  <a href="https://ghazalipublicschoolhathian.netlify.app"><strong>🌐 Visit Live Website</strong></a>
</p>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?logo=css&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
  <img alt="Netlify" src="https://img.shields.io/badge/Deployed%20on-Netlify-00C7B7?logo=netlify&logoColor=white" />
</p>

## 📖 About the Project

This project is a digital school website designed around **Ghazali Public School**, located in **Hathian, District Mardan, Khyber Pakhtunkhwa, Pakistan**. It brings school information into one accessible online space and includes an administrative interface for managing demonstration content.

The website is built with **HTML, CSS, and vanilla JavaScript** and is hosted on **Netlify**. The project is also part of my hands-on learning in web development and AI-assisted development.

> **Live demo:** https://ghazalipublicschoolhathian.netlify.app

## ✨ Features

### Public website

| Page | What it contains |
| --- | --- |
| **Home** | School introduction, highlights, statistics, and navigation |
| **About** | School story, mission, vision, and leadership content |
| **Academics** | Academic programs and curriculum information |
| **Admissions** | Admission process, requirements, and guidance |
| **Faculty** | School leadership and teaching staff profiles |
| **Results** | Class 9 and 10 board-result presentation and records interface |
| **News** | Announcements, school notices, and events |
| **Gallery** | School photo categories and gallery browsing |
| **Alumni** | Alumni stories and achievements section |
| **Contact** | Contact details and inquiry form interface |

### Admin dashboard

The project includes an `admin.html` interface designed for managing content such as:

- News and announcements
- Student and class records
- Board examination results
- Faculty and staff profiles
- Alumni success stories
- Gallery photos
- School details and site content
- JSON backup/export workflows

**Important:** This is a browser-based demonstration dashboard, not a production-grade school information system. Local browser edits do **not** automatically update the public Netlify site for everyone. Published changes require a deployment/content-update workflow. Do not store real student records or sensitive personal information in this demo.

## 🛠️ Technology Stack

| Technology | Use |
| --- | --- |
| HTML5 | Structure of the web pages |
| CSS3 | Layout, responsive design, and styling |
| JavaScript | Interactive features and dynamic content |
| Browser localStorage | Local editing and demo data persistence |
| JSON | Content export and data files |
| Canvas API | Client-side image processing in the admin workflow |
| Netlify | Static website hosting |

No large frontend framework is required for the current version.

## 📁 Project Structure

```text
ghazali-public-school/
├── index.html
├── about.html
├── academics.html
├── admissions.html
├── alumni.html
├── contact.html
├── faculty.html
├── gallery.html
├── news.html
├── results.html
├── admin.html
├── site-content.json
├── css/
│   ├── style.css
│   └── admin.css
├── js/
│   ├── main.js
│   ├── admin.js
│   ├── storage.js
│   └── data/
└── images/
```

*The structure above describes the project referenced by the supplied source and existing README. Ensure these CSS, JavaScript, and image folders are included in the repository when publishing it.*

## 🚀 Run Locally

1. Clone or download the repository.
2. Open the project folder in VS Code or another editor.
3. Start a local static server, for example with Python:

   ```bash
   python -m http.server 8000
   ```

4. Visit `http://localhost:8000` in your browser.
5. Open `http://localhost:8000/admin.html` to inspect the demonstration dashboard.

A local server is recommended so JavaScript can load JSON content reliably.

## ☁️ Deployment

This project is published using **Netlify**:

1. Push the complete site files to a GitHub repository.
2. Connect the repository to Netlify, or deploy the complete site folder manually.
3. Set the publish directory to the folder containing `index.html`.
4. Redeploy after changing the published files or `site-content.json`.

**Live site:** [Ghazali Public School](https://ghazalipublicschoolhathian.netlify.app)

### How content updates work

```text
Admin dashboard
      ↓
Browser-local edits / JSON export
      ↓
Update the site's published content files
      ↓
Deploy the updated site to Netlify
      ↓
Visitors see the published changes
```

For **instant, shared updates without redeploying**, a future version would need a real backend or hosted database, secure authentication, and appropriate file storage. Those features should not be assumed to exist in the current static version.

## 🔒 Security & Data Privacy

- The current dashboard includes demonstration access controls; **client-side passwords are not secure authentication**.
- Replace demo access with server-verified authentication before any real administrative use.
- Do not upload private student data, personal contact information, or student photos without appropriate permission.
- Validate school statistics, results, staff details, and announcements before publishing them as official information.

## 🧭 Future Improvements

- Secure administrator login and role-based permissions
- Cloud-backed content management with live updates
- Reliable image uploads and storage
- Better form submission handling and spam protection
- Accessibility and performance improvements
- Mobile-friendly dashboard refinements
- Automated deployment and testing

These are **planned improvements**, not claims about existing functionality.

## 👨‍💻 Project Author

**Ubaid Rahman**  
BS Computer Science Student  
Interested in web development, Python, artificial intelligence, and building useful digital solutions.

I developed this as a practical learning project, using development tools and AI assistance where helpful, while continuing to strengthen my own programming skills.

## 📝 Project Status & Disclaimer

**Status:** Live demonstration / ongoing development.

Some sections of the supplied project contain **sample or placeholder** school history, photographs, statistics, student achievements, admissions details, and alumni profiles. They should not be treated as verified official records until reviewed and approved by the school.

This README does not imply that the school has officially endorsed every demonstration feature or data entry.

---

<p align="center"><strong>Built for learning, community, and practical web development.</strong></p>
