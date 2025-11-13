# 🚀 How to Upload to GitHub and Get Links

## ✅ Files Ready for Upload (in Group_H_GitHub folder):
- `Presentation.html` - Presentation viewer (displays PDF)
- `Group_H_Presentation.pdf` - Original presentation PDF
- `Report_Web.html` - Full web report  
- `Report_Group_H.pdf` - Original report PDF (backup)
- `Final_EDA_Group_H.html` - Technical analysis
- `README.md` - Repository description

---

## 📝 Step-by-Step Guide

### Method 1: Using GitHub Website (Easiest - No Command Line)

#### Step 1: Create Repository
1. Go to https://github.com/new
2. Repository name: `wind-energy-analytics` (or any name you want)
3. Description: "Wind Energy Curtailment Analysis - Orkney Islands"
4. ✅ Public (so it can be hosted on GitHub Pages)
5. ❌ Don't initialize with README (we have one)
6. Click **Create repository**

#### Step 2: Upload Files
1. On your new repo page, click **uploading an existing file**
2. Drag all 6 files from `Group_H_GitHub` folder:
   - Presentation.html
   - Group_H_Presentation.pdf
   - Report_Web.html
   - Report_Group_H.pdf
   - Final_EDA_Group_H.html
   - README.md
3. Commit message: "Add wind energy analytics project"
4. Click **Commit changes**

#### Step 3: Enable GitHub Pages
1. Go to **Settings** tab (in your repo)
2. Scroll to **Pages** section (left sidebar)
3. Source: Select **main** branch
4. Click **Save**
5. Wait 1-2 minutes

#### Step 4: Get Your Links! 🎉
Your site URL will be:
```
https://YOUR-USERNAME.github.io/wind-energy-analytics/
```

Your specific file links:
- **Presentation:** `https://YOUR-USERNAME.github.io/wind-energy-analytics/Presentation.html`
- **Report:** `https://YOUR-USERNAME.github.io/wind-energy-analytics/Report_Web.html`
- **Technical:** `https://YOUR-USERNAME.github.io/wind-energy-analytics/Final_EDA_Group_H.html`

**IMPORTANT:** After uploading, edit `Presentation.html` and replace `YOUR-USERNAME` with your actual GitHub username in the iframe URL.

---

### Method 2: Using Command Line (For Developers)

```bash
# Navigate to the GitHub folder
cd "/Users/harsh/Documents/Imperial/Semester3/Analytics_in_Business/Group_H_GitHub"

# Initialize git
git init
git add .
git commit -m "Add wind energy analytics project"
git branch -M main

# Connect to GitHub (create repo on GitHub.com first!)
git remote add origin https://github.com/YOUR-USERNAME/wind-energy-analytics.git
git push -u origin main
```

Then follow **Step 3** above to enable GitHub Pages.

---

## 📱 Share on LinkedIn

Once your GitHub Pages is live, use these templates:

### Short Version:
```
⚡ Wind Energy Curtailment Analysis

Analyzed 217 GWh of wasted renewable energy across 500 turbines 
in Scotland's Orkney Islands.

🎤 Presentation: [your-github-pages-link]
📄 Report: [your-github-pages-link]

#DataAnalytics #RenewableEnergy #Python
```

### Detailed Version:
```
🌊 Just completed a comprehensive wind energy analytics project!

Analyzed 2+ years of turbine data (1.4M+ records) to design demand 
response programs for Scotland's Orkney Islands.

📊 Key Results:
• 217 GWh curtailed energy annually
• 5,192 households needed for 50% DR
• $9.1M grid cost savings potential
• 6,652 tonnes CO₂ reduction

🔗 View interactive presentation: [link]
📄 Read full report: [link]

Tech: Python | Pandas | Matplotlib | Scikit-learn

#DataAnalytics #RenewableEnergy #Sustainability #Python
```

---

## 🔗 Add to LinkedIn Profile

1. **Featured Section:**
   - Click "Add profile section" → "Recommended" → "Add featured"
   - Choose "Link"
   - Paste your GitHub Pages presentation link
   - Title: "Wind Energy Curtailment Analysis"

2. **Experience Section:**
   - Add as a project under Imperial College London
   - Include GitHub link in description

3. **Projects Section:**
   - Add as standalone project
   - Include both presentation and report links

---

## ✅ Checklist

- [ ] Created GitHub account (if you don't have one)
- [ ] Created new repository
- [ ] Uploaded all 4 files
- [ ] Enabled GitHub Pages
- [ ] Waited 2 minutes for deployment
- [ ] Tested links in browser
- [ ] Added to LinkedIn Featured section
- [ ] Posted on LinkedIn feed

---

## 🆘 Troubleshooting

**Q: GitHub Pages not working?**
- Wait 2-3 minutes after enabling
- Make sure repo is Public, not Private
- Check Settings → Pages shows green checkmark

**Q: Files not displaying correctly?**
- All 4 files must be in the root (not in subfolders)
- Filenames are case-sensitive

**Q: Want a custom domain?**
- Buy domain from Namecheap (~$12/year)
- Add in GitHub Pages settings
- Update DNS records

---

## 📧 Your GitHub Pages URLs

Replace `YOUR-USERNAME` with your GitHub username:

- **Presentation:** 
  `https://YOUR-USERNAME.github.io/wind-energy-analytics/Presentation.html`

- **Report:** 
  `https://YOUR-USERNAME.github.io/wind-energy-analytics/Report_Web.html`

- **Technical Analysis:** 
  `https://YOUR-USERNAME.github.io/wind-energy-analytics/Final_EDA_Group_H.html`

---

**That's it! You're done! 🎉**

Your work is now live on the internet and ready to share on LinkedIn!

