# 📚 sass-hole — Class Reference

This is a reference list of all utility classes and component classes available in the `sass-hole` SCSS library. Organized by category for quick lookup.

---

## 🧼 Reset

| Class         | Description                   |
| ------------- | ----------------------------- |
| `.reset`      | Applies global element reset  |
| `.box-border` | Sets `box-sizing: border-box` |

---

## 📐 Layout & Flex

| Class                           | Description               |
| ------------------------------- | ------------------------- |
| `.flex`                         | `display: flex`           |
| `.flex-col`                     | `flex-direction: column`  |
| `.justify-center`               | `justify-content: center` |
| `.items-center`                 | `align-items: center`     |
| `.gap-sm` / `gap-md` / `gap-lg` | Predefined spacing        |

---

## 🔳 Grid

| Class          | Description                             |
| -------------- | --------------------------------------- |
| `.grid`        | `display: grid`                         |
| `.grid-cols-2` | `grid-template-columns: repeat(2, 1fr)` |
| `.grid-gap-sm` | Small gap between grid items            |

---

## ✍️ Typography

| Class          | Description         |
| -------------- | ------------------- |
| `.text-sm`     | Small font size     |
| `.text-lg`     | Large font size     |
| `.text-center` | Center-aligned text |
| `.font-bold`   | Bold text           |
| `.uppercase`   | Uppercase text      |

---

## 🎛️ Buttons

| Class          | Description       |
| -------------- | ----------------- |
| `.btn`         | Base button style |
| `.btn-primary` | Primary style     |
| `.btn-outline` | Outline variant   |
| `.btn-sm`      | Small button      |

---

## 📝 Forms

| Class         | Description                 |
| ------------- | --------------------------- |
| `.input`      | Standard input styling      |
| `.textarea`   | Resizable textarea          |
| `.select`     | Styled dropdown select      |
| `.form-group` | Container for input + label |

---

## 🎨 Colors (example)

| Class           | Description              |
| --------------- | ------------------------ |
| `.bg-primary`   | Primary background color |
| `.text-danger`  | Red/danger text color    |
| `.border-muted` | Subtle border color      |

---

## 🚧 Custom Utilities (WIP)

| Class        | Description             |
| ------------ | ----------------------- |
| `.sr-only`   | Screen reader only text |
| `.no-select` | Disables text selection |

---

## 💬 Notes

- All classes are **opt-in** — no global styles are applied unless you import them.
- You can customize via SCSS variables, maps, or mixins.
- Class generation may change as the library evolves.
