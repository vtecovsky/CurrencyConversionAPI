# CurrencyConversionAPI

Данное API взаимодействует с внешним API и предоставляет следующие функционал: производить конвертацию валют, обновлять курсы валют, получать время последнего обноваления курса валют. 
## Содержание

1. [Установка](#установка)
2. [Запуск](#запуск)
3. [Примеры использования API](#примеры-использования)

## Установка

Чтобы установить проект, его нужно склонировать себе на компьютер. 
```bash
git clone https://github.com/vtecovsky/CurrencyConversionAPI
```

## Запуск

Для запуска проекта через Docker необходимо прописать следующую команду в папке проекта:   
```bash
docker-compose up -d
```

Проект будет запущен и доступен по адресу 0.0.0.0:8000 .

## Примеры использования

Всего реализовано 3 эндпоинта:

POST /api/v1/currency/exchange_rates - актуализирует данные в базе данных

GET /api/v1/currency/last_update - возвращает время последнего изменения в базе данных

GET /api/v1/currency/convert - производит конвертацию валют 

Вы можете протестировать API по адресу 0.0.0.0:8000/docs

