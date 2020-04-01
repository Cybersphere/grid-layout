# grid-layout
ЧЕРНОВИК

##INTRO

```display: grid / inline-grid``` - объявляет элемент контейнером сетки

```grid-gap: 10px 10px```

  ``` grid-row-gap: 10px```
  
   ```grid-column-gap: 10px``` - отступы между колонками / столбцами

GRID LINES

Линии между столбцами называются линиями столбцов
Линии между строками называются линиями строк

При размещении элемента в сетке, обращаемся к линии

``` selector {
  grid-column-start: 1;
  grid-column-end: 3;
  grid-row-start: 1;
  grid-row-end: 3;
}```

 grid-template-columns:auto/size Определят кол-во столбцов и их размер
grid-template-rows: auto/size Определяет высоту строки

justify-content используется для выравнивания всей сетки внутри контейнера.
align-content  используется для вертикального выравнивания всей сетки внутри контейнера.


```grid-column``` - определяет сколько элемент займет столбцов
To place an item, you can refer to line numbers, or use the keyword "span" to define how many columns the item will span.
