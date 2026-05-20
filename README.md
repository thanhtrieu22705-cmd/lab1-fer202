# Lab 1 – JSX and ES6 with React + Webpack + Babel

## Cấu trúc thư mục

```
react-demo/
├── src/
│   ├── components/
│   │   ├── App.js          ← Component chính
│   │   ├── HelloWorld.js   ← Bài JSX
│   │   └── Person.js       ← Bài ES6 class
│   ├── styles/
│   │   └── App.css
│   ├── index.js            ← Entry point
│   └── index.html          ← HTML template
├── .babelrc                ← Cấu hình Babel
├── webpack.config.js       ← Cấu hình Webpack
├── package.json
└── README.md
```

## Cách chạy

### Bước 1 – Mở VSCode / Kiro → mở thư mục `react-demo`

### Bước 2 – Mở Terminal (`Ctrl + `` `)

### Bước 3 – Cài dependencies
```bash
npm install
```

### Bước 4 – Chạy dev server
```bash
npm start
```
Trình duyệt tự mở tại `http://localhost:8080` — trang hiển thị **My React App!**

### Build production (nếu cần)
```bash
npm run build
```

---

## Lưu ý quan trọng (lỗi trong lab gốc đã được sửa)

| Vấn đề | Lab viết (sai) | File này (đúng) |
|---|---|---|
| React 18 render | `ReactDOM.render(...)` | `createRoot(...).render(...)` |
| Import render | `import ReactDOM from "react-dom"` | `import { createRoot } from "react-dom/client"` |

---

*Lab 1 – PRF192 / React Fundamentals*
