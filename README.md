# Belly Button Biodiversity Dashboard

This project is an interactive dashboard that visualizes **Belly Button Biodiversity** data. The dashboard is deployed using **GitHub Pages** and built with **JavaScript, D3.js, and Plotly.js**.

## 📌 Live Dashboard
🔗 **GitHub Pages Deployment:**  
[https://isalklm.github.io/belly-button-challenge/](https://isalklm.github.io/belly-button-challenge/)

## 📂 Repository
🔗 **GitHub Repository:**  
[https://github.com/isalklm/belly-button-challenge](https://github.com/isalklm/belly-button-challenge)

---

## 🚀 Project Overview

This dashboard allows users to:
- Select an individual sample ID from a dropdown menu.
- View a **horizontal bar chart** of the top 10 OTUs (Operational Taxonomic Units) found in that sample.
- Explore a **bubble chart** displaying bacterial cultures per sample.
- See demographic information for the selected individual.

---

## 🛠️ Technologies Used
- **JavaScript** (ES6+)
- **D3.js** (for fetching and handling data)
- **Plotly.js** (for creating interactive charts)
- **HTML & CSS** (for styling and layout)
- **GitHub Pages** (for deployment)

---

## 📊 Dataset
The dataset is provided in `samples.json` and includes:
- Sample IDs (`id`)
- OTU labels (`otu_labels`)
- OTU IDs (`otu_ids`)
- Sample values (`sample_values`)
- Demographic metadata

---

## 📄 Instructions to Run Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/isalklm/belly-button-challenge.git
2. Navigate to the project directory
   cd belly-button-challenge
3. Open index.html in a browser or use Live Server in VS Code.
---
📌 Deployment
The project is deployed using GitHub Pages.
Any updates pushed to the main branch will be automatically reflected in the live dashboard.
---
📜 Attribution and Code Sources
This project was developed as part of a bootcamp program. The code for database setup, updates, and analysis was created using Python libraries and MongoDB documentation.
