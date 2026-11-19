# 🚨 India Emergency & Travel SOS Directory

A high-performance, mobile-responsive, zero-dependency emergency directory web application ready for deployment on **GitHub Pages** (100% free).

---

## 📱 Live Features
- **Mobile Tap-to-Call (`tel:`):** Instant one-tap dialing for all national, transit, and local emergency helplines.
- **Save to Phone (.VCF Contact Card):** One-click download button for iOS & Android to automatically save all emergency numbers into contacts.
- **Tabs Architecture:**
  1. `⚡ Speed Dial (SOS)`: The top 9 essential speed-dial helplines.
  2. `🇮🇳 Pan-India`: Full national directory (112, 100, 101, 108/102, 1091, 181, 1098, 14567, 1033, Tele-MANAS, NDRF).
  3. `🚆 Transit & Travel`: RailMadad 139, Mumbai Local 1512, Metro lines (Mumbai & Hyderabad), Cab / Auto SOS protocol.
  4. `🌊 Mumbai City`: Mumbai Police, Women Helpline 103, BMC Disaster 1916, Traffic, Thane, Navi Mumbai.
  5. `🏛️ Hyderabad City`: Dial 100, SHE Teams, Cyberabad IT Corridor Safety, Rachakonda, GHMC DRF.
- **Real-Time Live Search:** Filter any service, number, or city instantly.
- **Integrated High-Res Infographic:** Built-in modal preview and download button for the emergency wallpaper/poster card.
- **Dark / Light Mode:** Automatic system preference detection with manual toggle.

---

## 🚀 How to Host on GitHub Pages (Free in 1 Minute)

### Option 1: Via GitHub Web Interface
1. Create a new public repository on GitHub (e.g., `india-emergency-helplines`).
2. Upload the files in this folder (`index.html`, `emergency_contacts_india.vcf`, `emergency_helplines_india.jpg`).
3. In your GitHub repo, go to **Settings** > **Pages** (under the "Code and automation" section).
4. Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/ (root)`.
5. Click **Save**. Within 60 seconds, your site is live at:
   `https://<your-username>.github.io/india-emergency-helplines/`

### Option 2: Via Terminal (Git CLI)
```bash
cd /Users/naren/Documents/Personal/india-emergency-helplines
git init
git add .
git commit -m "Initial commit of India Emergency SOS Directory"
git branch -M main
# Create repo with gh CLI or link to remote:
# gh repo create india-emergency-helplines --public --source=. --remote=origin --push
```
Then enable Pages under Repository Settings -> Pages.

---

## 📂 Included Assets
- `index.html`: Fully self-contained single-page web app.
- `emergency_contacts_india.vcf`: Multi-contact vCard 3.0 file compatible with iOS & Android.
- `emergency_helplines_india.jpg`: High-resolution 9:16 emergency infographic card.
