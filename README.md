☁️ Cinnamoroll Health Station ☁️


A visually appealing, responsive self-service "Health Self-Check Kiosk" web application designed with a pastel Cinnamoroll theme. This application allows students and campus employees to easily and privately calculate their Body Mass Index (BMI), receive personalized wellness recommendations, and automatically sync data directly into a Google Sheet backend database.


✨ Features
- **Cinnamoroll Theme:** A soft pastel aesthetic utilizing relative design styling that natively scales beautifully across both high-resolution monitors and mobile device viewports.
- **Fluid Zoom Responsiveness:** Fully adaptive to page zoom percentages, keeping text layout elements and tap targets in proportion.
- **Robust Client-Side Data Validation:** Utilizes JavaScript loops to cross-check form entries ensuring measurements are positive numbers and realistic ranges before evaluation.
- **Instant Health Diagnostics:** Leverages logical `switch-case` evaluation models to categorize your BMI (Underweight, Normal, Overweight, Obese) along with corresponding advice and dynamically matching theme colors.
- **Google Sheets Backend Integration:** Seamlessly routes submission records to a remote spreadsheet using asynchronous `fetch` requests powered by Google Apps Script.



🛠️ Technology Stack
- **Frontend:** HTML5, CSS3 (Flexbox, CSS Custom Properties, Media Queries)
- **Programming Logic:** Vanilla JavaScript (ES6+ Features)
- **Typography:** Google Fonts (Nunito, Fredoka One)
- **Database/Backend:** Google Sheets API & Google Apps Script (Web App Deployment)



📂 File Architecture
├── index.html          # Main application structure, styling rules, and JS logic
└── README.md           # Documentation for the project workspace
