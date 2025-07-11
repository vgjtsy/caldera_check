# Caldera Eligibility Checker

Проверка адресов на аирдроп токенов Caldera

## Требования
- Python
- requests (см. requirements.txt)

## Быстрый старт

1. Установите Python
2. Установите зависимости:
   
   ```bash
   pip3 install -r requirements.txt
   ```
3. В файл `evm.txt` поместите по одному EVM-адресу на строку.
4. (Опционально) В файл `proxies.txt` поместите прокси (по одному на строку) в формате:
   ```
   http://user:pass@ip:port
   ```
   или
   ```
   user:pass@ip:port
   ```
5. (Опционально) Для отключения прокси измените `USE_PROXIES = False` в начале файла `main.py`
6. Запустите скрипт:
   
   ```bash
   python3 main.py
   ```
7. Результаты появятся в консоли и в файле `result.txt`.



