# Ours — A Love Story 🌸

A beautiful, emotional, single-page birthday gift web app — built with pure HTML, CSS and JavaScript. No frameworks, no installs, no server needed.

---

## 🔐 Default Password
```
idiot
```
Change it to something personal before sharing. See how below.

---

## 🚀 How to Run

**Simplest way — just double-click `index.html`** and it opens in your browser. Done.

**For GitHub Pages (so she can open it from her phone):**
1. Upload all files to a GitHub repo
2. Go to **Settings → Pages → Source: main branch → Save**
3. Share the link: `https://yourusername.github.io/repo-name`

---

## ✏️ User Manual — What to Change

Open `script.js` in any text editor (Notepad, VS Code, anything). Everything you need is inside the `CONFIG` block at the very top.

---

### 1. 🔐 Password
```js
password: "idiot",
```
Change `"idiot"` to whatever you want her to type to unlock the site.
Also update the hint line in `index.html` — search for `gate-hint` and change the text inside it.

---

### 2. 🏷️ Your Name (shown in footer)
```js
yourName: "Someone",
```

---

### 3. ✍️ Letter Sign-off
```js
letterFrom: "Someone",
```

---

### 4. 📸 Photos
Create an `images/` folder, put your photos in it, then update the `photos` array:
```js
photos: [
  { src: "images/photo1.jpg", caption: "our little moment" },
  { src: "images/photo2.jpg", caption: "my favourite rabbit" },
],
```

---

### 5. 💬 Reasons I Love You
Find the `reasons` array and replace or add lines:
```js
reasons: [
  "I love how soft you are, even in a harsh world.",
  // add as many as you want
],
```

---

### 6. 📅 Timeline
```js
timeline: [
  {
    date: "The beginning",
    event: "We met",
    desc: "Your story here.",
    emoji: "✨"
  },
],
```

---

### 7. 💌 Love Letter
Find `letterBody` and replace the text between backticks. Use a blank line between paragraphs:
```js
letterBody: `First paragraph.

Second paragraph.`,
```

---

### 8. 🫙 Memory Jar
```js
memories: [
  { icon: "🌙", text: "Your memory here." },
  { icon: "💛", text: "Another one." },
],
```

---

### 9. 🎨 Colors
Edit the `:root` block at the top of `style.css`:
```css
:root {
  --cream:    #fdf6ee;
  --blush:    #f2d0c8;
  --rose:     #e8a49c;
  --deeprose: #c97b7b;
  --gold:     #c9a96e;
}
```

---

## 📁 File Structure
```
ours/
├── index.html     ← Page structure
├── style.css      ← All styling
├── script.js      ← All content (edit this the most)
├── images/        ← Put your photos here
└── README.md
```

---

Made with ❤️ by Someone — for someone worth every line of code.
