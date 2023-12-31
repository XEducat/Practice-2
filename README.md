# Практика_Linq

## Огляд

Ця консольна програма на C# демонструє використання LINQ для обробки футбольних матчів. Вона включає в себе різні LINQ-запити та використовує Newtonsoft.Json для роботи з JSON.

## Основні можливості

1. **Десеріалізація з JSON**: Програма зчитує дані матчів з JSON-файлу та десеріалізує їх у список `FootballGame`.

2. **LINQ-запити**:

   | Запит | Опис |
   |-------|------|
   | **Запит 1** | Всі матчі в Україні в 2012 р. |
   | **Запит 2** | Товариські матчі збірної Італії з 2020 р. |
   | **Запит 3** | Домашні матчі збірної Франції в 2021 р., які закінчилися внічию. |
   | **Запит 4** | Матчі збірної Німеччини з 2018 по 2020 р. (поразки на виїзді). |
   | **Запит 5** | Кваліфікаційні матчі UEFA Euro в Києві чи Харкові з перемогою української збірної. |
   | **Запит 6** | Останні 8 матчів Чемпіонату світу з футболу в зворотній послідовності. |
   | **Запит 7** | Перший матч 2023 року, де збірна України виграла. |
   | **Запит 8** | Трансформація матчів Євро-2012 в Україні. |
   | **Запит 9** | Трансформація матчів UEFA Nations League в 2023 р. |
   | **Запит 10** | Матчі Gold Cup 5-10 у липні 2023 р. |

## Використання

1. **Клонування репозиторію**:
   ```bash
   git clone https://github.com/your-username/Practice_Linq.git
   ```
3. **Відкриття у Visual Studio**: Відкрийте `Practice_Linq.sln` у Visual Studio.
4. **Запуск програми**: Зберіть та запустіть програму у Visual Studio.

## Залежності

- [Newtonsoft.Json](https://www.newtonsoft.com/json): Бібліотека для роботи з JSON в .NET.

## Ліцензія

MIT License - [LICENSE](LICENSE)
