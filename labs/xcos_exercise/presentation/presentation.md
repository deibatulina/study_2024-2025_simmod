---
## Front matter
lang: ru-RU
title: Презентация по упражнению xcos
subtitle: Компонентное моделирование. Scilab, подсистема xcos
author:
  - Ибатулина Д.Э.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 5 марта 2025

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Ибатулина дарья эдуардовна
  * студентка группы НФИбд-01-22
  * Российский университет дружбы народов
  * [1132226434@rudn.ru](mailto:1132226434@rudn.ru)
  * <https://deibatulina.github.io>

:::
::: {.column width="30%"}

![](./image/me.jpg)

:::
::::::::::::::

# Вводная часть

## Актуальность

Тема моделирования различных процессов, происходящих в мире, актуальна, поскольку позволяет найти решения для их оптимизации.

## Объект и предмет исследования

- Процесс функционирования двух источников синусоидального сигнала
- Программное обеспечение для моделирования (xcos, OpenModelica)

## Цели и задачи

Научиться работать со средствами моделирования xcos и OpenModelica.

Задачи:

1. Реализовать имитационную  модель функционирования двух источников синусоидального сигнала, позволяющая в зависимости от задаваемых параметров построить различные фигуры Лиссажу в xcos с различными параметрами;
2. Реализовать имитационную  модель функционирования двух источников синусоидального сигнала, позволяющая в зависимости от задаваемых параметров построить различные фигуры Лиссажу в OpenModelica.

# Основная часть

## Теоретическое введение

\centering
![](./image/1.png){width=100%}

## Палитры блоков

\centering
![](./image/2.png){width=100%}

## Пример модели

\centering
![](./image/3.png){width=100%}

## Математическое выражение для кривой Лиссажу

$$
\begin{cases} 
x(t) = A \sin(at + \delta), \\ 
y(t) = B \sin(bt) 
\end{cases}
$$

## Задание характеристик блоку

\centering
![](./image/5.png){width=60%}

## $A = B = 1, a = 2, b = 2, \delta = 0$

\centering
![](./image/7.png){width=60%}

## $A = B = 1, a = 2, b = 2, \delta = \pi /4$

\centering
![](./image/8.png){width=60%}

## $A = B = 1, a = 2, b = 2, \delta = \pi /2$

\centering
![](./image/9.png){width=60%}

## $A = B = 1, a = 2, b = 2, \delta = 3\pi /4$

\centering
![](./image/10.png){width=60%}

## $A = B = 1, a = 2, b = 2, \delta = \pi$

\centering
![](./image/11.png){width=60%}

## $A = B = 1, a = 2, b = 4, \delta = 0$

\centering
![](./image/12.png){width=60%}

## $A = B = 1, a = 2, b = 4, \delta = \pi /4$

\centering
![](./image/13.png){width=60%}

## $A = B = 1, a = 2, b = 4, \delta = \pi /2$

\centering
![](./image/14.png){width=60%}

## $A = B = 1, a = 2, b = 4, \delta = 3\pi /4$

\centering
![](./image/15.png){width=60%}

## $A = B = 1, a = 2, b = 4, \delta = \pi$

\centering
![](./image/16.png){width=60%}

## $A = B = 1, a = 2, b = 6, \delta = 0$

\centering
![](./image/17.png){width=60%}

## $A = B = 1, a = 2, b = 6, \delta = \pi /4$

\centering
![](./image/18.png){width=60%}

## $A = B = 1, a = 2, b = 6, \delta = \pi /2$

\centering
![](./image/19.png){width=45%}

## $A = B = 1, a = 2, b = 6, \delta = 3\pi /4$

\centering
![](./image/20.png){width=60%}

## $A = B = 1, a = 2, b = 6, \delta = \pi$

\centering
![](./image/21.png){width=60%}

## $A = B = 1, a = 2, b = 3, \delta = 0$

\centering
![](./image/22.png){width=60%}

## $A = B = 1, a = 2, b = 3, \delta = \pi /4$

\centering
![](./image/23.png){width=60%}

## $A = B = 1, a = 2, b = 3, \delta = \pi /2$

\centering
![](./image/24.png){width=60%}

## $A = B = 1, a = 2, b = 3, \delta = 3\pi /4$

\centering
![](./image/25.png){width=60%}

## $A = B = 1, a = 2, b = 3, \delta = \pi$

\centering
![](./image/26.png){width=60%}

## Редактор OMEdit

\centering
![](./image/27.png){width=60%}

## Создание класса

\centering
![](./image/28.png){width=80%}

## Просмотр класса в текстовом виде

\centering
![](./image/29.png){width=60%}

## Написание кода для задания дифференциального уравнения

\centering
![](./image/30.png){width=60%}

## Задание параметров симуляции

\centering
![](./image/31.png){width=60%}

## Полученные графики для x и x'

\centering
![](./image/32.png){width=60%}

## Полученный график для x

\centering
![](./image/33.png){width=60%}

# Заключительная часть

## Выводы

В результате выполнения лабораторной работы я научилась работать со средствами моделирования xcos и OpenModelica.


