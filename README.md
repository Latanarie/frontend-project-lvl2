### Hexlet tests and linter status:
[![Actions Status](https://github.com/Latanarie/frontend-project-lvl2/workflows/hexlet-check/badge.svg)](https://github.com/Latanarie/frontend-project-lvl2/actions)

[![Test Coverage](https://api.codeclimate.com/v1/badges/47d2292ecd14e1e19199/test_coverage)](https://codeclimate.com/github/Latanarie/frontend-project-lvl2/test_coverage)

[![Node CI](https://github.com/Latanarie/frontend-project-lvl2/actions/workflows/github-actions.yml/badge.svg)](https://github.com/Latanarie/frontend-project-lvl2/actions/workflows/github-actions.yml)
## Difference calculator
Вычислитель отличий — программа с интерфейсом командной строки (CLI), позволяющая формировать разницу между двумя структурами данных или файлами конфигурации и отображать в необходимом для пользователя формате.\
\
Поддерживает следующие форматы данных: yaml, json\
\
Формирует отчет в форматах: stylish (по умолчанию), plain, json

### Руководство по установке
1. ```git@github.com:Latanarie/frontend-project-lvl2.git```
2. ```make install```

### Запуск тестов
```make test```

### Запуск утилиты:
```gendiff <filepath1> <filepath2> -f <format>```

### Вывод справки
```gendiff -h```

### Пример работы утилиты
#### Сравнение плоских файлов (JSON)


[![asciicast](https://asciinema.org/a/XSR0rAcx2l4pGtMlK9hAxiRXn.svg)](https://asciinema.org/a/XSR0rAcx2l4pGtMlK9hAxiRXn)

#### Сравнение плоских файлов (yaml)


[![asciicast](https://asciinema.org/a/PyetPszHjM1bQSXNm4SEMZeVC.svg)](https://asciinema.org/a/PyetPszHjM1bQSXNm4SEMZeVC)

#### Сравнение вложенных структур в формате stylish


[![asciicast](https://asciinema.org/a/BbaISCClV6B5x7e00B8mIxMFP.svg)](https://asciinema.org/a/BbaISCClV6B5x7e00B8mIxMFP)

#### Сравнение вложенных структур в формате plain


[![asciicast](https://asciinema.org/a/547xi8RHeKsyJvgWrvv75ELJH.svg)](https://asciinema.org/a/547xi8RHeKsyJvgWrvv75ELJH)

#### Сравнение вложенных структур в формате json


[![asciicast](https://asciinema.org/a/i9zaQbAUxpXMoFteYCT5Dl16Y.svg)](https://asciinema.org/a/i9zaQbAUxpXMoFteYCT5Dl16Y)