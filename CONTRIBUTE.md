# 🤝 Contributing to GeekUp GitHub Profile

Welcome to **GeekUp GitHub Profile** — and thanks for considering a contribution!  
We’re building a curated galaxy of awesome GitHub profile READMEs — creative, useful, and fun. 🌌  

Your help makes this collection shine brighter ⭐

---

## 🧭 Before You Start

This is a **curated** collection — meaning we focus on *quality over quantity*.  
Please contribute READMEs that are:
- 💡 Unique or visually creative  
- 🧰 Technically useful (badges, APIs, layouts, animations, etc.)  
- 🌈 Aesthetically consistent and easy to read  
- 🎯 Original — not copy-pasted from someone else  

If you’d like to discuss ideas before contributing, please [open an issue](../../issues).

---

## ⚙️ How to Contribute

Follow these simple steps to beam your README into the **Geek-i-verse 🪐**

### 🪄 Step-by-Step Guide

1. **Fork this repository**  
   Click the **Fork** button in the top-right corner of this page.

2. **Clone your fork to your local machine**
   ```bash
   git clone https://github.com/<your-username>/geekup-github-profile.git
   cd geekup-github-profile
   ```

3. **Create a new branch**
   ```bash
   git checkout -b add_<your-username>
   ```

4. **Choose how you want to contribute**

   <details>
   <summary>🧩 <b>Option 1 — Add yourself to the Hall of Fame (Quick)</b></summary>

   1. Open the root `README.md`  
   2. Scroll to the **🏆 Hall of Fame** section  
   3. Add a new line like this (customize details as needed):

      ```md
      | [Your Name](https://github.com/your-username) | Style: Clean + API badges | Custom layout |
      ```

   </details>

   <details>
   <summary>🚀 <b>Option 2 — Add your full profile as a template (Detailed)</b></summary>

   1. Inside the `/templates` folder, create a new file named:  
      ```
      username.md
      ```
   2. Paste your GitHub Profile README content there.  
   3. At the end of the file, add:
      ```md
      ---
      Credit: [your-username](https://github.com/your-username)  
      Last Edited: DD/MM/YYYY
      ```
   4. Add your name and file reference inside `_sidebar.md`:  
      ```md
      - [username](/templates/username.md)
      ```

   </details>

5. **Commit your changes with a clear message**
   ```bash
   git add .
   git commit -m "Add profile/template: <your-username>"
   ```

6. **Push your branch**
   ```bash
   git push origin add_<your-username>
   ```

7. **Open a Pull Request (PR)**  
   - Go to your fork on GitHub  
   - Click **Compare & pull request**  
   - Add a clear title and short description of your contribution  

   The PR will be reviewed and merged promptly to feature your awesome profile 🚀

---

## 💡 Tips for a Great Contribution

- Keep intros short (2–3 lines max)  
- Add one or two visuals, not ten  
- Use matching badge styles and consistent colors  
- Always include alt-text for images  
- Keep your markdown neat and readable  

---

## 🧑‍💻 Example Commit Message
```bash
git commit -m "Add profile: sanchivarma"
```

---

## 🎉 That’s It!

Once your PR is merged:
- Your profile appears in the **GeekUp Hall of Fame**
- You officially join the Geek-i-verse 👾
- And your creative README inspires thousands more

---

⭐ **Star this repo** if you enjoyed contributing, and follow for more APIs & open-source fun!  
🪐 Visit [Geekageddon.com](https://geekageddon.com) for developer tools, APIs, and geeky experiments.
