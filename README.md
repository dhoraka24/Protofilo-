# Dhoraka S P — Personal Portfolio Website

A personal portfolio built for **Dhoraka S P** (Full Stack Developer & UI/UX Designer | Final-year ECE student at PSNA College of Engineering and Technology).

Designed with human-centered aesthetics, semantic HTML, mobile-first responsiveness, and performance standards.

---

## 🚀 Tech Stack

- **Framework:** React 18 + Vite
- **Styling:** Tailwind CSS (with bespoke Figma-inspired design tokens)
- **Icons:** Lucide React
- **Design System:** Left-aligned editorial hierarchy, Indigo/Violet accent (`#6366f1`), light/dark theme toggle (respects system preference & remembers choice in localStorage)
- **Deployment:** GitHub Pages (via GitHub Actions & `gh-pages`), Render, Vercel, or Netlify

---

## 🛠️ Local Development

### 1. Install Dependencies
```bash
npm install
```

### 2. Run the Development Server
```bash
npm run dev
```
Open your browser at `http://localhost:3000/`.

### 3. Build for Production
```bash
npm run build
```
Generates a static production bundle in `dist/` with relative asset paths.

### 4. Preview the Production Build
```bash
npm run preview
```

---

## 🌐 Deploy to GitHub

### Option A: GitHub Actions (Recommended & Automated)

1. Create a new repository on your GitHub account (`https://github.com/dhoraka24/`):
   - Name: `portfolio` (or `Protofilo` / `dhoraka24.github.io`)
   - Visibility: **Public**

2. Link your local repository and push:
   ```bash
   git remote add origin https://github.com/dhoraka24/portfolio.git
   git branch -M main
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - On GitHub, go to your repository **Settings** -> **Pages**.
   - Under **Build and deployment** > **Source**, select **GitHub Actions**.
   - The included workflow in `.github/workflows/deploy.yml` will automatically build and publish your site!

---

### Option B: Deploy via CLI (`gh-pages`)

If you prefer to deploy directly from your local terminal to the `gh-pages` branch:
```bash
npm run deploy
```
Then in GitHub repository **Settings** -> **Pages**, set the Source branch to `gh-pages` / `/ (root)`.

---

## 📋 TODOs & Items to Fill

Before your final showcase, update these specific placeholders:

1. **Project Links (`src/data/portfolioData.js`):**
   - [ ] **AI Resume Analyzer:** Add GitHub repository URL, Live demo URL, and Figma link.
   - [ ] **Real-Time Security Event Monitoring Dashboard:** Add GitHub URL and Live demo URL.
   - [ ] **Tournament Booking Platform:** Add GitHub URL and Live demo URL.
   - [ ] **UI/UX Mobile App Concept:** Add Figma community / prototype link.
   - [ ] Additional projects (NeuroShield AI, Decentralized Voting System, CBT Companion, etc.): Add repos if published.

2. **Resume PDF (`public/resume.pdf`):**
   - [ ] Place your updated resume file named `resume.pdf` into the `public/` directory. The "Resume" modal download button will instantly serve it.

3. **Project Screenshots & Mockups (`public/images/`):**
   - [ ] Replace the placeholder visual frames in `src/components/Projects.jsx` and `ProjectModal.jsx` with real UI screenshots or Figma renders.

---

## 👤 Profile Details (Verified Source of Truth)

- **Name:** Dhoraka S P
- **Role:** Full Stack Developer & UI/UX Designer | ECE Graduate
- **Education:** B.E. ECE (2023–2027), PSNA College of Engineering and Technology (CGPA 7.84)
- **Higher Secondary:** SMBM Higher Secondary School, Dindigul (72%)
- **Email:** dhorakanataraj@gmail.com
- **Phone:** +91 6369310170
- **LinkedIn:** https://www.linkedin.com/in/dhoraka-nataraj
- **GitHub:** https://github.com/dhoraka24
- **Location:** Dindigul, Tamil Nadu, India
