Student Management System - React (Vite)

Project files:
- index.html
- src/main.jsx
- src/App.jsx
- src/style.css

To run:
1. Open this folder in VS Code.
2. In the terminal, run:
   npm create vite@latest . -- --template react
   (If the project files already exist, choose/confirm the React template only if needed.)
3. Run:
   npm install
4. Run:
   npm run dev

This app renders Header, StudentList, and Footer components.
StudentList uses map() to render five students and a ternary expression
to show PASS when marks >= 40, otherwise FAIL.
