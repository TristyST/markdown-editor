# Markdown Editor

Простий онлайн-редактор Markdown: React (frontend) + Node.js/Express + MongoDB (backend).

## Вимоги
- Node.js 18+
- MongoDB (локально або хмарний кластер)
- npm

## Запуск локально

### 1) Бекенд
```bash
cd backend
npm install
# за потреби вкажіть MONGO_URI і JWT_SECRET
export MONGO_URI="mongodb://localhost:27017/markdown_editor"
export JWT_SECRET="dev_secret"
npm run dev
