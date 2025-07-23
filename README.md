Проект 5 спринта UI-тестирование в Stellar Burgers
conftest.py - фикстуры
driver - настройки webdriver
data.py - Данные пользователя и cписок URL для перехода на необходимые страницы
class Data - Данные пользователя для корректных логинов
class UrlList - Список URL для перехода на нужные страницы
Вспомогательные функции - helper_functions.py

Тесты
1. Проверки регистрации пользователя: файл test_registration.py
test_registration_successful - Успешная регистрация
test_registration_without_name - Попытка регистрации без имени
test_registration_without_email - Попытка регистрации без имейла
test_registration_without_password - Попытка регистрации без пароля
test_registration_password_less_6_synbols - Попытка регистрации с паролем меньше 6 символов. Проверяем граничные значения 1 и 5
2. Проверки входа пользователя: файл test_login.py
test_login_from_main_page - Вход по кнопке «Войти в аккаунт» на главной
test_login_from_account - Вход через кнопку «Личный кабинет»
test_login_after_registration - Вход через кнопку в форме регистрации
test_login_from_recovery_pass - Вход через кнопку в форме восстановления пароля
3. Проверка перехода в личный кабинет: файл test_go_to_account_from_main.py
test_go_to_account_from_main - Переход по клику на «Личный кабинет» с главной страницы
4. Проверка перехода из личного кабинета в конструктор: файл test_go_to_constructor_from_account.py
test_go_to_constructor_from_account - Переход по клику на «Конструктор» и на логотип Stellar Burgers
5. Проверка выхода из аккаунта: файл test_logout.py
test_logout - Выход по кнопке «Выйти» в личном кабинете
6. Взаимодействие с конструктором бургеров: файл test_constructor.py
test_go_to_sauses - Переход во вкладку "Соусы"
test_go_to_filling - Переход во вкладку "Начинки"
test_go_to_buns - Переход во вкладку "Булки" через "Начинки"# Sprin_5 n

