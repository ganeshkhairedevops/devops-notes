# Python for DevOps Notes with Examples

## Virtual Environment
Create virtual environment:

python -m venv venv
source venv/bin/activate

---

## Install Packages
pip install -r requirements.txt

---

## File Handling Example
with open("file.txt", "r") as f:
    data = f.read()
    print(data)

---

## API Request Example
import requests

response = requests.get("https://api.github.com")
print(response.status_code)

---

## Simple Monitoring Example
import psutil

print("CPU:", psutil.cpu_percent())
