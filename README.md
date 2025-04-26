# 🕸️ Web Scraping Project – IBM Data Analyst Capstone

This project is part of **Module 1** of the **IBM Data Analyst Capstone**, which is also part of the main course [IBM Data Analyst Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-analyst) that demonstrates real-world web scraping techniques using Python.
It focuses on downloading webpages, parsing HTML content, extracting links, images, and tabular data.

---

## 🎯 Project Objectives

- Perform HTTP requests to access web pages.
- Parse HTML content using **BeautifulSoup**.
- Extract **hyperlinks**, **images**, and **tables**.
- Process and preview extracted data for analysis.

---

## 🧪 Tools & Technologies

- Python (Jupyter Notebook)
- `requests` (HTTP requests)
- `BeautifulSoup` (HTML parsing)
- `pandas` (table extraction)
- Git + GitHub for project publication

---

## 📈 Key Functional Highlights

- ✅ Fetch webpages using `requests`
- ✅ Parse HTML content with `BeautifulSoup`
- ✅ Extract:
  - Links (`<a>` tags)
  - Images (`<img>` tags)
  - Tables (`<table>` elements)
- ✅ Save and preview extracted data

All functions are accompanied by printed outputs and markdown explanations for clarity.

---

## 📜 Dataset Source

This project uses live web scraping of open-access web pages from IBM's official website:  
🌐 [www.ibm.com](https://www.ibm.com)

The scraping was done **ethically**, targeting educational pages without violating `robots.txt` rules.

📌 **Important:** Always ensure your web scraping follows website terms and conditions.

---

## 🧠 Key Learnings

- Web scraping is a powerful method to gather data that isn't directly available via APIs.
- Proper parsing and data cleaning are crucial after scraping.
- Always check site permissions before scraping in a real-world scenario.

---

## 🖥️ Browser's Viewing

Explore the full project with visuals and insights via the hosted dashboard:

[![View in Browser](https://img.shields.io/badge/View-Dashboard-blue?style=for-the-badge&logo=plotly)](https://kelechiede.github.io/Project_5_Web-Scraping/dashboard/Web-Scraping-Review-Lab.html)
- 📄 [Download as PDF](dashboard/Web-Scraping-Review-Lab.pdf)

> 💡 This notebook includes bar charts, job demand visualizations, and clean API data analysis — best viewed on a desktop browser.

---

- 📁 **Original Jupyter Notebook**: `notebooks/Web-Scraping-Review-Lab.ipynb`
- 📄 **Static HTML Version**: [`Web-Scraping-Review-Lab.html`](https://kelechiede.github.io/Project_5_Web-Scraping/dashboard/Web-Scraping-Review-Lab.html)


---

## 📜 Certification

This project was completed as part of the **IBM Data Analyst Capstone Certificate** on Coursera.

[![IBM Certificate Thumbnail](certification/ibm-data-visualization-thumbnail.png)](https://www.coursera.org/account/accomplishments/verify/ARTLBRAPJ68Q)

> [Verify Capstone Certificate on Credly](https://www.credly.com/badges/259d69a8-bd52-47fb-b02e-19947b158dc6/public_url)

---

## 🧑‍💼 Author

**Kelechukwu Innocent Ede and Ramesh Sannareddy**  
IBM Certified Data Analyst  
🔗 GitHub: [@Kelechiede](https://github.com/Kelechiede)  
🔗 LinkedIn: [Kelechukwu Innocent Ede](https://www.linkedin.com/in/kelechukwu-innocent-ede-b448aa134/)  
📧 Email: kelechukwuede@gmail.com

---

## 📂 Project Structure
```plaintext
ibm_capstone_data_analyst_2025/
└── module_1_real_world_projects/
    └── web-scraping-lab-project/
        ├── data/
        │   ├── scraped_colors.csv
        │   └── scraped_colors.xlsx
        ├── notebooks/
        │   └── web-scraping-review-lab.ipynb
        ├── browser's viewing/
        │   ├── Web-Scraping-Review-Lab.html
        │   └── Web-Scraping-Review-Lab.pdf
        ├── certificate/
        │   ├── data-analyst-capstone-badge-project.png
        │   ├── ibm_capstone_certificate_thumbnail.png
        │   └── ibm_capstone_coursera_certificate_thumbnail.png
        ├── visuals/
        │   ├── web_scraping_summary_chart.png
        │   └── scraped_color_table_snapshot.png
        └── README.md
