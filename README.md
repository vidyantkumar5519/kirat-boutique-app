# Kirat Boutique — Android Mobile App

This project packages **Kirat Boutique (Mobile Manager)** into an installable Android APK using Capacitor and GitHub Actions.

---

## 🚀 How to Build Your APK with GitHub (Step-by-Step)

Because this repository includes an automated GitHub Actions workflow (`.github/workflows/build-apk.yml`), you do **not** need Android Studio or Java installed on your computer. GitHub builds the APK in the cloud for free!

### Step 1: Create a New GitHub Repository
1. Go to [github.com/new](https://github.com/new).
2. Name your repository (for example, `kirat-boutique-apk`).
3. Set it to **Public** or **Private**.
4. Leave "Add a README file" **unchecked** (we already have one).
5. Click **Create repository**.

### Step 2: Push this Project to GitHub
In your terminal, navigate to this project folder and run:

```bash
git commit -m "Initial commit: Kirat Boutique Android App with GitHub Actions"
git branch -M main
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/<YOUR_REPOSITORY_NAME>.git
git push -u origin main
```
*(Replace `<YOUR_GITHUB_USERNAME>` and `<YOUR_REPOSITORY_NAME>` with your GitHub details).*

---

### Step 3: Download Your APK
1. Open your repository on GitHub.
2. Click the **Actions** tab at the top.
3. You will see a workflow running named **"Build Android APK"**.
4. Click on the running workflow (it takes ~1.5 to 2 minutes to complete).
5. Once finished with a green checkmark, scroll down to the **Artifacts** section at the bottom.
6. Click **Kirat-Boutique-Manager-APK** to download your zip file.
7. Unzip the file to find `app-debug.apk` and transfer/install it on any Android device!

---

## 📱 Features Configured
- **Embedded App**: Your full `boutique-manager.html` is packaged inside `www/index.html`.
- **Local Storage & Offline Support**: Works 100% offline with full data persistence.
- **Android Permissions**: Handles file imports (JSON backups) and local storage out of the box.
- **Package ID**: `com.kirat.boutique`
