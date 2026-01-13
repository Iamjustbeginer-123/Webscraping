# Задача: 
- Спарсить данные с сайта строительного магазина, а именно список товаров и цену оптовую и розничную на каждый товар
- Создать excel таблицу в формате xlsx, где будут храниться данные по каждому товару

# Библиотеки: 
```python
import requests
from bs4 import BeautifulSoup
from openpyxl import load_workbook
```

# Исходный сайт для парсинга: 
[Строительный магазин](https://doka-baza.ru/catalog/?PAGEN_1=9)

