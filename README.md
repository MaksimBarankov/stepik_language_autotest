# stepik_language_autotest

# Привет, сокурсник! 👋

## Напомню критерии проверки:

1. **Запуск теста**
   - Тест в репозитории можно запустить командой:
     ```bash
     pytest --language=es
     ```
   - Тест успешно проходит.

2. **Проверка работоспособности кода для разных языков**
   - Добавьте в файл с тестом команду:
     ```python
     time.sleep(30)
     ```
     сразу после открытия ссылки.
   - Запустите тест с параметром `--language=fr` и визуально проверьте, что фраза на кнопке добавления в корзину выглядит так:
     ```
     Ajouter au panier
     ```

3. **Фикстура `browser`**
   - Браузер должен объявляться в фикстуре `browser` и передаваться в тест как параметр.

4. **Проверка кнопки добавления в корзину**
   - В тесте проверяется наличие кнопки добавления в корзину.
   - Селектор кнопки является уникальным для проверяемой страницы.
   - Есть `assert`.

5. **Название тестового метода**
   - Название тестового метода внутри файла `test_items.py` соответствует задаче.
   - Название `test_something` не удовлетворяет требованиям.
