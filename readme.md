# BKI - Smart Kitchen & Recipe Recommendation

## 📌 Project Overview
This project is developed by a team of first-year Artificial Intelligence students from UTS. Our goal is to immerse ourselves in a professional competitive landscape, seeking the practical experience and technical insights necessary to lead in the evolving AI field.

The application is an AI-powered smart kitchen assistant designed to help users manage their kitchen inventory, reduce food waste, and discover new cooking recipes.

## 📁 Project Structure
```
SMARTKITCHENRECOMMENDATION/
├── .github/
│   └── pull_request_template.md   # The template we just made
├── app/
│   ├── api/                      # Backend (Python/FastAPI)
│   │   ├── main.py
│   │   └── requirements.txt
│   └── web/                      # Frontend (Vite/TS)
│       ├── src/                  # Move your UI source code here
│       ├── package.json
│       ├── vite.config.ts
│       ├── tsconfig.json
│       ├── yarn.lock
│       └── .gitignore            # Frontend-specific (ignores node_modules)
├── data/
│   ├── raw/                      # Put food_recipes.csv here
│   ├── processed/                # Data after cleaning
│   └── EDA.md                    # Your notes on the data
├── notebooks/
│   └── S1_EDA.ipynb              # Exploration scripts
├── src/                          # CORE ML LOGIC (The "Engine")
│   ├── log/                      # Logging utilities
│   └── model/                    # Recommender architectures
├── .gitignore                    # Root-level (ignores .venv, .ds_store)
└── README.md                     # The "Front Page" of your project
```
## ⚙️ Setup
1. Clone repo
```Bash
git clone https://github.com/Hiihyhyhuhu/BackKhoaInnovation2026.git
cd BackKhoaInnovation2026
```
2. Create environment
```Bash
python -m venv venv
source venv/bin/activate
```
3. Install dependencies
```Bash
pip install -r requirements.txt
```

## 🚀 How to RunInput Data:
1. Scan barcodes or manually enter ingredients to the inventory.
2. Track Expiry: The app automatically tracks product shelf-life and sends adaptive reminders before items expire.
3. Get Recipes: Receive recipe suggestions to utilize ingredients before they go bad.
4. Engage: Discuss, share recipes, and earn reward points in the community forum.

## 📊 Features & Business Model
Core Feature | Description
:----|:----
Expiry Tracker | Keeps track of what is in the kitchen and sends timely notifications before items expire.
Recipe Recommendation | Suggests similar recipes based on user interest and predicts ratings (suggesting recipes with predicted rating > 4.5 stars).
Affiliate Marketing | Provides direct links to supermarket shopping carts (Co.opmart, Bach Hoa Xanh, ShopperFood) for required ingredients, earning a commission percentage on successful orders.
Ads & Sponsorship | Displays sponsored banner ads and features exclusive recipes highlighting signature products from spice companies (Chinsu, Knorr, etc.).
B2B Data Analytics | Compiles anonymous data into Trend Reports (food trends, excess inventory, purchasing habits) to sell to food corporations for production forecasting.

## 👤 Author Group

Name | Mail | Github
:--- | :--- | :---
Chanh Hy Tran| tranchanhhy.dev@gmail.com | [Hiihyhyhuhu](github.com/Hiihyhyhuhu)|
Vo Di Luan Dang| diluan801@gmail.com | [Dang Vo Di Luan](https://github.com/dluandv-toro) |