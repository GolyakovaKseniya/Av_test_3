# Av_test_3
# Selenium Test Project

Учебный проект по автоматизации тестирования интернет-магазина.

## Структура

- `pages/` — Page Object классы
- `test_main_page.py` — тесты главной страницы
- `test_product_page.py` — тесты страницы товара
- `conftest.py` — фикстуры

## Запуск тестов

\`\`\`bash
pytest -v --tb=line --language=en -m need_review
\`\`\`

## Требования

- Python 3.8+
- pytest
- selenium
