# AutoSalesEbayGermany
[![Kaggle Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue)](https://www.kaggle.com/datasets/shaunoilund/auto-sales-ebay-germany-random-50k-cleaned)

Проект по анализу данных и прогнозированию цен на подержанные автомобили на основе [данных eBay Kleinanzeigen (Германия)](https://www.kaggle.com/datasets/shaunoilund/auto-sales-ebay-germany-random-50k-cleaned).

## 📌 Описание

Анализ данных и построение модели для прогнозирования цен на подержанные автомобили на основе 37 тысяч случайно выбранных объявлений.

## 📋 Данные

### Основные признаки:
- `date_crawled` - дата сбора объявления
- `name` - название автомобиля
- **`price_EUR`** - цена (целевая переменная)
- `vehicle_type` - тип транспортного средства
- `registration_year` - год регистрации
- `power_ps` - мощность (PS)
- `odometer_km` - пробег (км)
- `fuel_type` - тип топлива
- `brand` - марка автомобиля
- `unrepaired_damage` - наличие повреждений

## 🛠️ Технологии

- **Python 3** + Jupyter Notebook
- **Pandas**, **NumPy** - обработка данных
- **Matplotlib**, **Seaborn** - визуализация
- **Scikit-learn** - машинное обучение
- Кастомные классы для автоматизации обработки

## ⚙️ Реализация

### Ключевые этапы:
1. Анализ и ручная обработка данных
2. Написание классов для атоматической обработки:
   - Класс для кодирования категориальных признаков `CustomFunctionTransformer`
   - Класс для автоматической обработки дат `AutoFeatureTransformer`
3. Обучение модели
   - Decision Tree с оптимизацией параметров
   - Кросс-валидация

## 📊 Результаты

**Качество на кросс-валидации:** `RMSLE = 0.434`

---

**Reinigen Sie die Autos!** 🚗💨 *(Чистим данные!)*
