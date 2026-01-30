 # 🎓 WBJEE 2026 Rank vs College Predictor
  
  **An aesthetic, AI-driven tool to analyze marks, predict GMR, and suggest top engineering colleges in West Bengal.**

  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
    <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white" />
  </p>

---

## 🚀 Overview

The **WBJEE 2026 Rank Predictor** is a modern, responsive web application designed to help engineering aspirants estimate their General Merit Rank (GMR) based on their actual exam or expected scores. 

Beyond simple prediction, it provides a **comprehensive dashboard** featuring subject-wise analysis, college probability based on previous year cutoffs, and a downloadable PDF report card.

## 🔗Live Project Link:
[https://wbjee-css.vercel.app/]

## ✨ Key Features

* **🎯 Precision Rank Algorithm:** Uses a power-law regression model (`Marks vs Rank`) to estimate GMR and Category Ranks (SC/ST/OBC/TFW).
* **📊 Visual Analytics:** Integrated **Chart.js** doughnut chart to visualize the Marks Obtained vs. Marks Lost ratio.
* **🏫 College Matcher:** Automatically filters top colleges (Jadavpur, Calcutta Univ, Heritage, Techno Main, etc.) based on the predicted rank and category.
* **🌓 Dark/Light Mode:** A toggleable theme with a sleek "Glassmorphism" UI and floating background animations.
* **📄 PDF Export:** One-click download of the analysis report using **html2canvas** and **jsPDF**.
* **⏳ Exam Countdown:** A live countdown timer set for the WBJEE 2026 exam date.
* **📱 Fully Responsive:** Optimized for Mobile, Tablet, and Desktop views.

## 🎨 Aesthetic Palette

The UI is built with a custom cool-tone palette:
* **Background:** Indigo-Midnight Gradient 
* **Rank Highlight:** Neon Red
* **Download Action:** Electric Blue 
* **College/Success:** Sea Green 
* **Accents:** Bright Yellow 

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Variables, Animations, Grid/Flexbox), Vanilla JavaScript.
* **Visualization:** [Chart.js](https://www.chartjs.org/) (CDN).
* **Icons:** [FontAwesome 6](https://fontawesome.com/) (CDN).
* **PDF Generation:** [jsPDF](https://github.com/parallax/jsPDF) & [html2canvas](https://html2canvas.hertzen.com/).

## 📸 Screenshots



## ⚙️ How to Run

Since this project is built using standard web technologies and CDN links, no complex installation (npm/yarn) is required.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Suchetamon27/wbjee-css](https://github.com/Suchetamon27/wbjee-css )
    ```
2.  **Navigate to the folder:**
    ```bash
    cd wbjee-rank-predictor
    ```
3.  **Launch:**
    * Simply double-click the `index.html` file to open it in your browser.
    * *Optional:* Use the "Live Server" extension in VS Code for hot reloading.

## 🧠 The Logic

The rank prediction is based on a mathematical approximation curve derived from historical WBJEE data trends.

> Note: This is an estimation tool. Actual ranks depend on the difficulty of the paper and the number of candidates appearing in 2026.

🤝 Contributing
Contributions are always welcome!

Fork the Project.

Create your Feature Branch (git checkout -b feature/AmazingFeature).

Commit your Changes (git commit -m 'Add some AmazingFeature').

Push to the Branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📜 License
Distributed under the MIT License. See LICENSE for more information.

🌟 Acknowledgements
Cutoff data based on 2024-2025 OR-CR trends.

  © WBJEE Predictor @JEE2Med 2026





