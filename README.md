# BharatPass — Digital Transit Pass System 🚌

BharatPass is a digital solution for bus and train passes, replacing paper-based systems with secure QR codes and online payments.

## 📄 Documentation
For detailed project documentation, system architecture, and workflows, please refer to:
👉 **[PROJECT_REPORT.md](./PROJECT_REPORT.md)**

## 🚀 Quick Start
1. **Install Dependencies**:
   ```bash
   npm install
   ```
2. **Start Server**:
   ```bash
   npm start
   ```
3. **Open Browser**:
   Visit `http://localhost:3000`

## Deploy on Render

This project includes `render.yaml` for deployment as a Render Web Service.

1. Push the project to GitHub.
2. In Render, choose **New → Blueprint** and select the repository.
3. Set the `MONGODB_URI` environment variable to your MongoDB Atlas connection string.
4. Deploy. Render uses `npm install`, `npm start`, and `/api/health` automatically.
5. Open the generated HTTPS URL. The conductor page is at `/conductor/scanner.html`.

Never commit `.env`; add the MongoDB connection string in Render's Environment settings.

## 👥 Demo Credentials
| Role | Email | Password |
| :--- | :--- | :--- |
| **Admin** | `admin@pass.com` | `demo123` |
| **User** | `user@pass.com` | `demo123` |
| **Conductor** | `conductor@pass.com` | `demo123` |

## 🛠️ Tech Stack
- **Frontend**: Vanilla HTML/JS, CSS (Glassmorphism)
- **Backend**: Node.js, Express
- **Core Library**: `qrcode`
- **Database**: `localStorage` (Demo Mode)

---
Developed as a college project.
