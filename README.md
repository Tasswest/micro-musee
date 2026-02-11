# MicroMusée Project

## Structure
- **root**: Main category pages (`index.html`, `livres.html`, etc.)
- **items/**: Individual content pages for each artwork/book/etc.
- **scripts/**: Python maintenance scripts.
- **css/**, **js/**, **images/**, **audio/**: Resources.

## Image Hosting
To host your images online and share your site:

1.  **Create a GitHub Repository**:
    - Go to [GitHub.com](https://github.com/new).
    - Create a new repository name (e.g., `micro-musee`).
    - Do not check "Initialize with README".

2.  **Push your code**:
    - Open your terminal in this folder.
    - Run the following commands (replace `YOUR_USERNAME` and `REPO_NAME`):
      ```bash
      git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
      git branch -M main
      git push -u origin main
      ```

3.  **Activate GitHub Pages**:
    - Go to your repository settings on GitHub.
    - Go to "Pages" sidebar item.
    - Under "Build and deployment" > "Source", select `main` branch.
    - Click Save.

4.  **Get Image Links**:
    - Your images will be available at:
      `https://YOUR_USERNAME.github.io/REPO_NAME/images/FILENAME.jpg`
