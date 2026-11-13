# 🎬 ProstoTV - Web Team Project

> Вебзастосунок для пошуку, фільтрації та підбору фільмів і серіалів на базі React та відкритих даних The Movie Database (TMDB) API.

---

## 🌐 Демонстрація (Live Demo)

- 🔗 **Робочий сайт (GitHub Pages):** [https://prosto-tv-team.github.io/prosto-tv-web-team-project/](https://prosto-tv-team.github.io/prosto-tv-web-team-project/)
- 📋 **Канбан-дошка задач (Projects):** [Дошка завдань команди](https://github.com/orgs/prosto-tv-team/projects/2)
- 📄 **Документ вимог до продукту:** [PRD.md](./PRD.md)

---

## 👥 Склад команди (група КС-32)

| Учасник | Роль у команді | Основна зона відповідальності |
|---|---|---|
| **Черноус Валерій** | **Team Lead / DevOps** | Архітектура репозиторію, налаштування середовища Vite/React, CI/CD, Code Review |
| **Павлова Софія** | **Product Manager / Tech Writer** | Розробка вимог (PRD), проєктування User Stories, ведення таск-трекера |
| **Прохоренко Нікіта** | **UI Engineer** | Підбір підходу до стилізації (SCSS/CSS Modules), компоненти інтерфейсу |
| **Сурмач Володимир** | **Quality Assurance** | Налаштування лінтерів (ESLint, Stylelint), контроль якості коду |

---

## 🛠 Стек технологій

- **Frontend:** [React 19](https://react.dev/) + [Vite](https://vite.dev/)
- **Мова:** JavaScript (ES6+)
- **Стилізація:** CSS / SCSS Modules
- **API:** [The Movie Database (TMDB) API](https://www.themoviedb.org/documentation/api)
- **Контроль якості коду:** ESLint (JS/React) + Stylelint (CSS/SCSS)
- **Автоматизація (CI/CD):** GitHub Actions (автоматичні тести, валідація білду та лінтерів, автодеплой на GitHub Pages)

---

## 🚀 Локальний запуск та розробка

1. **Клонувати репозиторій:**
   ```bash
   git clone https://github.com/prosto-tv-team/prosto-tv-web-team-project.git
   cd prosto-tv-web-team-project
   ```

2. **Встановити залежності:**
   ```bash
   npm install
   ```

3. **Запустити сервер для розробки:**
   ```bash
   npm run dev
   ```

4. **Перевірити лінтери та зібрати проєкт:**
   ```bash
   npm run lint
   npm run build
   ```