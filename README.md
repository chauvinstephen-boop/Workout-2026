# Ruck & Strength Tracker (8-Week Program)

A **Progressive Web App (PWA)** to track an 8-week ruck and strength training program. Includes:

✅ Full workout schedule  
✅ Dark Mode toggle  
✅ Weekly summary dashboard  
✅ Progress tracking  
✅ Notes for each exercise  
✅ Export notes as a `.txt` file  
✅ Works offline (via Service Worker)  
✅ Installable on mobile (Add to Home Screen)  

---

## 🚀 Features
- **Dark Mode**: Toggle between light and dark themes.
- **Navigation**: Jump to today, next, or previous day.
- **Start Date Picker**: Automatically calculates current week/day.
- **Weekly Summary Dashboard**: Shows completion % for all 8 weeks.
- **Export Notes**: Download all notes as a text file.
- **Offline Support**: PWA with service worker.
- **Mobile App**: Add to Home Screen for native-like experience.

---

## 📂 Files
- `index.html` – Main app
- `manifest.json` – PWA manifest
- `service-worker.js` – Offline caching
- `icon.png` – App icon

---

## ✅ How to Test Locally
1. **Unzip the files** into a folder.
2. Start a local server:
   ```bash
   python -m http.server 8000
   ```
3. Open:
   ```
   http://localhost:8000
   ```
4. Test:
   - Dark Mode toggle
   - Navigation buttons
   - Weekly summary updates
   - Export notes downloads file

---

## 🌐 Deploy on GitHub Pages
1. Create a new GitHub repository.
2. Upload all files (`index.html`, `manifest.json`, `service-worker.js`, `icon.png`).
3. Go to **Settings → Pages → Source → main branch → root folder**.
4. Your app will be live at:
   ```
   https://yourusername.github.io/ruck-strength-tracker
   ```
5. Open the URL on your phone and tap **Add to Home Screen**.

---

## 🛠 Troubleshooting
- **No workouts showing?**
  - Ensure `index.html` contains the full `workoutData` array.
  - Clear browser cache or service worker data.
- **Buttons not working?**
  - Check console for errors.
  - Confirm all files are in the root folder.

---

## 📱 Install as App
- Open the GitHub Pages URL on your phone.
- Tap **Add to Home Screen** (Chrome or Safari).
- Enjoy your app offline!
