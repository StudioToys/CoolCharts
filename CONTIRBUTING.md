# Contributing to CoolCharts.org

Thank you for your interest in helping expand CoolCharts!

---

## 🧩 What You Can Add
- New chart categories or topics in **pages.html**
- New Google Sheets embeds for data tables
- HTML or CSS improvements
- Explanatory text, icons, or emoji refinements
- Educational links in resource sections

---

## 🧠 How to Contribute
1. **Fork** this repository on GitHub.  
2. **Edit or add** files (usually `pages.html`, `sidebar-list.js`, or new `.html` pages).  
3. **Preview locally** by opening `index.html` in a browser.  
4. **Commit and open a Pull Request (PR)** describing what you changed and why.

---

## 🏷️ Style & Structure
- Use concise, educational language.  
- Keep emoji-based section headers consistent (🌿, 🧠, ⚙️ etc.).  
- Each chart section should have:
  ```html
  <div class="content-topic" data-page="topic">
      <div class="content-title">🌿 TITLE <span class="bookmark-star" data-bookmark="topic">☆</span></div>
      <div class="description">Short explanation here.</div>
      <iframe class="nutrition-sheet" data-src="https://docs.google.com/spreadsheets/..."></iframe>
  </div>
