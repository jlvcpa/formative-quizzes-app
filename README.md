## 📄 README.md

```markdown
# 🎓 Interactive Learning Quiz

An accessible, responsive, and motivational quiz platform designed to empower learners through interactive questions, personalized progress tracking, and dynamic inspiration.

---

## 🌟 Features

- 🔐 **User Login**  
  Simple login system using localStorage to personalize and persist progress.

- 📊 **Performance Tracking**  
  Displays percentage score and correct/total count. Progress is saved per user.

- 🔍 **Topic Filtering**  
  Dynamically generated dropdown to filter questions by topic.

- 🔢 **Sequential & 🎲 Random View Modes**  
  Toggle between ordered and shuffled question sequences.

- 📝 **Mark for Review**  
  Users can flag questions for later review. Sidebar updates dynamically.

- 📱 **Responsive Design**  
  Optimized for desktop and mobile. Review sidebar moves below quiz panel on small screens.

- 🌐 **Inspirational Quotes**  
  Fetched from [Quotable API](https://api.quotable.io) and updated with each question. Includes fade-in animation and caching.

- 🖨️ **Printable Summary**  
  Generates a printable performance report with review items.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/interactive-learning-quiz.git
cd interactive-learning-quiz
```

### 2. Open the HTML File

Simply open `index.html` in your browser. No server setup required.

---

## 🛠️ Customization

- **Add Questions**  
  Modify the `questions` array in the `<script>` section of `index.html`.

- **Change Topics**  
  Topics are auto-detected from each question’s `topic` field.

- **Style Tweaks**  
  Customize layout and colors via the embedded `<style>` block.

---

## 📦 Deployment

You can host this on GitHub Pages:

1. Push your repository to GitHub.
2. Go to **Settings > Pages**.
3. Select the branch and root folder.
4. Your site will be live at `https://your-username.github.io/interactive-learning-quiz/`.

---

## 🤝 Credits

- Quotes powered by [Quotable API](https://api.quotable.io)
- Developed by Joselito ✨

---

## 📄 License

This project is open-source and free to use under the MIT License.
