# 🛒 Lanka Price Comparer (Web Scrapper)

A specialized Python tool designed to automate the process of comparing grocery prices between **Laughs Super** and **Glomark** online stores.

## ✨ Features
* **Automated Data Fetching:** Uses `requests` to fetch web page content.
* **HTML Parsing:** Implements `BeautifulSoup` to extract product names and prices.
* **Smart Comparison:** Compares prices of common items like Coconut, Coca-Cola, Bread, and Tissues.
* **Cost Saving Analysis:** Calculates and displays which supermarket offers the better deal for a specific item.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** BeautifulSoup4, Requests, JSON

## 🚀 How it works
1. The script imitates a browser session using a `User-agent`.
2. It fetches data from the provided supermarket URLs.
3. The logic parses the price data and converts it into floating-point numbers.
4. Finally, it outputs a side-by-side price comparison and suggests the cheapest option.

---
*Developed by I. W. Saketh Akitha* 🇱🇰
