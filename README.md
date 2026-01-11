# TabControl Privacy Policy

Privacy Policy page for the TabControl Chrome/Opera Extension.

**Live URL:** [https://mello2110.github.io/TabControl-Privacy-Policy/](https://mello2110.github.io/TabControlPrivatePolicy/)

## Deployment Instructions

Since this repository was created locally, you need to push it to GitHub manually to activate the Privacy Policy page.

### 1. Create Repository on GitHub
1. Go to https://github.com/new
2. Repository name: `tabcontrol-privacy-policy`
3. Make it **Public**
4. Do **not** initialize with README/gitignore (create empty repo)
5. Click **Create repository**

### 2. Push Code
Run these commands in your terminal (inside this folder):

```powershell
git init
git add .
git commit -m "Initial commit: Privacy Policy page"
git branch -M main
git remote add origin https://github.com/[YOUR_GITHUB_USERNAME]/tabcontrol-privacy-policy.git
git push -u origin main
```

*(Replace `[YOUR_GITHUB_USERNAME]` with your actual GitHub username)*

### 3. Activate GitHub Pages
1. Go to your new repo **Settings** > **Pages**
2. Under "Build and deployment", select **Source**: `Deploy from a branch`
3. Select **Branch**: `main` / `root`
4. Click **Save**

Wait about 60 seconds, and your site will be live at the URL shown in the settings.

### 4. Chrome Web Store / Opera Sync
Copy the generated URL (e.g., `https://username.github.io/TabControl-Privacy-Policy/`) and paste it into the **Privacy Policy URL** field in your extension's store listing.

## Licensing

**TabControl** is dual-licensed:

*   **[Apache License 2.0](LICENSE)**: Free for personal use, education, and open-source contribution.
*   **[Commercial License](COMMERCIAL_LICENSE.md)**: Required for commercial use, proprietary integration, or revenue-generating activities > €10k/year.

