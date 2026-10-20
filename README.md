# s-string

Собственная реализация библиотеки `string.h` на C с дополнениями (`sprintf`, функции обработки строк).

## Сборка
```bash
cd src
make            # собрать s21_string.a
make test       # unit-тесты
make gcov_report
```
В `src/scripts/` — скрипты для установки зависимостей, проверки утечек и запуска тестов в Docker.

Полное задание — в [README_RUS.md](README_RUS.md).
