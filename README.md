# Preact на Deno

Пример приложения [Preact](https://preactjs.com/) на [Deno](https://deno.com/).

## Параметры деплоя

Выберите рантайм **Deno**, фреймворк **Preact** и тип приложения **frontend**. Для frontend будет опубликована статическая сборка.

| Параметр | Значение |
| --- | --- |
| Фреймворк | Preact |
| Версия Deno | 2.7.14 |
| Тип приложения | `frontend` |
| Команда сборки | `deno task build` |
| Директория сборки | `dist` |

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
deno install --allow-scripts

# сборка для продакшн
deno task build
```
