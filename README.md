# FastAPI Tutorial Project

A simple learning project built with [FastAPI](https://fastapi.tiangolo.com/) as I explore and understand how to create modern web APIs using Python. This app serves as a starting point for building fast, efficient, and clean backend applications with FastAPI.

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.8+
- [pip](https://pip.pypa.io/en/stable/installation/) installed

---

### 📦 Installation

1. **Clone the repository**:
```bash
git clone https://github.com/lawrence615/fastapi-tut-1.git
cd fastapi-tut-1
```

2. Create and activate a virtual environment:
```bash
# Create a virtual environment
python3 -m venv venv

# Activate it (choose the correct command based on your OS)
source venv/bin/activate        # Linux/macOS
venv\Scripts\activate           # Windows
```

3. Install the dependencies:
```bash
pip3 install -r requirements.txt
```

## ▶️ Running the App
Start the FastAPI server with:
```bash
uvicorn main:app --reload
```

Then open your browser and visit:
```bash
http://127.0.0.1:8000
```

To explore the interactive API docs:
```bash
http://127.0.0.1:8000/docs
```

or ReDoc alternative docs:
```bash
http://127.0.0.1:8000/redoc
```

## 📝 Notes
- The `--reload` flag makes the server restart automatically on code changes (great for development).

- To regenerate `requirements.txt` after adding packages:
```bash
pip3 freeze > requirements.txt
```

## 📌 License
MIT – Feel free to use, fork, and learn.
