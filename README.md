# Synergy GK - сайт на Tilda

Магазин воротарських рукавиць. Перегляд сайту: https://timoshes229-beep.github.io/synergy-gk/

## Блоки для Tilda (T123)
Кожен файл: інструкція -> код -> пояснення, що змінювати. Порядок на сторінці - нижче таблиці.

| № | Файл | Блок | Якір |
|---|------|------|------|
| 01 | `tilda-blocks/01-hero-T123.txt` | Перший екран | - |
| 02 | `tilda-blocks/02-why-T123.txt` | Чому Synergy | `why` |
| 03 | `tilda-blocks/03-catalog-T123.txt` | Каталог + кнопка "У кошик" | `catalog` |
| 04 | `tilda-blocks/04-cut-T123.txt` | Типи крою | `cut` |
| 05 | `tilda-blocks/05-size-T123.txt` | Калькулятор розміру | `size` |
| 06 | `tilda-blocks/06-story-T123.txt` | Засновник | `about` |
| 07 | `tilda-blocks/07-game-T123.txt` | В грі: галерея і відгуки | `game` |
| 08 | `tilda-blocks/08-care-T123.txt` | Догляд | `care` |
| 09 | `tilda-blocks/09-delivery-T123.txt` | Доставка, оплата, обмін | `delivery` |
| 10 | `tilda-blocks/10-faq-T123.txt` | FAQ | `faq` |
| 11 | `tilda-blocks/11-final-T123.txt` | Фінальний екран + підвал | `contacts` |
| 12 | `tilda-blocks/12-cart-T123.txt` | Кошик і замовлення (Telegram / Instagram) | - |
| 13 | `tilda-blocks/13-save-T123.txt` | Сейв при прокрутці (м'яч летить - рукавиця ловить) | - |
| 14 | `tilda-blocks/14-compare-T123.txt` | Порівняння моделей | `compare` |
| 15 | `tilda-blocks/15-turn-T123.txt` | 3D-огляд (поверни рукавицю) | `turn` |
| 16 | `tilda-blocks/16-catch-T123.txt` | Міні-гра "Зловуй м'яч" з промокодом | `play` |
| 17 | `tilda-blocks/17-cursor-T123.txt` | Курсор-рукавиця (ПК) | - |

### Порядок блоків на сторінці
01 -> 02 -> 13 -> 15 -> 03 -> 14 -> 04 -> 05 -> 06 -> 16 -> 07 -> 08 -> 09 -> 10 -> 11 -> 12 -> 17

## Для розробки
`_src/blocks/*.blk` - вихідники блоків 02-12, `python3 _src/build.py` збирає TXT-файли і `index.html`.
