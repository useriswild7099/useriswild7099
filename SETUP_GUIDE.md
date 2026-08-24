# 🚀 Prince Tigga's GitHub Profile Deployment Guide

This guide walks you through publishing your **Minimalist Obsidian GitHub Profile** to [`github.com/useriswild7099`](https://github.com/useriswild7099) in 3 simple steps.

---

## 📌 Step 1: Create Your Profile Repository on GitHub

1. Open [GitHub: New Repository](https://github.com/new).
2. Set the **Repository name** to:
   ```
   useriswild7099
   ```
   *(GitHub will show a special banner confirming this creates your public profile README).*
3. Set visibility to **Public**.
4. Leave *Add a README file* unchecked (since you already have your production README prepared).
5. Click **Create repository**.

---

## 🐍 Step 2: Enable GitHub Actions Workflow Permissions

The snake contribution workflow in [`.github/workflows/snake-contribution.yml`](file:///f:/hermes%20projects/github%20upgrage/.github/workflows/snake-contribution.yml) runs every midnight to generate your live contribution snake animation.

To grant write permissions:
1. In your `useriswild7099/useriswild7099` repository, click **Settings** (top tab).
2. In the left navigation menu, click **Actions** → **General**.
3. Scroll down to **Workflow permissions**.
4. Select **Read and write permissions**.
5. Click **Save**.
6. Go to the **Actions** tab, select **Generate Contribution Snake** from the left menu, and click **Run workflow** to generate your first live snake immediately.

---

## 📤 Step 3: Push All Files to GitHub

Run these commands inside your local workspace directory (`f:\hermes projects\github upgrage`):

```bash
git init
git add .
git commit -m "feat: launch Prince Tigga minimalist obsidian profile"
git branch -M main
git remote add origin https://github.com/useriswild7099/useriswild7099.git
git push -u origin main
```

---

## 📁 Repository Overview

- [`README.md`](file:///f:/hermes%20projects/github%20upgrage/README.md): Master profile featuring:
  - Custom vector hero banner for **Prince Tigga**
  - Dynamic typing subtitle
  - **Neural x Hackathon (Winner)** & **Dehradun Cyber Hackathon (Finalist)** showcases
  - Ventures: **Artificial Studio** & **Steady Pulse AI**
  - **Dual-Axis Solar Tracker**, **Digital Notice Board**, **U-DELT**, and **neo.ai**
  - Live GitHub metrics (`@useriswild7099`) & daily snake graph
  - Direct LinkedIn & Email contact links
- [`assets/header-banner.svg`](file:///f:/hermes%20projects/github%20upgrage/assets/header-banner.svg): Vector SVG banner tailored to your name and engineering credentials.
- [`assets/divider.svg`](file:///f:/hermes%20projects/github%20upgrage/assets/divider.svg): Obsidian glowing line divider.
- [`.github/workflows/snake-contribution.yml`](file:///f:/hermes%20projects/github%20upgrage/.github/workflows/snake-contribution.yml): Automated contribution snake animation generator.
