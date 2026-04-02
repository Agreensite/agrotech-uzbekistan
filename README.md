# 🌿 AgroTech Uzbekistan: AI & Satellite Monitoring Platform

Инновационная веб-платформа для фермеров Узбекистана, объединяющая спутниковые данные NASA/ESA и искусственный интеллект для оптимизации земледелия.

## 🚀 Основные функции
* **Интерактивная карта:** Выделение границ полей (Leaflet.js) и привязка к махаллам (Каттакурганский р-н и др.).
* **Спутниковый мониторинг:** Автоматическое получение индексов NDVI и влажности почвы через NASA POWER API.
* **ИИ-Агроном:** Прогноз урожайности в центнерах с гектара и персональные рекомендации по удобрениям.
* **Экономический модуль:** Расчет рентабельности (ROI) и затрат на гектар.
* **Telegram-бот:** Ежедневные отчеты и экстренные уведомления о заморозках или засухе.

## 🛠 Технологический стек
- **Frontend:** HTML5, CSS3, JavaScript (Leaflet.js, Leaflet.draw)
- **Backend:** Python 3.10+, FastAPI
- **Database:** PostgreSQL + PostGIS (геопространственные данные)
- **AI/ML:** Shapely (геометрия), Scikit-learn (прогнозирование)
- **Bot:** Aiogram 2.x + APScheduler

## 📦 Установка и запуск

1. Клонируйте репозиторий:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/agrotech-uzbekistan.git](https://github.com/YOUR_USERNAME/agrotech-uzbekistan.git)
