# HACCP Labels Pro

Модуль печати этикеток сроков годности для общепита (HACCP).

**GitHub Pages:** https://smol0901-jpg.github.io/haccp-labels-pro/

## Возможности (Проход 1)

- Сетка продуктов + быстрый поиск
- Выбор условий хранения (холодильник / морозильник)
- Назначение исполнителя
- Ввод срока (дни / часы) + автоматический расчёт дат
- Предпросмотр и «печать» этикетки
- JSON-импорт продуктов и сотрудников
- Журнал операций
- Интеграция с Telegram-коннектором (уведомление после печати)

## Как пользоваться

1. Откройте вкладку **Продукты** → выберите позицию
2. На вкладке **Печать** укажите условия, исполнителя и срок
3. Нажмите **Предпросмотр** или **Печать**
4. В **Админ** можно загрузить свои JSON-справочники

## JSON-формат продуктов

```json
[
  {
    "sku": "001",
    "name": "Кальмар ПФ",
    "type": "semi_finished",
    "shelf_life_days": 3,
    "storage_temp_min": 2,
    "storage_temp_max": 6,
    "default_storage": "refrigerator"
  }
]
```

## Стек

- Чистый HTML + CSS + Vanilla JS
- localStorage для данных
- Telegram-коннектор: `telega-send.netlify.app`

## Neural Architect Premium++

Часть экосистемы Neural Architect.  
Репозиторий: [haccp-labels-pro](https://github.com/smol0901-jpg/haccp-labels-pro)
