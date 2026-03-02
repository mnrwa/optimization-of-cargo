# Frontend – UI для интеллектуальной маршрутизации

## 📌 Обзор

Клиентское приложение на Next.js.

Отвечает за:

- Визуализацию маршрутов
- Обновления в реальном времени
- Интерфейс для водителя
- Уведомления о рисках

---

## 🏗 Архитектура

Feature-Sliced Design (FSD):

- app – маршрутизация приложения
- shared – переиспользуемые утилиты
- entities – доменные модели
- features – бизнес-функции
- widgets – UI-блоки
- pages – страницы маршрутов

---

## 🛠 Технологии

- Next.js
- TypeScript
- Tailwind CSS
- TanStack Query
- Leaflet
- Socket.io-client

---

## 🚀 Запуск проекта

```bash
pnpm install
pnpm run dev