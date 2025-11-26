<div align="center">

# 💳 Billing System

### A Complete Invoice & Billing Management Solution for Businesses

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-FF6F00?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-Database-044a64?style=for-the-badge&logo=sqlite&logoColor=white)
![Billing](https://img.shields.io/badge/System-Billing-blue?style=for-the-badge)

**A desktop-based billing and invoice management application built with Python, offering product management, customer handling, bill generation, and print-ready receipts.**

[🐛 Report Bug](https://github.com/TanayV24/Billing-system/issues) | [💡 Request Feature](https://github.com/TanayV24/Billing-system/issues)

</div>

---

## ✨ Features

### 🧾 **Core Billing Features**
- ➕ **Add Products to Bill** – Items, quantity, GST, rates  
- 🧮 **Auto Calculations** – Subtotal, tax, discounts, grand total  
- 🧑‍🤝‍🧑 **Customer Records** – Store name, phone, and billing details  
- 🧾 **Invoice Generation** – Auto invoice number & date  
- 📄 **Printable Receipts** – Save & print customer bills  
- 💾 **Local Database Storage** (Optional) – Using SQLite  

### 📦 **Utility Features**
- 🔍 **Search Customer Bills** by name or invoice number  
- 🗃️ **Clear Bill / Reset Interface** instantly  
- 🏷️ **Automatic GST Calculation** per item  
- 🖨️ **Print Bill Option** (PDF/Printer)  
- 🖥️ **Simple & Clean Tkinter UI**  

---

## 🛠 Tech Stack

<table>
<tr>
<td width="50%" valign="top">

### Application Layer
- **Language:** Python  
- **GUI Framework:** Tkinter  
- **Data Handling:** Python Dictionaries / Lists  
- **Billing Logic:** Dynamic calculations  

</td>
<td width="50%" valign="top">

### Database (Optional)
- **Database:** SQLite  
- **Queries:** CRUD operations  
- **File Storage:** `.db` local file  
- **Backups:** Can export/load database  

</td>
</tr>
</table>

---

## 📋 Prerequisites

Make sure you have the following installed:

| Tool | Version | Link |
|------|---------|------|
| 🐍 Python | 3.8+ | https://python.org |
| 💻 Git | Latest | https://git-scm.com |
| 🗄 SQLite (optional) | Latest | https://sqlite.org |

Verify installation:

```

python --version
git --version

```

---

## ⚙️ Installation & Setup

### 🚀 Quick Start

1. **Clone the Repository**
```

git clone [https://github.com/TanayV24/Billing-system.git](https://github.com/TanayV24/Billing-system.git)
cd Billing-system

```

2. **Run the Application**
```

python billing.py

```

> The Tkinter UI will open immediately.

---

## 🎮 How to Use

1. Enter **customer details**  
2. Select/add **products** with quantity  
3. The system calculates:  
   - Subtotal  
   - GST  
   - Total amount  
4. Click **Generate Bill**  
5. View the bill in preview area  
6. Click **Print** to print or save as PDF  
7. Use **Search** to find previous bills  

---

## 📁 Project Structure

```

Billing-system/
│
├── billing.py               # Main application file (Tkinter GUI)
├── database/                # Optional SQLite DB folder
│   └── billing.db           # Local database file
│
├── assets/                  # Icons, logos (if used)
│
├── .gitignore
└── README.md

```

---

## 📄 Example Bill Format

```

---

```
         XYZ STORE
     INVOICE NO: 10234
```

---

## Item            Qty     Price

Shampoo         2       ₹240
Soap            4       ₹80
---------------------------

Subtotal:               ₹320
GST (18%):              ₹57.6
Total:                  ₹377.6
------------------------------

## Thank you for shopping with us!

```

---

## 🐛 Troubleshooting

<details>
<summary>Tkinter window not opening</summary>

Run:
```

python billing.py

```
Ensure Python is installed correctly.
</details>

<details>
<summary>Print not working</summary>

Install Python `pywin32` for Windows print support:
```

pip install pywin32

```
</details>

<details>
<summary>Database not updating</summary>

Make sure:
- SQLite file isn't locked  
- Correct permissions on folder  
</details>

--

