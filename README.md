# 🔗 Simple URL Shortener (Flask + Python)

A minimal URL Shortener built with **Python**, **Flask**, and **pyshorteners**.  
This project demonstrates how to create a basic web application that takes a long URL and returns a shortened version using the TinyURL service.

The frontend is styled using **TailwindCSS**, with templates organized following Flask’s recommended structure.

---

## 📁 Project Structure

```bash

url_shortner/
│── main.py
│── templates/
│ ├── base.html
│ └── form.html
│── static/
│ └── css/
│ └── styles.css
│── myenv/ (virtual environment)

```


---

## 🛠️ Tech Stack

- **Python 3.9+**
- **Flask**
- **pyshorteners - from python**
- **TailwindCSS (via CDN)**

---


## How It Works
User inputs a valid HTTPS URL

Flask receives it via a POST request

pyshorteners generates a shortened version (TinyURL)

The shortened link appears on the page with a Copy button

No database is required — the service simply transforms URLs

---
## How to use?

Just click in here: https://url-shortner-hi7i.onrender.com/

---

## 📚 Reference
This project was inspired by the tutorial:
https://kinsta.com/pt/blog/url-simples-com-python/


