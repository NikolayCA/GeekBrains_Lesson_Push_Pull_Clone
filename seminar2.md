## Туториал по основам системы контроля версий GIT

## Инициализация проекта
**Чтобы добавить возможность использовать разные версии файлов, необходимо использовать следующую команд:**

```fix
git init
```
## Как добавить файл в отслеживание
**Чтобы добавить файл в отслеживание, используйте следующую команду**

```fix
git add
```

## Команда для просмотра статуса GIT
**Чтобы получить информацию от git о его текущем состоянии:**

```fix
git status
```
**Чтобы добавить коммит, необходимо ввести команду:**

```fix
git commit -m
```

**Вывод на экран истории всех коммитов с их хеш-кодами:**

```fix
git log
```

**Переход от одного коммита к другому:**

```fix
git checkout
```


# Инструкция-туториал по разметке MarkDawn


## Заголовки

```fix
Заголовки отмечаются диезом `#` в начале строки, от
одного до шести. Например:
```

# Заголовок первого уровня
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6  

В декоративных целях заголовки можно «закрывать» с
обратной стороны.



## Списки

Для разметки неупорядоченных списков можно использовать
или `*`, или `-`, или `+`:
- элемент 1
- элемент 2
- элемент ...
Вложенные пункты создаются четырьмя пробелами перед
маркером пункта:
* элемент 1
* элемент 2
 * вложенный элемент 2.1
 * вложенный элемент 2.2
* элемент ...
Упорядоченный список:
1. элемент 1
2. элемент 2
 1. вложенный
 2. вложенный
3. элемент 3
4. Donec sit amet nisl. Aliquam semper ipsum sit amet
velit. Suspendisse id sem consectetuer libero luctus
adipiscing.
На самом деле не важно как в коде пронумерованы пункты,
главное, чтобы перед элементом списка стояла цифра
(любая) с точкой. Можно сделать и так:
0. элемент 1
0. элемент 2
0. элемент 3
0. элемент 4
Список с абзацами:
* Раз абзац. Lorem ipsum dolor sit amet, consectetur
adipisicing elit.
* Два абзац. Donec sit amet nisl. Aliquam semper ipsum
sit amet velit. Suspendisse id sem consectetuer libero
luctus adipiscing.
* Три абзац. Ea, quis, alias nobis porro quos laborum
minus sed fuga odio dolore natus quas cum enim
necessitatibus magni provident non saepe sequi?
 Четыре абзац (Четыре пробела в начале или один tab).



## Ссылки

Это встроенная [ссылка с title элементом]
(http://example.com/link "Я ссылка"). Это — [без title]
(http://example.com/link).
А вот [пример][1] [нескольких][2] [ссылок][id] с
разметкой как у сносок. Прокатит и [короткая запись][]
без указания id.
[1]: http://example.com/ "Optional Title Here"
[2]: http://example.com/some
[id]: http://example.com/links (Optional Title Here)
[короткая запись]: http://example.com/short
Вынос длинных урлов из предложения способствует
сохранению читабельности исходника. Сноски можно
располагать в любом месте документа.




## Картинки

**Что бы добавить изображения, воспользуйтесь командой**
```fix
![Здесь был кто то](ссылка на фото)
```
## например:
![просто картинка](https://images.unsplash.com/photo-1642362932918-e06b87fc185b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80)

## *также можно добавить клик картинку, конструкция выглядит таким образом:*

```fix
[![]()]()
```

# Например:

[![Click to bonus](https://images.unsplash.com/photo-1642362932918-e06b87fc185b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80)](https://www.google.com/imgres?imgurl=https%3A%2F%2Fpng.pngtree.com%2Fpng-vector%2F20210110%2Fourlarge%2Fpngtree-hello-world-svg-design-png-image_2719857.jpg&tbnid=vGklTupr25mp1M&vet=12ahUKEwjyl-yZ3Z3_AhVFuCoKHZugCUoQMygHegUIARDcAQ..i&imgrefurl=https%3A%2F%2Fru.pngtree.com%2Ffreepng%2Fhello-world-svg-design_5839365.html&docid=T7KZILIKfSMYuM&w=640&h=640&q=%D0%BA%D0%B0%D1%80%D1%82%D0%B8%D0%BD%D0%BA%D0%B8%20%D0%BF%D1%80%D0%B8%D0%B2%D0%B5%D1%82%20%D0%BC%D0%B8%D1%80&ved=2ahUKEwjyl-yZ3Z3_AhVFuCoKHZugCUoQMygHegUIARDcAQ)
