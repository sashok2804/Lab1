# README

## Описание проекта

Данный проект написан на языке Go. Программа выполняется через команду `go run`, с возможностью передачи параметра через флаг `-t`. Параметр задает выполнение определенной логики программы и принимает значения от 1 до 6.

## Требования

- Go версии 1.16 и выше
- Операционная система: Windows/Linux/macOS

## Запуск программы

Для запуска программы используйте команду:

```bash
go run .\Lab<num>\Go\main.go -t <value>
```

где `<value>` — это значение от 1 до 6, которое определяет поведение программы.

### Пример

```bash
go run .\Lab1\Go\main.go -t 6
```

## Возможные значения параметра

Параметр `-t` принимает целые значения от 1 до 6. Каждое значение соответствует определенному заданию лабалоторной работы:

## Ошибки

- Если параметр `-t` не указан, программа выполнит 1 задание.
- Если передано значение вне диапазона от 1 до 6, программа выполнит 1 задание.