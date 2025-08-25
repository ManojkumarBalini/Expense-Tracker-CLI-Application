# 💰 Expense Tracker CLI Application

A command-line tool built with Python to help you manage and track your daily expenses. This application allows you to:

* Add expense entries with category, amount, and optional description.
* Generate monthly reports with summaries and bar charts.
* Email reports using SMTP setup.

---

## 🚀 Features

* **Expense Management**: Easily add and categorize your expenses.
* **Monthly Summaries**: Generate summaries of your expenses for each month.
* **Visual Reports**: View bar charts representing your monthly expenses.
* **Email Reports**: Send your expense reports via email using SMTP.

---

## 🛠️ Tech Stack

* **Backend**: Python
* **Libraries**:

  * `matplotlib` for generating bar charts.
  * `smtplib` for sending emails.
  * `sqlite3` for database management.
  * `argparse` for command-line interface.

---

## 📂 Project Structure

```
Expense-Tracker-CLI-Application/
├── expense_tracker.py  # Main application script
├── database.db         # SQLite database file
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ManojkumarBalini/Expense-Tracker-CLI-Application.git
   cd Expense-Tracker-CLI-Application
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**

   ```bash
   python expense_tracker.py
   ```

---

## 📧 Email Configuration

To enable email reporting, configure your SMTP settings in the `expense_tracker.py` file:

```python
smtp_server = 'smtp.example.com'
smtp_port = 587
smtp_user = 'your_email@example.com'
smtp_password = 'your_password'
```

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

* **Manoj Kumar**

  * GitHub: [@ManojkumarBalini](https://github.com/ManojkumarBalini)
  * Portfolio: [manojkumar.dev](https://manojkumar.dev)

