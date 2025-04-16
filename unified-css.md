Yessss, now we’re talking 👑

If you go with the **scoped variant approach** (e.g., `.float-frame.figure-style`, `.float-frame.seealso-style`), you’ll have **granular control over size, float behavior, margins, font, everything**, per box type. It’s like making your own wiki design system. Here's how to do it like a pro:

---

### ✅ Unified `<style>` Block Example (Copy-Paste-Ready)

```html
<style>
/* 🔳 Default float frame base (shared traits) */
.float-frame {
    border: 1px solid #ccc;
    background-color: #f9f9f9;
    position: relative;
    padding: 6px 10px;
    margin: 15px;
    font-family: sans-serif;
}

/* 🖼️ For image/code figures */
.float-frame.figure-style {
    float: right;
    width: 35%;
    font-size: 12px;
    text-align: center;
}

/* 📎 For seealso callouts */
.float-frame.seealso-style {
    float: right;
    width: 190px;
    max-width: 190px;
    min-width: 100px;
    font-size: 13px;
    white-space: nowrap;
    text-align: left;
}

/* 📱 Responsive fallback */
@media (max-width: 768px) {
    .float-frame {
        float: none !important;
        display: block;
        width: 95vw !important;
        max-width: 95vw !important;
        margin: 10px auto;
        white-space: normal;
    }
}

/* 🔍 Magnify icon overlay for figures */
.image-bubble.layered-icon {
    position: absolute;
    bottom: 8px;
    right: 8px;
    width: 14px;
    height: 12px;
    background: none;
    padding: 0;
    cursor: pointer;
    z-index: 5;
}

.large-icon {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: #ddd;
    border: 1px solid #888;
    border-radius: 2px;
}

.small-icon {
    position: absolute;
    width: 50%;
    height: 50%;
    background-color: #aaa;
    border: 1px solid #666;
    border-radius: 2px;
    bottom: -1px;
    left: -1px;
}

.image-bubble.layered-icon:hover .large-icon {
    background-color: #007BFF;
    border-color: #0056b3;
}

.image-bubble.layered-icon:hover .small-icon {
    background-color: white;
    border-color: #007BFF;
}
</style>
```

---

### 🧠 How to Use

#### For a **figure/code** cell (like a chart):

```html
<div class="float-frame figure-style">
  <!-- Put your code block, caption, or image here -->
</div>
```

#### For a **seealso** box:

```html
<div class="float-frame seealso-style">
```{seealso}
[Click me](#)
```
</div>
```

---

### 🎛️ Customization Power

- **Want a wider seealso?** → change `width: 190px;` in `.seealso-style`
- **Want centered figures?** → add a `.figure-center-style` and do `float: none; margin: auto;`
- **Want a dark mode version?** → create `.float-frame.dark-style` and override `background-color` etc.

---

Wanna go full design-system and make a `<div class="ukubox">` set of classes next? I got you.
