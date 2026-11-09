# Personal Portfolio Website — Azizbek Xajibayev (Zizx4uM)

Live personal portfolio website designed for **GitHub Pages**.

## 🚀 Quick Deployment to GitHub Pages

To publish this website live at `https://zizx4um.github.io`:

1. **Create a new repository on GitHub named**:
   ```
   Zizx4uM.github.io
   ```
   *(Make sure it is public)*

2. **Initialize and push this directory**:
   ```bash
   cd /home/zaax/Projects/portfolio-website
   git init -b main
   git add .
   git commit -m "feat: initial portfolio website launch"
   git remote add origin git@github.com:Zizx4uM/Zizx4uM.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub: `Settings` > `Pages`.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select Branch: `main`, folder: `/ (root)`.
   - Click **Save**.

Your portfolio will be live at:
👉 **https://zizx4um.github.io**

---

## 💻 Local Preview

To test or preview locally:

```bash
cd /home/zaax/Projects/portfolio-website
python3 -m http.server 8000
```
Then open `http://localhost:8000` in your browser.
