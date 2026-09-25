# 🩺 EPI Vaccination Database System.

A database-driven application designed to manage and monitor vaccination records under the **Expanded Programme on Immunization (EPI)**. This system ensures secure, organized, and real-time tracking of immunization data — helping healthcare authorities streamline vaccination efforts, especially in rural or underserved regions.

---

## 🎯 Objective

To build a centralized digital system for recording and retrieving vaccination data of infants and children under the EPI schedule, enabling **easy tracking**, **planning**, and **monitoring** of immunization coverage.

---

## 🧩 Key Features

- ✅ Add/Edit/Delete child vaccination records  
- 👶 Stores personal details: Name, Date of Birth, Parent Info, Address  
- 💉 Tracks vaccines: BCG, DPT, Polio, HepB, Measles, etc.  
- 📅 Auto-calculates due dates for upcoming vaccinations  
- 🔍 Search functionality: by Name, ID, or Location  
- 🔐 Role-based access control: Admin vs. Data Entry Operator  
- 💾 SQL Database (MySQL via XAMPP)

---

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript (optional)  
- **Backend:** PHP or Java *(depends on version)*  
- **Database:** MySQL (via XAMPP or WAMP)  
- **Optional GIS:** Leaflet.js / Google Maps API (for mapping vaccination areas)

---

## 🔐 Future Enhancements (Research-Oriented)

This system is being extended into a **Blockchain-Integrated SQL Database** to store tamper-proof vaccination records, enabling:

- Enhanced data integrity  
- Immutable medical records  
- Greater trust for use by national and international health organizations

> This enhancement aligns with Mahdi Hasan’s research focus:  
> *"Blockchain-Integrated SQL Database for Secure EPI Records."*

---

## 🚀 How to Run Locally

1. **Install [XAMPP](https://www.apachefriends.org/index.html)** (or WAMP)
2. **Start Apache and MySQL**
3. **Import the SQL database:**
   - Open `phpMyAdmin`
   - Create a new database (e.g., `epi_vaccination`)
   - Import the provided `.sql` file
4. **Place project files in the `htdocs/` directory**
5. **Visit** `http://localhost/epi_vaccination/` in your browser

---

## 🖼️ UI Preview

[UI Preview][https://github.com/user-attachments/assets/b670c232-ce0c-4b28-8daa-a3b8c6d6d4a7]

---

> 📌 *Feel free to fork, contribute, or suggest enhancements — especially if you’re interested in health-tech, public health systems, or database security.*

