# Vite + React + shadcn/ui Starter Template

A minimal React + Vite template with [shadcn/ui](https://ui.shadcn.com/), built for quick setup and styling.

## 🚀 Getting Started

### 1. Clone the Template and install dependencies

```bash
git https://github.com/goodgithubname/shadcn-vite-template.git
npm install
```

### 2. Remove Git history to start new project
```bash
rm -rf .git
git init
git add .
git commit -m "Initial commit"
```

### 3. Update name in package.json to change project name
// package.json (lines 2–5)
```bash
{
  "name": "shadcn-vite-template",
  "private": true,
  "version": "0.0.0",
  "type": "module",
```
## 🧱 Using shadcn/ui
To add new components:
```bash
npx shadcn-ui@latest add button
```

You can configure base styles in tailwind.config.js and customize components inside:
```components/ui/```

Refer to the official [shadcn/ui docs](https://ui.shadcn.com/docs) to learn more.

## 📄 License

This template is licensed under the [MIT License](./LICENSE).