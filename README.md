
# 🎭 Event Attendance Tracker

A lightweight Progressive Web App (PWA) for tracking your visits to theater, opera, concerts, and more.

## 🚀 Features

- Add events with title, date, type, location, notes, and a 5-star rating
- Filter events by title, type, or location
- Export your event history to CSV
- View simple event statistics
- Installable on iOS as a full-screen app

---

## 📦 Project Setup

### 1. Install dependencies

```bash
npm install
```

### 2. Start development server

```bash
npm run dev
```

### 3. Build for production

```bash
npm run build
```

---

## 🌐 Deployment Options

### 🔹 Vercel (Recommended)

```bash
npm install -g vercel
vercel
```

### 🔹 Netlify

1. Push to GitHub
2. Import to Netlify
3. Set:
   - **Build Command**: `npm run build`
   - **Publish Directory**: `dist`

### 🔹 GitHub Pages

```bash
npm install --save-dev gh-pages
```

Add to `package.json`:

```json
"homepage": "https://<your-username>.github.io/<repo-name>",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
```

Deploy:

```bash
npm run deploy
```

---

## 📱 iOS Web App

- Full iOS PWA support (add to home screen via Safari)
- Includes touch icon and metadata for app-like behavior

---

## 🖼️ Icons

Place your app icon at `public/icon.png` (192x192 recommended).

---

## 📄 License

MIT
