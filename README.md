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
}

 grid-template-columns Определят кол-во столбцов и их размер
