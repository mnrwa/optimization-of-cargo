# Backend – API для интеллектуальной маршрутизации

## 📌 Обзор

Сервис backend на NestJS.  
Отвечает за:

- Управление маршрутами
- Интеграцию с погодой и новостями
- Взаимодействие с AI
- Обновления в реальном времени
- Логику принятия решений

---

## 🏗 Архитектура

Модульная структура:

- route module
- weather module
- news module
- driver module
- ai module
- auth module

---

## 🛠 Технологии

- NestJS
- PostgreSQL + PostGIS
- Prisma ORM
- Axios
- WebSocket (Socket.IO)
- Redis (планируется)
- BullMQ (планируется)

---

## 📂 Структура проекта


src/
├── modules/
├── common/
├── config/
├── prisma/
├── app.module.ts
└── main.ts


---

## 🧠 Интеграция AI

Backend взаимодействует с отдельным AI-сервисом (Python), который выполняет:

- Классификацию новостей
- Прогнозирование уровня риска
- Оценку решений

---

## 🚀 Запуск проекта

```bash
pnpm install
pnpm run start:dev
🗄 База данных

Используется PostgreSQL с расширением PostGIS.

Prisma — ORM для работы с базой.

npx prisma generate
npx prisma migrate dev