# 💰 MoneyYOU-Project

A simple and efficient **personal finance management application** built with **Python + PyQt6**, designed to help **international students** keep track of their income and expenses during their time abroad.

---

## ✨ Features

- ✅ Register income and expenses with custom categories  
- 💼 Categorize transactions by type (e.g. Food, Rent, Transport, etc.)  
- 🌍 Currency conversion with predefined fixed rates (e.g. BRL to USD or EUR)  
- 📊 View updated balance and basic financial summaries  
- 📁 Save and load your data locally using **JSON** or export as **CSV**  
- 📈 Generate simple reports to understand spending habits  
- 🖥️ Friendly **GUI interface** with PyQt6

---

## 📌 Project Goals

- Help exchange students organize their finances simply and offline  
- Serve as a learning project for:
  - GUI development using **PyQt6**
  - File manipulation (JSON/CSV)
  - Object-oriented programming
  - Practical finance application logic

---

## 🚀 Getting Started

### 📦 Prerequisites

- Python 3.8 or higher
- Install dependencies:

```bash
pip install PyQt6
```

### ▶️ Run the application

```bash
python main.py
```

---

## 🗂️ File Structure
moneyyou/
│
├── main.py                        # Main entry point of the program
├── config.py                      # Global settings (e.g., colors, file paths)
├── database/
│   ├── __init__.py
│   ├── data_manager.py            # Data handling (read, save, update)
│   └── data.json                  # JSON file with data (temporary or fixed)
│
├── ui/
│   ├── __init__.py
│   ├── login_screen.py           # Login screen
│   ├── dashboard.py              # Main screen with summary and charts
│   ├── transaction_form.py       # Screen/modal for adding transactions
│   ├── widgets/
│   │   ├── __init__.py
│   │   ├── transaction_card.py   # Reusable UI components
│   │   └── chart_widget.py       # Chart widget (modular separation)
│
├── logic/
│   ├── __init__.py
│   ├── auth.py                   # Login logic (even if simple)
│   ├── transactions.py           # Functions to add, edit, and filter transactions
│   └── reports.py                # Report and chart generation
│
├── assets/
│   ├── icons/                    # Icons
│   └── style.qss                 # Stylesheet (separated for easier visual maintenance)
│
└── README.md                     # Project description

```bash

```

---

## 🖼️ Screenshots

_You can add screenshots here showing the main interface, transaction form, and summary screen._

---

## 🛠️ Future Improvements

- [ ] Monthly budget limits and alerts  
- [ ] Visual charts with PyQtGraph or matplotlib  
- [ ] Cloud sync support  
- [ ] Multi-language support (EN / PT)

---

## 📄 License



---

## 🤝 Contributing

Pull requests are welcome! If you find a bug or have a suggestion, feel free to [open an issue](https://github.com/Rian1303/Finance_traker_for_international_students).


---

## 👤 Author

Developed by **Rian** — Student, designer & developer.  
> Focused on creating practical and educational solutions for real-world problems.

---

