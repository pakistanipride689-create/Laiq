# 🛞 STPL - Complaint Management System (PWA)

<div align="center">

![STPL Logo](https://img.shields.io/badge/STPL-Service%20Tyre%20Pvt%20Ltd-DC2626?style=for-the-badge)
![PWA](https://img.shields.io/badge/PWA-Ready-4CAF50?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**Service Tyre Private Limited - Professional Complaint Management System**

[Live Demo](#) | [Features](#features) | [Installation](#installation)

</div>

---

## 📱 Progressive Web App (PWA)

This application is fully PWA-compatible and can be installed on:
- 📱 Mobile devices (Android & iOS)
- 💻 Desktop computers (Windows, Mac, Linux)
- 🌐 Works offline after first load

---

## ✨ Features

### 🔐 Smart Authentication System
- **First-time Registration**: Set Employee ID, Role, and Password
- **Auto-Login**: Role automatically saved and pre-selected
- **Password Protected**: Secure login with confirmation
- **Role-based Access**: Worker, Staff, Manager roles

### 📝 Complaint Management
- ✅ Submit new complaints
- ✅ Track complaint status
- ✅ View complaint history
- ✅ Filter by status (Pending, In Progress, Resolved, Closed)
- ✅ Offline functionality with local storage

### 🎨 Modern UI/UX
- 🎭 Animated tyre-themed background
- 🌓 Dark red professional theme
- 📱 Fully responsive design
- ⚡ Smooth transitions and animations
- 🎯 Intuitive navigation

---

## 🚀 Quick Start

### 1️⃣ Clone Repository
```bash
git clone https://github.com/YOUR-USERNAME/stpl-cms.git
cd stpl-cms
```

### 2️⃣ Generate Icons (Important!)
1. Open `generate-icons.html` in your browser
2. Click "Download" on each icon size
3. Create an `icons` folder in the project root
4. Save all downloaded icons in the `icons` folder

### 3️⃣ Deploy to GitHub Pages

#### Option A: Via GitHub Web Interface
1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **main** branch
4. Click **Save**
5. Your app will be live at: `https://YOUR-USERNAME.github.io/stpl-cms/`

#### Option B: Via Git Commands
```bash
git add .
git commit -m "Initial PWA deployment"
git push origin main
```

Then enable GitHub Pages in repository settings.

---

## 📂 Project Structure

```
stpl-cms/
├── index.html                    # Login page
├── Dashboard.html                # Main dashboard
├── new-complaint.html           # New complaint form
├── submitted-complaints.html    # Complaints list
├── manifest.json                # PWA manifest
├── service-worker.js            # Service worker for offline
├── generate-icons.html          # Icon generator tool
├── icons/                       # App icons (create this folder)
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   └── icon-512x512.png
└── README.md                    # This file
```

---

## 🔧 Installation on Devices

### 📱 Android
1. Open the app in Chrome
2. Tap the menu (⋮)
3. Select "Install app" or "Add to Home screen"
4. Confirm installation

### 🍎 iOS
1. Open the app in Safari
2. Tap the Share button
3. Select "Add to Home Screen"
4. Tap "Add"

### 💻 Desktop (Chrome/Edge)
1. Open the app in browser
2. Look for install icon (➕) in address bar
3. Click "Install"
4. App will open in standalone window

---

## 🎯 How to Use

### First Time Setup
1. Open `index.html`
2. Enter Employee ID (e.g., EMP001)
3. Select your Role (Worker/Staff/Manager)
4. Create a password
5. Confirm password
6. Click **LOGIN**

### Subsequent Logins
1. Enter Employee ID
2. Enter password only
3. Click **LOGIN**
   - Role is automatically selected
   - No need to re-enter role or confirm password

### Submit a Complaint
1. Click **New Complaint**
2. Fill in complaint details
3. Click **Submit**
4. Complaint saved and redirected to Dashboard

### View Complaints
1. Click **Submitted Complaints**
2. Filter by status
3. View complaint details

---

## 🛠️ Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling with animations
- **JavaScript** - Logic and interactivity
- **LocalStorage** - Data persistence
- **Service Worker** - Offline functionality
- **PWA Manifest** - App installation
- **GitHub Pages** - Free hosting

---

## 🌐 Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Edge | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Opera | ✅ Full |

---

## 📊 Data Storage

- All data stored locally using **LocalStorage**
- No backend server required
- Data persists across sessions
- Private to each device

---

## 🔒 Security Features

- Password encryption ready (can be enhanced)
- Role-based access control
- Session management
- No data sent to external servers

---

## 🚧 Future Enhancements

- [ ] Admin dashboard
- [ ] Email notifications
- [ ] Export complaints to PDF/Excel
- [ ] Multi-language support
- [ ] Cloud sync option
- [ ] Analytics dashboard
- [ ] Push notifications

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Authors

**Abdullah Shah & Mirza Laiq Ahmed**
- Service Tyre Private Limited
- STPL Development Team

---

## 📧 Support

For support and queries:
- 📧 Email: support@stpl.com
- 🌐 Website: www.stpl.com
- 📞 Phone: +92-XXX-XXXXXXX

---

## 🙏 Acknowledgments

- Developed by: **Abdullah Shah & Mirza Laiq Ahmed**
- Font: [Rajdhani & Orbitron](https://fonts.google.com/)
- Icons: Custom generated
- Theme: Custom tyre-themed design

---

<div align="center">

### ⭐ Star this repo if you find it useful!

Made with ❤️ by **Abdullah Shah & Mirza Laiq Ahmed**  
STPL Development Team

</div>
