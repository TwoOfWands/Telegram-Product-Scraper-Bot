# Telegram Product Scraper Bot

<p align="center">
  A Telegram bot for searching Newegg products and exporting product information to Excel.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python" />
  <img src="https://img.shields.io/badge/Telegram-Bot-blue?logo=telegram" />
  <img src="https://img.shields.io/badge/BeautifulSoup-Web%20Scraping-green" />
  <img src="https://img.shields.io/badge/SQLite-Database-lightgrey?logo=sqlite" />
  <img src="https://img.shields.io/badge/Excel-Export-green?logo=microsoftexcel" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## 📖 About

**Telegram Product Scraper Bot** is a Python-based Telegram bot that allows users to search for products on **Newegg**, collect detailed product information, and receive the results as an Excel file directly through Telegram.

The project combines **Telegram Bot development, asynchronous programming, web scraping, SQLite, and Excel data processing** in a single practical application.

## ✨ Features

* 🤖 Telegram bot interface
* 🔎 Search Newegg products by product name
* 🕷️ Web scraping with BeautifulSoup
* 📦 Extract product information including:

  * Brand
  * Color
  * CPU
  * Memory
  * SSD
  * GPU
  * Price
* 🗄️ SQLite for data storage
* 📊 Generate Excel files from scraped data
* 📤 Send generated Excel files directly through Telegram
* 🎛️ Inline buttons and custom keyboards
* ⚡ AsyncIO-based processing

## 🛠️ Tech Stack

| Technology       | Purpose                     |
| ---------------- | --------------------------- |
| Python           | Core programming language   |
| AsyncIO          | Asynchronous operations     |
| Telegram Bot API | Bot interface               |
| BeautifulSoup    | HTML parsing & web scraping |
| SQLite           | Data storage                |
| Excel            | Data export                 |

## 🔄 How It Works

```text
User
  ↓
Telegram Bot
  ↓
Enter Product Name
  ↓
Search Newegg
  ↓
Scrape Product Information
  ↓
Store / Process Data
  ↓
Generate Excel File
  ↓
Send Excel File to User
```

## 📁 Project Structure

```text
Telegram-Product-Scraper-Bot/
├── src/                  # Main source code
├── video/                # Project demonstration
├── config_example.py     # Configuration template
├── requirements.txt      # Python dependencies
├── LICENSE
└── README.md
```

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/TwoOfWands/Telegram-Product-Scraper-Bot.git
cd Telegram-Product-Scraper-Bot
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

## ⚙️ Configuration

Create a `config.py` file based on `config_example.py`.

```python
API_TOKEN = "YOUR_TELEGRAM_BOT_TOKEN"
```

Replace the placeholder with your Telegram Bot API token.

> Never commit your real bot token or other sensitive credentials to GitHub.

## ▶️ Run

After configuring the bot, run the main application from the project source directory.

```bash
python src/main.py
```

Then open your Telegram bot and send a product name to start a search.

## 📊 Example Workflow

```text
"Gaming Laptop"
       ↓
Newegg Search
       ↓
Product Information
       ↓
Excel File
       ↓
Telegram
```

## 📄 License

This project is licensed under the **MIT License**.

## 👨‍💻 Author

**TwoOfWands**

Python Developer | Web Scraping | Telegram Bots

---

<p align="center">
  Built with Python 🐍
</p>
