# 🎞️ React Animatable (Story book)

**Tiny (~1kB) animation hooks for React**, powered by the [Web Animations API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API). Build performant, smooth, and customizable animations for modern React apps — with zero dependencies.

![demo](./demo.gif)

---

## 🚀 Features

- 🔁 Powerful hooks for declarative animations
- ⚡ Based on native **Web Animations API**
- 🎯 Works with **scroll-driven animations**
- 📦 Tree-shakeable & lightweight (~1kB)
- 🎨 Compatible with UI frameworks: Material UI, Chakra UI, Mantine, Ant Design, etc.
- 🧪 Tested with Vitest
- 📚 Visual stories via Storybook
- 📘 Auto-generated TypeDocs

---

## 📦 Installation

```bash
npm install react-animatable
# or
yarn add react-animatable
```

---

## 🧩 Example Usage

```tsx
import { useAnimation } from "react-animatable";

function MyComponent() {
  const ref = useAnimation({
    keyframes: [{ opacity: 0 }, { opacity: 1 }],
    duration: 500,
  });

  return <div ref={ref}>Hello, world!</div>;
}
```

More examples in the [`/stories`](./stories) directory.

---

## 🧪 Run Locally

```bash
# Install dependencies
npm install

# Run storybook (for visual demos)
npm run storybook

# Run tests
npm run test

# Build package
npm run build
```

---

## 📁 Project Structure

```
storybook/
├── .storybook          # Storybook config
├── docs                # API Docs and interface references
├── images              # Demo GIFs
├── src                 # Library source code
│   ├── react/hooks     # Animation hooks (core logic)
│   ├── core            # WAAPI & utility helpers
│   └── types           # Internal type definitions
├── stories             # Storybook demos with libraries
└── ...
```

---

## 📘 Documentation

- 📄 [API Reference](./docs/API.md)
- 🧩 [Interfaces](./docs/interfaces)
- 📕 [TypeDocs](./lib/index.d.ts)

---

## 🤝 Contributing

1. Fork this repo
2. Create a new branch (`git checkout -b feat/my-feature`)
3. Commit your changes (`git commit -am 'Add feature'`)
4. Push to your branch (`git push origin feat/my-feature`)
5. Create a Pull Request ✅

---

## 📄 License

MIT © [inokawa](https://github.com/inokawa)

---

## 🌐 Links

- 🧠 Demo Storybook: _[Coming Soon]_
- 📦 NPM: [`react-animatable`](https://www.npmjs.com/package/react-animatable)
- 🐙 GitHub: [Krishprajapati15/Admin-Panel](https://github.com/Krishprajapati15/Admin-Panel)

---

> Made with ❤️ by [Krish Prajapati](https://github.com/Krishprajapati15)
