# My Todo App (React + TypeScript + Vite)

This is a simple Todo List app built with React, TypeScript, and Vite.

## Features

- Add new todos
- Mark todos as completed (click to toggle)
- All logic written in TypeScript

---

## Getting Started

### 1. Clone the repository

```sh
git clone <your-repo-url>
cd my-todo-app
```

### 2. Install dependencies

If you have **Node.js installed locally**:

```sh
npm install
```

#### Using Node.js in Docker

If Node.js is **not installed on your PC** but you have Docker, you can run all commands inside a Node Docker container:

```sh
docker run --rm -it -v %cd%:/app -w /app node:20 npm install
```

### 3. Start the development server

**Locally:**
```sh
npm run dev
```

**With Docker:**
```sh
docker run --rm -it -v %cd%:/app -w /app -p 5173:5173 node:20 npm run dev
```

- Open your browser and go to [http://localhost:5173](http://localhost:5173)

---

## Project Structure

```
my-todo-app/
├── src/
│   ├── App.tsx         # Main app component
│   ├── AddTodo.tsx     # Input for adding todos
│   ├── TodoList.tsx    # List and toggle todos
│   ├── main.tsx        # Entry point
│   ├── index.css       # Global styles
│   └── App.css         # App styles
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

---

## Notes

- You can edit the code in the `src/` folder and the app will reload automatically.
- If you use Docker, all commands should be run from the project root.

---

## License
