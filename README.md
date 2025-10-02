## 🧠 WEEK 1 — DAY 3: Accessibility from the Start

### 🎯 Objectives:

By the end of today, you will:

- Understand **core accessibility (a11y) principles**
- Use semantic **HTML and ARIA roles** correctly
- Make your HTML **navigable by screen readers & keyboard**
- Audit your current project for accessibility

### 👀 Why This Matters

Awwwards-level work isn’t just beautiful — it’s **usable by everyone**. Accessibility is a **non-negotiable skill** in modern web dev, and integrating it from Day 1 makes everything better:

- Better UX for _everyone_
- Cleaner, more semantic code
- You stand out in job interviews

### 🔍 Topics to Focus On

#### ✅ 1. Landmark Roles

These help screen readers understand layout.

Add `role` attributes or HTML5 semantic tags (many roles are implicit):

| Section        | Tag         | Role                         |
| -------------- | ----------- | ---------------------------- |
| Main nav       | `<nav>`     | role="navigation" (optional) |
| Hero / content | `<section>` | role="region"                |
| Footer         | `<footer>`  | role="contentinfo"           |

> **Your task:** Add appropriate roles and `aria-labels` to your nav, hero, etc.

#### ✅ 2. ALT Text for Images

- Make `alt=""` for decorative images
- Be descriptive for meaningful images
- Avoid “image of” or “photo of”

> Your task:
> Update this:

```
<img src="#" alt="abstract 3d image" />
```

To something like:

```
<img src="#" alt="Colorful 3D artwork representing typography concepts" />
```

#### ✅ 3. ARIA Attributes (Use Sparingly!)

Only use ARIA when native elements don’t do the job.

For example:

```
<button aria-label="Toggle grid overlay">[Grid]</button>
```

> Your task:
> Update ambiguous buttons (e.g., grid toggle) with `aria-label` so they make sense out of context.

#### ✅ 4. Keyboard Navigation

Ensure all interactive elements:

- Can be **tabbed through**
- Don’t require a mouse
- Use native elements like `<button>`, `<a>`, `<input>` (avoid `<div role="button">`)

#### ✅ 5. Run an Accessibility Audit

Install the **axe DevTools Chrome extension** or use the built-in **Lighthouse audit** in Chrome DevTools.

> Your task:

- Run an a11y audit on your page
- Fix any basic issues it surfaces (missing labels, contrast, etc.)

### 🛠️ Tasks for Day 3

#### ✏️ In Code:

- [ ] Add proper `role` attributes or confirm semantic tags are enough
- [ ] Improve all `alt` text
- [ ] Add `aria-labels` to non-obvious buttons
- [ ] Confirm all links/buttons are keyboard accessible

#### 🔍 Audit:

- [ ] Run axe or Lighthouse audit
      Note any warnings/errors and fix at least 2

#### 🗒️ Journal Prompt:

> “What surprised you about accessibility? What’s one thing you’ll do differently in future projects because of this?”

#### 📚 Resources:

- WebAIM: Alt Text Decision Tree
- MDN: ARIA Roles
- Deque’s axe DevTools

Once you've completed these tasks and the journal, say **“Day 3 complete”** and we’ll move on to **Day 4: Git + GitHub Mastery.**
