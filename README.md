## Домашнее задание к лекции 4.«Tests»

### Задача №1 unit-tests
Напишите тесты на любые 3 задания из занятия «Коллекции данных» модуля «Основы языка программирования Python». Используйте своё решение домашнего задания.
При написании тестов не забывайте использовать параметризацию.
Рекомендации по тестам: если у вас в функциях информация выводилась (print), то теперь её лучше возвращать (return), чтобы можно было протестировать.

### Задача №2 Автотест API Яндекса
Проверим правильность работы Яндекс.Диск REST API. Написать тесты, проверяющий создание папки на Диске.
Используя библиотеку requests напишите unit-test на верный ответ и возможные отрицательные тесты на ответы с ошибкой
Пример положительных тестов:
Код ответа соответствует 200.
Результат создания папки - папка появилась в списке файлов.

Токен Яндекс необходимо сохранить в файле config.json
В формате: {"ya_token": ""}

### Задача №3. Дополнительная (не обязательная)
Применив selenium, напишите unit-test для авторизации на Яндексе по url: https://passport.yandex.ru/auth/


#
#
#


код из лекции:
https://replit.com/@addirossi/py76tests

документации библиотек:
selenium https://selenium-python.readthedocs.io/
unittest https://docs.python.org/3/library/unittest.html (en), https://django.fun/ru/docs/python/3.10/library/unittest/ (ru)
pytest https://docs.pytest.org/en/7.2.x/ (en), https://django.fun/ru/docs/pytest/7.2/ (ru)
nose https://nose.readthedocs.io/en/latest/
doctest https://docs.python.org/3/library/doctest.html (en), https://django.fun/ru/docs/python/3.10/library/doctest/ (ru)

туториалы:

unittest:
https://www.youtube.com/watch?v=6tNS--WetLI
https://www.youtube.com/watch?v=sNihKT7YScY

pytest:
https://www.youtube.com/playlist?list=PLB2iiSfKWtvykq9s0plSVI_Du60i0iphU

selenium:
https://www.youtube.com/watch?v=PEitHOkK-74&list=PLzf74dZga1fSViOkTfi15Ok12EfgedmIu&index=2
https://www.youtube.com/playlist?list=PLqGS6O1-DZLp1kgiQNpueIMCHRNzgHa1r
https://www.youtube.com/playlist?list=PLUDwpEzHYYLsuUBvuoYTlN0KsBB5t-BDa
https://www.youtube.com/watch?v=m7SvKhsJrNg
https://www.youtube.com/playlist?list=PLL34mf651faPOf5PE5YjYgTRITzVzzvMz