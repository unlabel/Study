# Поля и списки

Наверняка в интернете тебе часто встречались различные списки, они скорее всего уже были стилизованы, но основная их задача визуализировать перечисление каких-либо сущностей. В этой задаче твоя задача написать HTML-код где с помощью тегов `ul`, `li`, `select` и `option` будут формироваться списки.

## Release 0. Изучение тегов

Поэкспериментируй с каждым тегом, чтобы понимать, как работает каждый.
Прочитай дополнительные материалы которые добавлены к сегодняшнему дню.

## Release 1. Списки с иерархией вне полей

Создай файл `ul.html` добавь в него базовый HTML-код:

```html
<!doctype html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Списки с иерархией вне полей</title>
</head>

<body>

</body>

</html>
```

Теперь необходимо создать список, у тебя есть четыре главные темы:
- Фаза 0
- Фаза 1
- Фаза 2
- Фаза 3

Фазы между собой должны быть на одном уровне иерархии, но недели в каждой фазе должны быть вложены в фазу.
Соответственно дни должны быть вложены в неделю. Используй теги `ul` `li` чтобы формировать списки.

Пример вложенности которую нужно реализовать для всех фаз:

```plain
Фаза 0
  Неделя 1
    Понедельник
    Вторник
    Среда
    Четверг
    Пятница
    Выходные
  Неделя 2
    Понедельник
    Вторник
    Среда
    Четверг
    Пятница
    Выходные
```

## Release 2. Списки с иерархией в полях

Когда первый список готов, пора делать второй, но другим способом.

Создай файл `select.html` добавь в него базовый HTML-код:

```html
<!doctype html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Списки с иерархией в полях</title>
</head>

<body>

</body>

</html>
```

Тебе нужно использовать теги `select`, `optgroup` и `option` для работы с новым списком.

В итоге нужно сделать 4 выпадающих списка с разным контентом внутри. Каждый список будет описывать фазу, начиная с 0-ой и заканчивая 3-ей. За основу возьми контент из списка который сформирован в файле `ul.html`.Дни каждой недели должны быть сгруппированы для наглядности и удобства выбора. Группировка делается через тег `optgroup`. Если тебе эти теги незнакомы, то самое время через поисковик узнать как они работают.

## Release 3. Стилизация*

Задание со звёздочкой, так как мы ещё не доходили до CSS-кода, но максимально поддерживаем твоё рвение и самостоятельность.
Было бы очень полезно, если ты начнёшь заранее изучать и пробовать стилизацию элементов.
Возьми за основу файл `ul.html` и сделай свой список стильным, тут уже нужно проявить фантазию!

Кстати, информацию по стилизации можно найти на [MDN](https://developer.mozilla.org/ru/docs/Web/HTML/Element/style).
