# 📺 Netflix Relational Database

Welcome to my Netflix Dataset project!  

In this repository, I walk through how I applied formal database normalization techniques to create a real-world Netflix relational database, including detailed steps, an entity-relationship (ER) diagram, and the final cleaned dataset files.  

---

## 📦 Project Contents

This repository includes:
- **Raw Dataset** → Original Netflix dataset file.
- **Normalized Files** → Datasets transformed into:
  - First Normal Form (1NF)
  - Second Normal Form (2NF)
  - Third Normal Form (3NF)
- **ER Diagram** → Visual map of the final entities, keys, and relationships.
- **Final Normalized Dataset** → Fully normalized dataset ready for database import or analysis.

---

## 🏗️ What I Did

### ✅ Step 1: Analyzed Raw Dataset
- Reviewed the original dataset structure.
- Identified multivalued attributes (e.g., multiple genres, casts in a single row).

### ✅ Step 2: Applied First Normal Form (1NF)
- Broke down all fields into atomic values.
- Removed repeating groups.
- Used MS Excel's text-to-columns feature.

### ✅ Step 3: Applied Second Normal Form (2NF)
- Eliminated partial dependencies.
- Created separate tables for data groups like genres, actors, and directors.
- Used MS Excel and Power Query's unpivot feature.

### ✅ Step 4: Applied Third Normal Form (3NF)
- Removed transitive dependencies.
- Ensured non-key attributes depend only on primary keys.

---

## 🖼 ER Diagram

The repository includes an **ER diagram** that illustrates:
- Entities (Titles, Directors, Categories, Casts, etc.)
- Primary keys and foreign keys
- Relationships and cardinalities between entities

This provides a clear visual overview of how the normalized data is structured.

---

## 🔍 Why This Matters

Normalization:
- Improves **data integrity** and reduces redundancy.
- Prepares data for **relational database systems**.
- Enables more efficient and accurate **queries**.

This project demonstrates key data modeling skills, making it a great example of applying theoretical concepts (1NF, 2NF, 3NF) to real-world data.

---

## 💾 Files Included

| File/Folder              | Description                               |
|--------------------------|-----------------------------------------|
| `raw_dataset.xlsx`       | Original Netflix dataset (pre-normalization) |
| `1NF_dataset.xlsx`       | Dataset in First Normal Form            |
| `2NF_dataset.xlsx`       | Dataset in Second Normal Form           |
| `3NF_dataset.xlsx`       | Dataset in Third Normal Form            |
| `final_dataset.xlsx`     | Final normalized dataset                |
| `ER_diagram.png` / `.pdf`| Entity-Relationship diagram             |
| `README.md`              | This project overview                  |

---

## 🚀 How to Use

1. Download the normalized dataset files.
2. Import into your favorite RDBMS (e.g., MySQL, PostgreSQL, SQLite).
3. Use the ER diagram to understand table relationships.
4. Run meaningful queries to explore Netflix data (e.g., top directors, genre breakdowns, actor collaborations).

---

## 📬 Contact

If you have any questions or suggestions, feel free to open an issue or contact me!

