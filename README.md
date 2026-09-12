# mle-razrabotka-v-ide
# DataFrameReporter

Класс для быстрого получения сводного отчёта по датафрейму pandas.

## Какую проблему решает

При первичном анализе данных (EDA) приходится каждый раз вручную писать код для
проверки размера датафрейма, поиска дубликатов и пропусков, получения сводной
статистики. `DataFrameReporter` собирает всё это в один читаемый отчёт с гибкой
настройкой форматирования чисел и процентов.

## Установка окружения

1. Склонируйте репозиторий и перейдите в его папку.
2. Создайте виртуальное окружение:
python -m venv venv
3. Активируйте его:
   - Windows (Git Bash): `source venv/Scripts/activate`
   - Windows (PowerShell): `venv\Scripts\Activate.ps1`
   - Linux / macOS: `source venv/bin/activate`
4. Установите зависимости:
pip install -r requirements.txt
## Запуск
python main.py
