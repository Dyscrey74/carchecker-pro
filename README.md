# 🚗 CarChecker Pro

**The #1 Vehicle History Check Platform**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-00d4aa?style=for-the-badge)](https://dyscrey74.github.io/carchecker-pro/)

## 🌐 Live Website

**👉 [https://dyscrey74.github.io/carchecker-pro/](https://dyscrey74.github.io/carchecker-pro/)**

## ✨ Features

- **🔍 VIN Lookup** - Decode any Vehicle Identification Number instantly
- **🚘 License Plate Search** - Search by license plate with country/state selection
- **👤 User Authentication** - Sign up/login with Email, Google OAuth, or Apple
- **📊 User Dashboard** - Track your reports, vehicles, and order history
- **📱 Fully Responsive** - Works on desktop, tablet, and mobile
- **🎨 Modern Dark UI** - Professional design with smooth animations

## 🛠️ Tech Stack

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript
- **Authentication**: Supabase Auth (Email, Google OAuth, Apple OAuth)
- **Database**: Supabase PostgreSQL
- **Hosting**: GitHub Pages
- **Automation**: n8n workflows

## 🚀 Quick Start

### View the Live Site
Simply visit: **https://dyscrey74.github.io/carchecker-pro/**

### Local Development
1. Clone this repository:
   ```bash
   git clone https://github.com/Dyscrey74/carchecker-pro.git
   ```
2. Open `index.html` in your browser
3. Or use a local server:
   ```bash
   npx serve .
   ```

## 📁 Project Structure

```
carchecker-pro/
├── index.html          # Main application (single-page app)
├── README.md           # This file
└── supabase-setup.sql  # Database schema (for reference)
```

## 🔧 Configuration

### Supabase Setup
The app uses Supabase for authentication and database. Configuration is in `index.html`:

```javascript
const SUPABASE_URL = 'https://your-project.supabase.co';
const SUPABASE_ANON_KEY = 'your-anon-key';
```

### n8n Webhooks
The app integrates with n8n for:
- VIN lookup API calls
- Premium report generation
- Email notifications

## 🔐 Authentication Methods

1. **Email/Password** - Traditional signup/login
2. **Google OAuth** - One-click Google sign-in
3. **Apple OAuth** - Sign in with Apple (coming soon)

## 📊 Database Tables

- `profiles` - User profile information
- `vehicles` - Saved vehicles
- `reports` - Generated vehicle reports
- `orders` - Purchase history

## 🚀 Deployment

### GitHub Pages (Current)
The site automatically deploys to GitHub Pages when you push to `main` branch.

### Manual Deployment via n8n
Use the GitHub Deploy workflow in n8n to push updates.

## 📝 License

MIT License - feel free to use this for your own projects!

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

**Built with ❤️ for car buyers everywhere**
