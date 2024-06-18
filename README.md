# -- > Telegram - бот < --

### Общее описание
Бот для проверки статуса домашнего задания, с последующим уведомлением пользователя в Telegram. 
Производится опрос API сервиса учебного заведения с заданным интервалом времени, затем проверяется 
изменение статуса, если статус изменился, отправляется уведомление в telegram.

### Подготовка проекта к запуску под Linux
  * Клонируем репозиторий на пк
    ```
    git clone git@github.com:PetrovKRS/telegram_bot_homework.git
    ```
  * переходим в рабочую папку склонированного проекта
  * разворачиваем виртуальное окружение
    ```
    python3 -m venv venv
    ```
    ```
    source venv/bin/activate
    ```
  * устанавливаем зависимости из файла requirements.txt
    ```
    pip install --upgrade pip
    ```
    ```
    pip install -r requirements.txt
    ```
  * запускаем бота
    ```
    python3 homework.py
    ```

Стек технологий: |*| python-telegram-bot 13.7 |*| python-dotenv 0.19.0 |*| flake8 |*|
