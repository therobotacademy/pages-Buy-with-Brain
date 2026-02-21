# Static Site Deployment - Buy with Brain

This repository contains the production build of the [Buy with Brain](https://github.com/therobotacademy/Buy-with-Brain#) React application. Fid the site at:

https://therobotacademy.github.io/pages-Buy-with-Brain/index.html

## 🚀 How to Deploy on Digital Ocean App Platform

This repo is optimized for a **Static Site** deployment.

1. **Create a New App**: Go to the Digital Ocean App Platform.
2. **Select Repository**: Connect your GitHub/GitLab account and select **this** repository (the one containing the `build/` folder contents).
3. **Configure App**:
   * **Resource Type**: Ensure it's detected as a **Static Site**.
   * **Build Command**: Leave empty (the site is already built).
   * **Output Directory**: `.` (root of the repo).
4. **Deploy**: Click "Create Resources".

## 📦 Contents

- `index.html`: Main entry point.
- `static/`: Bundled CSS and JavaScript assets.
- `asset-manifest.json`: Metadata about the build assets.

## 🛠 Features

- **Relative Paths**: This build uses relative paths, making it portable and compatible with the `file://` protocol.
- **Optimized**: Minified and compressed assets for production performance.
