# VAP OS Publisher - Privacy Policy & Compliance

This repository hosts the official Privacy Policy, User Data Deletion Instructions, and Terms of Service for **VAP OS Publisher** (Meta App ID: `3292835964437949`), optimized for **GitHub Pages**.

---

## 📄 Pages Included

1. **`index.html`**: Privacy Policy (compliant with Meta Developer Policies, GDPR, and CCPA).
2. **`data-deletion.html`**: Official User Data Deletion Instructions required by Meta for switching an app to **Live Mode**.
3. **`terms.html`**: Terms of Service.

---

## 🚀 Quick Setup: Deploying to GitHub Pages

### 1. Initialize Git in this directory
From this directory (`/Users/macbook/Documents/repos/vapos-privacy-policy`):

```bash
cd /Users/macbook/Documents/repos/vapos-privacy-policy
git init
git add .
git commit -m "Initial commit: Privacy Policy, Data Deletion instructions, and Terms for VAP OS Publisher"
git branch -M main
```

### 2. Create the repository on GitHub
Create a new public repository on GitHub (for example, named `vapos-privacy-policy`) under your account (`La-Bruja-Software` or personal profile).

Then link and push:
```bash
git remote add origin git@github.com:La-Bruja-Software/vapos-privacy-policy.git
# Or using HTTPS:
# git remote add origin https://github.com/La-Bruja-Software/vapos-privacy-policy.git

git push -u origin main
```

### 3. Enable GitHub Pages
1. Go to your repository on GitHub: `https://github.com/La-Bruja-Software/vapos-privacy-policy`
2. Click **Settings** &rarr; **Pages** (in the left sidebar).
3. Under **Build and deployment** &rarr; **Branch**:
   - Select **`main`** branch.
   - Select **`/ (root)`** folder.
   - Click **Save**.
4. Within 1 minute, GitHub Pages will deploy your site!

---

## 🔗 Live URLs to paste into Meta for Developers

Once deployed, copy and paste these exact links into your Meta App Settings ([developers.facebook.com/apps](https://developers.facebook.com/apps) &rarr; **VAP OS Publisher** &rarr; **App Settings** &rarr; **Basic**):

| Meta Field | URL |
| :--- | :--- |
| **Privacy Policy URL** | `https://la-bruja-software.github.io/vapos-privacy-policy/` |
| **User Data Deletion URL** | `https://la-bruja-software.github.io/vapos-privacy-policy/data-deletion.html` |
| **Terms of Service URL** | `https://la-bruja-software.github.io/vapos-privacy-policy/terms.html` |
| **Category** | `Business and Pages` |
| **App Contact Email** | `labrujasiete@gmail.com` |

---

## 🔒 Switching Meta App to "Live Mode"

After filling in the URLs above:
1. In the top bar of the Meta App Dashboard, toggle **In development** &rarr; **Live**.
2. Click **Switch Mode**.
3. Done! Now your Facebook Page posts published via VAP OS will be visible to the general public, friends, and your personal account!
