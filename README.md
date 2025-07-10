#  Record Management System (Python)

This is a **file-based Record Management System** built using Python and Object-Oriented Programming (OOP). The system is designed to manage simple records (like library books) and includes full CRUD functionality via a command-line menu.

>  Developed as part of an internship task and implemented in **Google Colab** for simplicity and accessibility.

---

##  Features

- ✅ Add new book records
- 📋 View all records
- 🔍 Search for a book by ID
- ✏️ Update a book's information
- ❌ Delete a record by ID
- 🔃 Sort records (by title or year)
- 📤 Export all records to a CSV file
- 💾 Data persistence via `data.json`
- ✅ Simple CLI interface for interaction

---

## Technologies Used

- Python 3
- File I/O (`json`, `csv`)
- Google Colab (for execution)

---

## File Overview

- `TASK1.ipynb` – Main Colab notebook with all functionality
- `data.json` – Local storage for book records (created automatically)
- `books.csv` – Exported CSV file (created on demand)

---

## How to Run

### Option 1: In Google Colab (Recommended)

1. Open the notebook: [🔗 Open in Colab]((https://colab.research.google.com/drive/1F4CAaOMSrkZyjscqI-LCkgL3gnxH202N?usp=sharing))
2. Run the cells
3. Use the command-line prompts to manage records

### Option 2: Locally on Your Machine

1. Download `TASK1.ipynb` or convert it to `.py`
2. Run with:
   ```bash
   python TASK1.py
