# Deployment Guide: Cloud Architect Portfolio

Follow these steps to take your high-fidelity "Professional Journey" screen from this workspace to a live URL on GitHub Pages or Vercel.

## 1. Export the Code
- Select the **History | Professional Journey (Premium Polish)** screen on the canvas.
- Click the **View Code** (`</>`) icon in the toolbar.
- Copy the entire HTML/CSS block.

## 2. Setup Your GitHub Repository
1. Log in to your [GitHub account](https://github.com/).
2. Create a new repository named `dev-portfolio` (or your preferred name).
3. Keep it **Public** and click **Create repository**.

## 3. Upload Files
1. In your new repository, click **"uploading an existing file"** or use the command line.
2. Create a new file named `index.html`.
3. Paste the code you copied from Step 1 into this file and save/commit.

## 4. Go Live
### Option A: GitHub Pages (Free & Simple)
- Go to your repository **Settings** > **Pages**.
- Under **Build and deployment**, set the source to **Deploy from a branch**.
- Select the `main` branch and `/ (root)` folder. Click **Save**.
- Your site will be live at `https://raghavendra2006.github.io/dev-portfolio/` in a few minutes.

### Option B: Vercel (Recommended for DevOps)
- Go to [Vercel.com](https://vercel.com/) and sign in with GitHub.
- Click **Add New** > **Project**.
- Import your `dev-portfolio` repository.
- Click **Deploy**. Vercel will provide a professional, fast-loading URL.

## Professional Pro-Tip
As a Cloud & DevOps professional, you can also deploy this using an **AWS S3 Bucket** configured for static website hosting, fronted by **CloudFront** for SSL and edge caching. This directly demonstrates the skills listed on your resume!