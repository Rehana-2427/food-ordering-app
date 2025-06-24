

### 📦 Setting Up a Food Ordering App using React and Parcel

In this project, we are creating a **Food Ordering App** using **React 18** and **Parcel** bundler.

---

### ⚙️ Why not use Create React App (CRA)?

When you initialize a React project using **CRA** (with `npx create-react-app`), it automatically comes with:

* **Webpack** as the bundler
* **Babel** for transpiling code
* Many hidden configurations

While this is convenient, it's not very customizable. If you want to change Webpack settings, you either need to **eject** or use workarounds like `react-app-rewired`.

---

### 🚀 Why use Parcel over Webpack?

| Feature                  | Webpack (CRA)                | Parcel                            |
| ------------------------ | ---------------------------- | --------------------------------- |
| Configuration            | Complex, hidden by default   | Zero-config, easy to customize    |
| Build Speed (small apps) | Slower                       | Faster                            |
| Ideal Use Case           | Large, production-scale apps | Prototyping, small to medium apps |
| Learning Curve           | Steep                        | Simple                            |

So, **Parcel is preferred** here for:

* Faster build times
* Simpler setup
* Better developer experience for small to medium projects

---

### 📦 Installing Parcel

To install Parcel as a dev dependency:

```
npm install -D parcel
```

> `-D` or `--save-dev` means it's only needed during development.

---

### ⚛️ Using React 18 (Not 19)

Use **React version 18** instead of 19, because React 19 is still in beta/RC and might cause compatibility issues with other tools or libraries.

Install React and ReactDOM version 18:

```
npm install react@18
npm install react-dom@18
```

