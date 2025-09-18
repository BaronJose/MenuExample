# 🌮 Taco Truck Menu 🚚

A simple, mobile-friendly, and responsive digital menu for restaurants.  
This project is powered by **HTML, CSS, and JavaScript**, with menu items loaded dynamically from a **Google Sheets (CSV export)**.  

🔗 **Live Demo**: [View Menu](https://baronjose.github.io/MenuExample/)

---

## ✨ Features
- 📱 **Responsive Design**: Works great on both desktop and mobile.
- 🖼️ **Images**: Each item supports an image (with fullscreen zoom on tap).
- 🎯 **Categories**: Expandable categories for easy navigation.
- ⭐ **Specials Ribbon**: Highlight daily specials at the top.
- 📝 **Editable via Google Sheets**: Update your menu without touching code.

---

## 📖 How It Works
1. The menu reads from a **Google Sheet published as CSV**.  
2. Each row in the sheet represents one menu item.  
3. Specials appear in the **red ribbon** automatically if flagged.

---

## 📊 Example Google Sheet Format
| Category | Item        | Description              | Price | Image URL | Special |
|----------|------------|--------------------------|-------|-----------|---------|
| Tacos    | Carne Asada | Grilled steak taco 🌮     | 3.50  | https://... | Yes |
| Burritos | Veggie      | Beans, rice, salsa wrap 🌯 | 7.00  | https://... | No  |

👉 Columns should be exactly as above (case-insensitive).  

- **Category** → Section (e.g., Tacos, Burritos).  
- **Item** → Name of the menu item.  
- **Description** → Short description.  
- **Price** → Number only (no $ sign needed).  
- **Image URL** → Direct link to an image (or leave blank).  
- **Special** → "Yes" to display in specials ribbon, otherwise leave blank.  

---

## 🔧 How to Update the Menu
1. Open your Google Sheet.  
2. Add / edit rows as needed.  
3. Make sure it is **Published to the Web** (File → Share → Publish to Web → CSV link).  
4. Update the CSV link in `index.html` (inside `loadMenu()` function).  

No redeployment needed — just refresh the site after saving your sheet! 🎉  

---

## 🚀 Deployment
This project is ready to deploy on **GitHub Pages**:
1. Push your code to a GitHub repository.  
2. In your repo, go to **Settings → Pages**.  
3. Set source to **main branch → root**.  
4. Your site will be live at:  


---

## 📞 Branding & Contact
- Add your logo, address, and phone number in the `<header>` section of `index.html`.  
- Update styles inside the `<style>` tag as needed.  

---

## 🛠️ Future Ideas
- 🍽️ Multiple themes (dark / light).  
- 🔑 Admin panel for non-technical staff.  
- 🖨️ Print-friendly version.  

---

## 👨‍💻 Author
Created by Jose Baron.  
Need a custom version? Reach out at: [contact@baronxdev.com](mailto:contact@baronxdev.com).
