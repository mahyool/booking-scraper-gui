# 🏨 Booking.com Web Scraper with GUI + Email Automation

This project scrapes Airbnb listings from booking.com using user inputs via a Tkinter GUI, filters the data based on stay length and budget, and emails a filtered list to the user.

## 💡 Features

- Scrape booking data
- GUI to enter city, date, guest, stay type
- Export to CSV
- Filter by budget
- Email results

## 📂 Files

- `airbnb_scrapy.ipynb` → scraping logic
- `traveler.py` → filtering + emailing class
- `Airbnb_data.csv` → raw data
- `filtered_data.csv` → cleaned data
- `Final Project.pdf` → summary overview

## 📧 Email Feature

Auto-sends results to the user via Gmail (SMTP) with attachment.

## 🔧 Requirements

- Python 3.8+
- pandas
- smtplib
- Tkinter

## 🚀 How to Run

1. Run `airbnb_scrapy.ipynb` to collect listings
2. Use `traveler.py` to filter + send email

## 📬 Contact

Mahboubeh Bagheri  
[mahboubeh.bagheri99@gmail.com](mailto:mahboubeh.bagheri99@gmail.com)
