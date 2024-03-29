# Инструкция для работы с Markdown

## Выделение текста

### Чтобы выделить текст курсивом необходимо обамить его звездочками (*) или знаками нижнего подчеркивания (_). Например, *вот так* или _вот так_.

### Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**) или двойным знаком нижнего подчеркивания (__). Например, **вот так** или __вот так__.

### Альтернативные способы выделение текста жирным или курсиовом нужны для того, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.

## Списки

### Чтобы добавить ненумерованный список необходимо пункты выделить звездочкой (*) или знаком (+).
Напимер, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

### Чтобы добавить нумерованный список необходимо пункты просто пронумеровать.
Например, вот так:
1. Первый пункт
2. Второй пункт
3. Третий пункт

## Работа с изображениями
### Чтобы вставить изображения в текст, достаточно написать сдедующее:
```
![Привет, это Хаски!](dog.jpg)
```
![Привет, это Хаски!](dog.jpg)

### Чтобы добавить подпись к изображению после ссылки к файлу просто добавьте через пробел текст в кавычках:
```
![Привет, это Хаски!](dog.jpg "Подпись для картинки Хаски")
```
![Привет, это Хаски!](dog.jpg "Подпись для картинки Хаски")

### Чтобы изменить размер картинки и добавить рамку вокруг нужно использовать следующий способ:
```
<img src="dog.jpg" width="300" height="170" border="5px solid">
```
<img src="dog.jpg" width="300" height="170" border="5px solid">

## Ссылки
```
[Текст ссылки](https://www.example.com)
```
**[Текст ссылки](https://www.example.com)**

## Цитаты
```
> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования
```
> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования

## Чек-листы
```
- [x] Задача 1
- [ ] Задача 2
- [ ] Задача 3
```

## Таблицы
### Первый способ
| Заголовок 1 | Заголовок 2 |
| ----------- | ----------- |
| Ячейка 1    | Ячейка 2   |
| Ячейка 3    | Ячейка 4   |

### Второй способ
<table>
    <tr>
        <th>Заголовок 1</th>
        <th>Заголовок 2</th>
    </tr>
    <tr>
        <td>Ячейка 1.1</td>
        <td>Ячейка 2.1</td>
    </tr>
    <tr>
        <td>Ячейка 1.2</td>
        <td>Ячейка 2.2</td>
    </tr>
</table>

Создали строчку с локального компьютера

Создали строчку с другого компьютера
