# 🌐 Angular Google Translate Language Switcher

A **custom Angular component** to integrate **Google Translate** with:

- Full list of all available Google Translate languages.
- Clean, small, and stylish **dropdown UI**.
- **FontAwesome** Language icon support (`fa fa-language`).
- Default language is **English**, can switch to any other and back to English easily.
- No Google top toolbar or frames shown — looks **native**.
- Fully **responsive** and **mobile friendly**.

---

## ✨ Features

- ✅ Google Translate integration without showing default ugly bar.
- ✅ Dropdown with all languages supported by Google Translate.
- ✅ Default selected language: **English**.
- ✅ Language icon (`fa-language`) inside select box.
- ✅ Smooth transition when switching languages.
- ✅ Automatically reloads page after language change.
- ✅ Stylish, compact, and user-friendly design.

---

## 🔥 How it looks

```text
[🌐] Select Language ▼
- English
- Hindi
- Spanish
- French
- ... (all Google languages)
```

---

## ⚙️ Installation

1. Copy the `GoogleTranslateComponent` into your Angular project.
2. Add **FontAwesome** to your project (for the Language icon):

```bash
npm install @fortawesome/fontawesome-free
```

Then import the CSS in `angular.json`:

```json
"styles": [
  "node_modules/@fortawesome/fontawesome-free/css/all.min.css",
  "src/styles.scss"
]
```

3. Use the component in your template:

```html
<ds-google-translate></ds-google-translate>
```

---

## 🛠️ Technologies Used

- Angular
- Google Translate API (free widget)
- FontAwesome

---

## 🖼️ Screenshots

*Add a screenshot here showing the dropdown with the language icon.*

---

## 📜 License

This project is **open-source** and free to use.

---

## 💬 Author

Developed by Navneet Tomar

---

## 📌 Example GitHub Commit Message

> ✨ Added custom Google Translate language switcher with FontAwesome icon, full language support, and clean UI.

---

