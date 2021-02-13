\---

\# Front matter

lang: ru-RU

title: Оотчет по лабораторной работе №1"

subtitle: "Филиппова Вероника"

\# Formatting

toc-title: "Содержание"

toc: true # Table of contents

toc\_depth: 2

lof: true # List of figures

lot: true # List of tables

fontsize: 12pt

linestretch: 1.5

papersize: a4paper

documentclass: scrreprt

polyglossia-lang: russian

polyglossia-otherlangs: english

mainfont: PT Serif

romanfont: PT Serif

sansfont: PT Sans

monofont: PT Mono

mainfontoptions: Ligatures=TeX

romanfontoptions: Ligatures=TeX

sansfontoptions: Ligatures=TeX,Scale=MatchLowercase

monofontoptions: Scale=MatchLowercase

indent: true

pdf-engine: lualatex

header-includes:

- \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
- \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
- \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
- \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
- \binoppenalty=700 # the penalty for breaking a line at a binary operator
- \relpenalty=500 # the penalty for breaking a line at a relation
- \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
- \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
- \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
- \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
- \predisplaypenalty=10000 # penalty for breaking before a display
- \postdisplaypenalty=0 # penalty for breaking after a display
- \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
- \raggedbottom # or \flushbottom
- \usepackage{float} # keep figures where there are in the text
- \floatplacement{figure}{H} # keep figures where there are in the text

\---

\# \*\*Цель работы\*\*

Узнать как работать с github, а также познакомиться

с основными возможностями разметки Markdown.

# **Задание**

1. Создать репозиторий на github.com
1. Создать и загрузить файлы на github.com
1. Сделать коммит и пуш
1. Создать и подключить ssh ключ
1. Сделать релиз на github.com
1. Оформить и загрузить отчет и презентацию в 3 форматах doc,pdf,md.

\# \*\*Выполнение лабораторной работы\*\*

1. \*Создала репозиторий на гитхаб (рис.1)\*

![Рис.1](scrn/1.jpg){ #fig:001 width=70% }

1. \*Создала и загрузила файлы на гитхаб (рис.2)\*

![Рис.2](scrn/5.jpg){ #fig:002 width=70% }

1. \*Сделать коммит и пуш (рис.3)\*

![Рис.3](scrn/6.jpg){ #fig:003 width=70% }

1. \*Создала и подключила ssh ключ\*

![Рис.4](scrn/2.jpg){ #fig:004 width=70% }

![Рис.5](scrn/3.jpg){ #fig:005 width=70% }

1. \*Сделала релиз на github.com\*

![Рис.6](scrn/4.jpg){ #fig:006 width=70% }

\# \*\*Выводы\*\*

Научилась работать с github.com, а так же познакомилась с основными разметками Markdown.
