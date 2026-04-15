🛒 BasketFlow

BasketFlow is a lightweight mobile-first web app designed to turn messy shopping lists into a structured, efficient grocery shopping workflow — optimised for Tesco delivery users.

---

🚀 Features

✨ Hybrid AI Workflow (Free)

- No API required
- Uses ChatGPT as the AI engine
- One-tap prompt generation
- Paste structured results back into the app

---

🧠 Smart Structuring

- Converts messy lists into:
  - Clean item names
  - Deduplicated entries
  - Categorised sections:
    - Protein
    - Fruit & Veg
    - Dairy
    - Carbs
    - Pantry
    - Household
    - Snacks

---

📱 Tesco-Optimised Shopping

- Tap any item → opens Tesco search
- Works seamlessly with mobile browser → Tesco app
- Designed for fast add-to-basket workflow

---

✅ Progress Tracking

- Track items added to basket
- Visual completion indicator

---

💡 Habit Awareness (v4)

- Highlights commonly purchased items missing from your list
- Helps prevent forgotten essentials

---

🔁 How to Use

Step 1 — Paste List

Paste your shopping list into the app.

---

Step 2 — Copy AI Prompt

Tap “Copy AI Prompt” and paste into ChatGPT.

---

Step 3 — Paste Result

Copy the JSON response and paste it back into the app.

---

Step 4 — Shop

- Tap “Search” on each item
- Add in Tesco
- Mark as complete ✔

---

🧠 Habit System

The app includes a simple “usual items” check.

Example:

- Milk
- Bananas
- Bread
- Cheese

If missing, you’ll get a reminder:

«“You usually buy: milk, bananas”»

---

🔧 Customising Habits

Edit this in "index.html":

const usuals = [
  "milk",
  "bananas",
  "cheese",
  "bread"
];

---

🛠 Tech Stack

- Vanilla HTML / CSS / JavaScript
- No backend required
- Hosted via GitHub Pages

---

📈 Future Improvements

- Meal → ingredient auto-expansion
- Save previous shops (localStorage)
- Personalised Tesco product matching
- Smart substitutions
- UI polish (animations, transitions)

---

🎯 Philosophy

BasketFlow is designed to:

- Reduce mental load
- Prevent missed items
- Keep the human in control
- Avoid fragile automation

---

🧪 Status

Prototype (v4) — actively evolving through real-world use.

---

🤝 Contributing

This is a personal project, but ideas and improvements are welcome.

---

📌 Notes

- No data is stored externally
- Works entirely client-side
- Safe for personal use

---

Enjoy faster, smarter shopping 🛒
