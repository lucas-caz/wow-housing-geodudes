# 🏠 WoW Housing — Testemunhas de Geodude

A simple and interactive **World of Warcraft housing map** for guilds, now upgraded to support **real-time data editing and persistence via Firebase**.

---

## 🌍 Overview

This project displays an interactive map for the WoW housing system — specifically the Alliance map — showing **plot numbers** for all available houses.

Each plot can now be **clicked and edited directly from the browser**, allowing guild members to easily mark which plots are taken and by whom.

No more editing code manually — everything is handled visually and saved automatically!

---

## ✨ New Features

✅ **Browser-based editing**  
You can click any plot on the map to add, update, or clear the occupant’s name directly from the page.  
No need to open or modify the `index.html` file anymore.

✅ **Persistent data via Firebase**  
All updates are saved to a shared **Firebase Realtime Database**, so the map data remains consistent and synchronized for everyone viewing it.  
Changes are reflected in real-time across all users.

✅ **Easy collaboration**  
Multiple guild members can open the same page and see updates instantly as others make changes.

---

## 🧩 How to Use

1. Clone or fork this repository.

2. Set up your own Firebase instance.
   Before running the site, you must configure your own Firebase project to store data.
   Follow the steps in the Firebase Configuration section below and replace the Firebase config block inside index.html with your own credentials.

3. Open index.html in your browser (or host it on GitHub Pages for public access).

4. Click on any plot number to edit the occupant name.
   The data will automatically save and sync via Firebase in real time.
