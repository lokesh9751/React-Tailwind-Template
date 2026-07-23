# React + Tailwind Template

A clean React + Vite + Tailwind CSS starter template. This template removes the default Vite demo and comes with Tailwind CSS already configured, so you can start building immediately.

## Features

- React + Vite
- Tailwind CSS pre-configured
- Clean project structure
- Default Vite page removed
- Ready to use

---

## Prerequisites

Make sure you have the following installed:

- Node.js (v18 or later recommended)
- Git
- GitHub account

Verify the installation:

```bash
node -v
npm -v
git --version
```

---

## Creating a New Project

### Method 1: Using GitHub (Recommended)

1. Open this repository.
2. Click **Use this template**.
3. Select **Create a new repository**.
4. Enter a repository name.
5. Choose **Public** or **Private**.
6. Click **Create repository**.

---

### Clone the Repository

```bash
git clone https://github.com/<YOUR_USERNAME>/<YOUR_REPOSITORY>.git
```

Example:

```bash
git clone https://github.com/lokesh9751/Background_Changer.git
```

Move into the project folder:

```bash
cd Background_Changer
```

---

## Install Dependencies

```bash
npm install
```

---

## Start the Development Server

```bash
npm run dev
```

By default, Vite runs on:

```
http://localhost:5173
```

---

## Using GitHub CLI

If you have GitHub CLI installed, you can create and clone a new repository directly from this template.

```bash
gh repo create Background_Changer \
  --template lokesh9751/React-Tailwind-Template \
  --public \
  --clone
```

Then run:

```bash
cd Background_Changer
npm install
npm run dev
```

---

## Project Structure

```
src/
├── App.jsx
├── main.jsx
└── index.css

public/

package.json
vite.config.js
```

---

## Why isn't `node_modules` included?

The `node_modules` directory is not pushed to GitHub because:

- It can be recreated using `npm install`.
- It makes the repository unnecessarily large.
- This is the standard practice for Node.js projects.

---

## Available Scripts

Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview production build:

```bash
npm run preview
```

---

## Contributing

Contributions are welcome. Feel free to open an issue or submit a pull request if you'd like to improve this template.

## License

This project is licensed under the MIT License.
