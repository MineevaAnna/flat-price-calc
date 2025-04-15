# Apartment Discount Calculator / Калькулятор стоимости квартиры

A beginner-friendly Python script to calculate the final price of an apartment after applying a discount.

Простой и понятный Python-скрипт для расчёта итоговой стоимости квартиры с учётом скидки.

---

## What it does / Что делает

- Asks the user:
  - Name
  - City
  - Apartment size (in m²)
  - Price per square meter
  - Desired discount percentage

- Validates the discount:
  - Too small (<5%) → "Too small"
  - Too big (>30%) → "Too large"
  - Acceptable → "Nice choice!"

- Calculates:
  - Full price without discount
  - Discount amount in rubles
  - Final price after discount

---

## How to run / Как запустить

1. Download `apartment_calculator.py`
2. Run the file in any Python environment (Mu, IDLE, VS Code, Terminal)

```bash
python apartment_calculator.py


Example output / Пример вывода
Enter your name: Anna
Enter city: Berlin
Price per square meter: 120000
Apartment size: 45
Discount: 10
→ Final price: 4,860,000 rub.


Введите ваше имя: Анна
Город: Берлин
Цена за 1 м²: 120000
Площадь квартиры: 45
Скидка: 10
→ Финальная стоимость: 4 860 000 руб.


Why I made this / Зачем я это сделала

To practice Python basics, build a real mini-project, and start filling my GitHub portfolio.

Чтобы потренироваться в базовых конструкциях Python, создать свой первый мини-проект
и начать наполнять GitHub реальными, рабочими скриптами.


Feedback / Обратная связь

If you like the idea — feel free to suggest improvements.

Если вам понравилось — буду рада обратной связи!
