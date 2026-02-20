# United for Autonomy - GitHub Deployment Files

## 📦 What's in This Zip

This zip file contains everything you need to deploy your website to GitHub and Netlify:

```
united-for-autonomy/
├── index.html          → Your main website
├── generic.jpg         → Hero background image
└── admin/              → Decap CMS files
    ├── config.yml      → CMS configuration
    └── index.html      → Admin panel interface
```

---

## 🚀 Quick Deployment (3 Steps)

### Step 1: Create GitHub Repository
1. Go to [github.com](https://github.com)
2. Click "+" → "New repository"
3. Name: `united-for-autonomy`
4. Click "Create repository"

### Step 2: Upload These Files
1. **Unzip this file first!**
2. On your GitHub repository page, click "uploading an existing file"
3. Drag the **contents** of the `united-for-autonomy` folder:
   - `index.html`
   - `generic.jpg`
   - `admin` folder (the whole folder)
4. Commit changes

### Step 3: Deploy to Netlify
1. Go to [app.netlify.com](https://app.netlify.com)
2. Sign up with GitHub
3. "Import existing project" → Select your repository
4. Click "Deploy"

---

## ✅ File Structure on GitHub

Your repository should look like this:

```
(root of repository)
├── index.html
├── generic.jpg
└── admin/
    ├── config.yml
    └── index.html
```

**IMPORTANT:** Don't upload the `united-for-autonomy` folder itself - upload its CONTENTS!

---

## 📋 After Deployment

Once deployed on Netlify:

1. **Enable Netlify Identity:**
   - Site configuration → Identity → Enable Identity
   - Set to "Invite only"
   
2. **Enable Git Gateway:**
   - Identity → Services → Enable Git Gateway
   
3. **Invite yourself:**
   - Identity → Invite users → Enter your email
   - Accept the invitation in your email
   
4. **Access admin panel:**
   - Go to `yoursite.netlify.app/admin`
   - Log in and start adding press releases!

---

## 📖 Full Instructions

For detailed step-by-step instructions with screenshots, see:
- **DECAP-QUICK-START.md**
- **DECAP-DEPLOYMENT-GUIDE.md**

(These should be in your downloads folder)

---

## 🆘 Need Help?

**Common Issues:**

**Q: Files uploaded to wrong place?**
A: Make sure you're uploading the CONTENTS of the `united-for-autonomy` folder, not the folder itself.

**Q: Admin panel won't load?**
A: Make sure the `admin` folder is in the root of your repository with both files inside.

**Q: Can't log in to CMS?**
A: Make sure you enabled Netlify Identity and Git Gateway, and accepted the email invitation.

---

## ✨ You're All Set!

Total deployment time: ~20 minutes

Your website will be live with a fully functional CMS for managing press releases!

Good luck! 🚀
