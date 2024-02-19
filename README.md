# ИНТЕНСИВ (3 занятия).

# ДЗ к занятию 1.
# Задание 1.
# ИНТЕГРАЦИОННЫЙ ТЕСТ:
# Тест 1: зайти на Главную, написать письмо, отправить письмо, проверить, что оно появилось в Отправленных.
# Тест 2: зайти на Главную, прочитать какое-нибудь полученное письмо, удалить его, проверить, что оно отображается в Удаленных.
# ДЫМОВОЙ ТЕСТ:
# Тест 1: зайти на главную, создать письмо, отправить себе на временную почту, проверить, что оно пришло.
# Тест 2: отправить со своей временной почты письмо, проверить, что оно получено, отображается во Входящих, открывается.
# РЕ-ТЕСТ:
# Тест 1: удалить какое-либо письмо из входящих, проверить, что оно попадает в Удаленные, и что его нет в Отправленных.
# НЕФУНКЦИОНАЛЬНЫЙ ТЕСТ:
# Тест 1: UI, например. Открыть почту, проверить глазами и через DevTools/Inspector элементы интерфейса, что нет скрытых, что элементы не наезжают друг на друга.
# Тест 2: Кроссбраузерное, проверить работу почту в Chrome и Yandex, в мобильном Chrome

# Задание 2.
# - Добавлен раздел Спам - да, нужно провести регресс, т.к. это новая фича, новый модуль, могла нарушиться работа уже имеющихся модулей и их взаимодействие.
# - Удаленные переименован в Корзина - спорно. Если просто переименовали элемент интерфейса - то регресс не нужен. А если было переименование элементов в коде - то могли переименовать не везде, и, например, удаление письма могло сломаться.
# - На «Странице входа» устранен ранее обнаруженный дефект - спорно, но скорее нет. Нужен однозначно сначала ретест. Т.к. изменение на Странице входа - оно скорее всего не заденет работу основных модулей.

# Задание 3.
# На новом билде надо провести в первую очередь Smoke, чтобы проверить, что основная функциональность работает.

# Задание 4.
# Перестала работать кнопка "Удалить письмо" после добавления раздела "Черновик" - это обнаружится при регрессе.

