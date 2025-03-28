# 🕳️ sass-hole

A lightweight, modular SCSS utility library built to plug into your workflow without dictating it.

---

## 📦 Install

```bash
npm install sass-hole
```

---

## 🔌 Import

### SCSS (Recommended)

```scss
@use "sass-hole" as *; // or use an alias: @use "sass-hole" as sh;
```

> This loads all variables, mixins, and utilities. Use an alias to avoid polluting global scope.

### JS/TS (for bundlers that support style imports)

```js
import "sass-hole";
```

> This will work if your bundler (e.g., Vite, Webpack) supports importing SCSS or CSS files directly.

---

## 📚 Class Reference

All available utility classes are documented in [`CLASSES.md`](./CLASSES.md).

---

## 🧱 Features

- ✨ SCSS-first, zero JavaScript
- 💡 Modular structure (`buttons`, `forms`, `grid`, `typography`, etc.)
- 🧩 Customizable via SCSS variables and mixins
- 🎯 Easy to extend and override
- 🔥 Built-in reset and theming potential

---

## 🗂️ Folder Structure

```
sass-hole/
├── scss/
│   ├── _reset.scss
│   ├── _variables.scss
│   ├── index.scss
│   ├── components/
│   ├── layout/
│   └── utilities/
└── package.json
```

---

## 🛠️ Build (Optional)

If you want to generate a compiled CSS version:

```bash
sass src/index.scss dist/styles.css
```

Or add it to `package.json` scripts:

```json
 "scripts": {
    "build": "sass src/index.scss dist/styles.css",
  },
```

---

## 🤝 Contributing

Pull requests and feature ideas are welcome! Please:

1. Fork the repo
2. Create a new branch
3. Make changes with clear commits
4. Open a PR

---

## 🪪 License

MIT © Jordan Gerber

---

## 📛 Badges (Optional)

You can add these via [shields.io](https://shields.io):

```md
![npm](https://img.shields.io/npm/v/sass-hole)
![license](https://img.shields.io/npm/l/sass-hole)
![downloads](https://img.shields.io/npm/dt/sass-hole)
```

---

> sass-hole: for when your styles need a light touch... and a dorky name.
