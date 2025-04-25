# DIY Cocktail Tab 🍹

This Google Colab app lets users discover and explore cocktails by choosing ingredients, comparing drink options, and getting personalized recommendations based on A/B testing. It's built with Python, interactive widgets (`ipywidgets`), and TheCocktailDB API.

## 💻 How to Use It

### Open in binder
Click below to launch the notebook in binder (no setup required):
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tw584/Alcohol_DIY_Generator_Project/main?labpath=drink%20DIY%20%26%20AB%20testing.ipynb)


## 🧪 App Features & Tabs

### Tab 1: One Ingredient DIY
- Select:
  - Glass type (e.g., cocktail glass, mug, highball)
  - Alcoholic or non-alcoholic
  - One main ingredient (e.g., gin, coffee, lime juice)
- Click the button to search
- Get:
  - A random drink that matches your criteria
  - A full image of the drink
  - Instructions and a list of ingredients

---

### Tab 2: Two Ingredients DIY
- Same as Tab 1 but lets you pick two ingredients
- Example: Mix **dark rum** + **Kahlua**
- Great for exploring new combos with what you have

---

### Tab 3: Drink from Popular List
- Click a button to get a random drink from the **popular cocktail list**
- It will display:
  - Drink image
  - Instructions
  - Ingredients and measurements

---

### Tab 4: A/B Testing
- You pick a glass, alcohol type, and an ingredient
- The app finds 2 drinks that match and shows you both
- You choose your preferred drink (A or B)
- Your choice is logged for preference learning

➡ After a few votes, click **"Get My Personal Recommendation"** to see what the system thinks you'll like!

---

## 📈 Bonus Features

- 📊 **Charts** to show:
  - Most chosen glass types
  - Alcohol preferences
  - Top ingredients based on user votes
- ✅ Save your preferences to a CSV file
- 📦 Built with:
  - Python
  - Ipywidgets
  - Requests
  - Matplotlib / Seaborn
  - Pandas
---


## 📂 Files
- `cocktail_tab.ipynb`: main interactive notebook
- 'requirements.txt': all the required package
- `README.md`: usage guide

---
