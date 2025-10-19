# Health Scan ZA Application (Frontend)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Netlify](https://img.shields.io/badge/Deployment-Netlify-00C7B7?style=flat-square&logo=netlify)](https://www.netlify.com/)

A client-side application built purely with **HTML, CSS, and Vanilla JavaScript**. It provides a clean, mobile-first user interface for scanning barcodes and consuming data from the external [Health Scan ZA API](https://YOUR-RENDER-APP-NAME.onrender.com/api). The UI is inspired by the Yuka mobile application.

---

## 📂 Project Structure

This project is entirely static and forms the presentation layer of the application.

---

## ⚙️ Key Technologies

| Technology | Role |
| :--- | :--- |
| **Vanilla JavaScript** | Handles all application logic, including the view state and API communication. |
| **QuaggaJS (CDN)** | Third-party library used for real-time barcode scanning via the device camera. |
| **Responsive CSS** | Ensures the **Yuka-style UI** and camera viewport are functional on all screen sizes. |

---

## 🛠️ Setup & Local Run

This is a static site and can be opened directly in a browser.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/YourUsername/health-scanner-frontend-repo.git
    cd health-scanner-frontend-repo
    ```
2.  Open `index.html` in your browser.

**Note:** For the **Camera Scan** feature to work, the page must be served over a local web server (e.g., VS Code's Live Server extension) or `http://localhost`, as browsers block camera access from direct `file://` paths.

---
