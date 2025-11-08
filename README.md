A Python-based airline booking simulator that allows users to view, search, and book flights with automatically generated booking IDs and PDF fare receipts.
It uses JSON for data storage and provides an Admin Dashboard powered by Pandas and NumPy for analytics.

 Features

View and search available flights

Book tickets and generate PDF receipts automatically

Store bookings securely in ~/Documents/SkyFly_Data

Cancel existing bookings

Admin Dashboard showing revenue, average fare, and popular routes

 Concepts Used

Lists and dictionaries

File handling (JSON read/write)

PDF generation with ReportLab

Data analytics using Pandas and NumPy

Modular function-based programming

 Installation
# Clone this repository
git clone https://github.com/<your-username>/skyfly-airline-booking.git
cd skyfly-airline-booking

# (Optional) Create a virtual environment
python3 -m venv .venv
source .venv/bin/activate    # Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

 Run the Program
python skyfly.py

 Admin Dashboard

Access analytics with:

Admin Password: admin123


Displays:

Total bookings

Total revenue

Average, highest, and lowest fares

Most popular flight route

Revenue by city

 Data Storage

Bookings: ~/Documents/SkyFly_Data/bookings.txt

Receipts: ~/Documents/Flight_Receipts/ (auto-generated PDFs)

 Requirements

Python 3.9+

Libraries:

reportlab

pandas

numpy
