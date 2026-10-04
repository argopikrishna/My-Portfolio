# A R Gopikrishna — Data Engineer Portfolio

Personal developer and data engineering portfolio website for **A R Gopikrishna**, built with semantic HTML5, modern CSS3, and vanilla ES6+ JavaScript.

Features a high-performance zero-dependency architecture with no build steps, instant loading, and seamless GitHub Pages deployment.

---

## 🚀 Key Highlights & Sections

* **Hero & Network Canvas:** Dynamic 2D HTML5 canvas rendering distributed data nodes that interact with pointer movement, paired with split-character typography and animated role rotation.
* **Interactive Data Terminal:** Built-in command-line terminal in the About section supporting interactive queries (`help`, `whoami`, `experience`, `wbd`, `skills`, `projects`, `education`, `contact`, `resume`, `sudo hire gopi`) with command history and tab autocompletion.
* **Enterprise Experience Timeline:** Visually prominent vertical timeline spotlighting work at **Warner Bros. Discovery** (Data Engineer Intern), alongside training at Software Campus and EDUNET Foundation (IBM SkillsBuild).
* **Technical Projects:**
  1. **UPSC Essay Evaluation System:** Multi-agent evaluation flow using LangGraph, Streamlit, and OpenRouter with parallel rubric pipelines.
  2. **Smoking Cessation Detection:** Machine learning pipeline using PCA, LDA, GridSearchCV, and a VotingClassifier (92.3% Accuracy, 0.94 ROC-AUC).
  3. **Batua — Income & Expense Tracker:** Desktop application built with Java Swing and MySQL utilizing DAO patterns, Prepared Statements, and jBCrypt encryption.
* **Skills Bento & Education:** Bento-grid architecture categorizing Data Engineering, Machine Learning, Cloud & Tools, and Software Development, with dedicated academic highlights from **SRM University–AP** (B.Tech CSE - Big Data, Minor in Mathematics, 8.81/10 CGPA).
* **Physics & Micro-Interactions:** Cursor-following spotlight border illumination, 3D card tilt, magnetic buttons, scroll-reveal observer, and top scroll progress tracker.
* **Accessibility & Performance:** Zero runtime dependencies, native lazy asset loading, semantic markup, and full support for `prefers-reduced-motion: reduce`.

---

## 🛠️ Local Development

Because this project uses vanilla web standards, you can preview it immediately using any local web server:

### Using Python 3:
```bash
python3 -m http.server 8000
```
Then open [http://localhost:8000](http://localhost:8000) in your browser.

### Using Node.js (npx):
```bash
npx serve .
```

---

## 📦 Deployment to GitHub Pages

The repository includes a ready-to-use GitHub Actions workflow at [`.github/workflows/static.yml`](.github/workflows/static.yml) for GitHub Pages.

To deploy:
1. Initialize git and commit your files:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of A R Gopikrishna portfolio"
   ```
2. Create your repository on GitHub and link the remote:
   ```bash
   git remote add origin https://github.com/argopikrishna/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```
3. In your GitHub repository:
   * Go to **Settings** > **Pages**.
   * Under **Build and deployment** > **Source**, choose **GitHub Actions**.
   * The included action will automatically build and publish your site at `https://argopikrishna.github.io/<repo-name>/`.
