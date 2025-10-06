# 🎯 Day 5: Pixel-Perfect Clone Build

## ✅ Goals

- Recreate part of a high-quality site (**Obys Typography Principles**, in your case)
- Focus on **structure**, **spacing**, and **typography**
- Style your layout to match the real site — **visually and rhythmically**
- Maintain accessibility and clean HTML
- Track changes in Git/GitHub

---

## 🧱 What You’re Building

You already have:

- Semantic HTML ✅
- Atomic comments ✅
- Accessibility ✅

Now you’ll **style the layout** using CSS to closely match a section of the Obys site:

- Navigation bar
- Hero block (image, headline, pricing, meta, video teaser)

---

## 🛠️ Tasks

### 🔹 1. Set Up CSS Baseline

In `style.css`:

- Add a **CSS reset** (e.g. `* { margin: 0; padding: 0; box-sizing: border-box; }`)
- Set base fonts and colors
- Define spacing variables if you want (custom properties)

---

### 🔹 2. Style Your Layout

Use **Flexbox** or **Grid** to lay out the hero section:

- Align left/right columns
- Make spacing match the reference site
- Use `clamp()` or media queries for responsive behavior

---

### 🔹 3. Style Typography

- Use correct font sizes, weights, and spacing
- Apply consistent hierarchy:
  - `<h1>`: clamp-based
  - `<p>`: readable, good line-height
- Consider using Google Fonts if needed

---

### 🔹 4. Make It Accessible

- Maintain your existing `aria-label`s, alt text, etc.
- Ensure text contrast is good
- Make sure buttons and links are keyboard accessible

---

### 🔹 5. Commit Your Progress

Use clear messages like:

```bash
git add .
git commit -m "style: layout nav and hero section"
git push
```

---

## 🧠 Bonus Challenges (if time allows)

- Add `hover` styles to buttons/links
- Add a custom cursor or motion-ready class (to prepare for Week 2)
- Use `:focus-visible` for keyboard users

---

## 📌 Your Deliverables

By the end of Day 5:

- A styled `index.html` and `style.css` matching your chosen section of Obys site
- A committed + pushed GitHub repo with all changes
- Pixel-perfect or close visual alignment
- Accessibility still intact

---

## 📚 Resources

- [clamp() visual playground](https://clamp.font-size.app/)
- [CSS Grid Cheat Sheet](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Typography in UI](https://uxdesign.cc/typography-in-user-interface-design-a-beginners-guide-205f0a4c5b9b)
- [Google Fonts](https://fonts.google.com/)

---

## ✅ Next Step

Start styling your layout and push changes as you go. When you're ready, say **“Day 5 complete”**, and I’ll:

- Review your repo and CSS
- Close out Week 1
- Set you up for **Week 2: Responsive CSS + Editorial Grid Layouts**

Let me know if you want:

- Help scaffolding your CSS
- Font or spacing advice based on Obys
- Debugging help as you build

You're ready — let's go build something beautiful.
