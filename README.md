# Advanced ATS-Optimized Resume Builder 📄✨

A comprehensive, fully responsive client-side web application that allows users to build, customize, and export professional resumes. Built with performance and Applicant Tracking Systems (ATS) in mind, this tool ensures resumes are semantically structured and visually appealing.

## 🚀 Features

* **Dynamic Multi-Section Form:** Easily input personal details, education, technical/soft skills, project details, and work experience.
* **Real-Time Data Handling:** Add or remove multiple degrees, experiences, and certifications on the fly without page reloads.
* **3 Distinct Templates:**
    * *Classic Single Column:* Highly ATS-friendly, best for traditional corporate roles.
    * *Modern Split:* A clean, two-column layout highlighting skills and contacts instantly.
    * *Creative Accent:* Bold headers and distinct sections tailored for design and tech roles.
* **Multiple Export Options:** Download the final rendered resume strictly on a single A4 page in PDF, JPEG, or JPG formats.
* **PWA Ready:** Includes a Web App Manifest and Service Worker, allowing the application to be installed as a standalone app on Android and desktop devices.
* **AI Integration Ready:** Designed with conceptual hooks to easily integrate AI APIs (like OpenAI or Gemini) for automated text enhancement and professional summaries.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Libraries:** [html2pdf.js](https://ekoopmans.github.io/html2pdf.js/) (for rendering DOM elements to PDF and Images)
* **Architecture:** Progressive Web App (PWA)

## 💻 Getting Started

To run this project locally, no complex build tools or servers are required.

1.  **Clone or Download the Repository:**
    Extract the files into a local directory.
2.  **Ensure File Structure:**
    Make sure the following files are in the same root folder:
    * `index.html` (Main application logic and UI)
    * `manifest.json` (PWA configuration)
    * `sw.js` (Service Worker for offline caching)
3.  **Run the App:**
    Simply open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
    *(Note: To fully test the PWA installation features, you may need to serve the folder through a local server extension like VS Code's "Live Server").*

## 🔮 Future Enhancements

* **Backend Integration:** Connect to a PHP and MySQL backend to allow user authentication, data saving, and resume editing at a later date.
* **Live AI Endpoints:** Connect the existing "Enhance with AI" buttons to a live API for real-time text polishing.
* **Custom Color Themes:** Add a color picker to allow users to override the default template accent colors.

---

## 👨‍💻 Developer

Designed and developed by **Vinay Kumar**. 

*A Full-Stack Web Developer with a strong focus on building efficient, user-centric applications using HTML, CSS, JavaScript, PHP, and MySQL, alongside an active interest in Artificial Intelligence and Machine Learning implementations.*
