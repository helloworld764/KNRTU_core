# KNRTU core

Telegram-бот для студентов КНИТУ с расписанием, учебными инструментами и другими сервисами.

## Запуск

Установите зависимости из `requirements.txt` и создайте файл `.env` по примеру `.env.example`. Для работы отдельных функций нужны MongoDB, ключи внешних сервисов и FFmpeg. Укажите необходимые параметры в `.env`, затем запустите `python main.py` из корня проекта.

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
Copy-Item .env.example .env
.\.venv\Scripts\python.exe main.py
```
