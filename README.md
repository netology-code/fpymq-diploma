# Курсовой проект курса «Адаптивная и мобильная верстка»

## Цель

Сверстать адаптивные макеты сайта для устройств:

1. Мобильные (mobile)
2. Планшеты (tablet)
3. Стационарные (desktop)

Макеты выглядят так:

![Layout](img/layouts.jpg)

## Зачем?

1. Закрепите навыки работы с Git и Github
2. Разработаете с нуля проект, который можно добавить в своё портфолио
3. Закрепите знания адаптивной вёрстки

## Необходимые инструменты

1. Git и GitHub
2. Photoshop ([а можно без него?](#Часто-задаваемые-вопросы))
3. Ваш любимый текстовый редактор (Visual Studio Code, если вы ничего не любите)

## Этапы сдачи проекта

Работа сдаётся поэтапно

1. Готовая desktop-версия сайта (без медиазапросов)
2. Адаптивная версия сайта (mobile+tablet)

Для удобства обратной связи в рамках этапа вы можете отправлять на проверку проект по частям/блокам.

## Исходные файлы

1. PSD-макеты в папке [./sources/psd](./sources/psd)
2. JPG версии макетов для быстрого просмотра в папке [./sources/preview](./sources/preview/)
3. Фоновые и контентные изображения в [./sources/img](./sources/img/)
4. Файлы шрифтов папке [./sources/fonts](./sources/fonts/)
5. SVG-иконки в папке [./sources/svg](./sources/svg/)

## С чего начать?

Перед началом работы, пожалуйста, посмотрите видео-инструкцию по [ссылке](https://embed.new.video/cxEqtfQzkYST15TtikEAWF?sig=eyJhbGciOiJIUzI1NiJ9.eyJ1c2VyX2lwIjoiMTA5LjI1Mi40MS45OCIsInZpZGVvX3Rva2VuIjoiY3hFcXRmUXprWVNUMTVUdGlrRUFXRiJ9.fqxDLhpUA1gcTj6mnjqO0q9r5Wvqk8by1jdkCzz6FMY).

Примечание к видео:
> Если при выборе ветки для публикации у вас нет ветки `master` в выпадающем списке, то выбирайте `main`.

## Критерии зачёта

1. Макет опубликован на [GitHub Pages](https://pages.github.com/). 
2. Работа выполнена в соответствие с [требованиями](#requirements)

<a id="requirements"></a>

## Требования

1. [Этап 1. Стационарная версия](./requirements_step-1.md)
2. [Этап 2. Адаптивная версия + всплывающая форма](./requirements_step-2.md)

## Рекомендации

Следование данным рекомендациям не обязательно и не влияет на получение зачёта

1. Для кроссбраузерной вёрстки используйте библиотеку [normalize.css](./https://necolas.github.io/normalize.css/)
2. Для упрощения работы, уменьшения повторов кода рекомендуется использовать методологию БЭМ
3. При выполнении второго этапа рекомендуется использовать подход Mobile First
4. Чтобы выдержать точное соответствие макету, вы можете использовать подход по Pixel Perfect

### Как правильно задавать вопросы руководителю курсового проекта?
Что поможет решить большинство частых проблем:

1. Попробовать найти ответ сначала самому в интернете. Скилл поиска ответов пригодится вам в профессиональной деятельности. И только после этого спрашивать руководителя курсового проекта.
1. Если вопросов больше одного, то присылайте их в виде нумерованного списка. Так руководителю будет проще отвечать на каждый из них.
1. При необходимости прикрепите к вопросу скриншоты и стрелочкой покажите, где не получается. Программу для этого можно скачать здесь [https://app.prntscr.com/ru/](https://app.prntscr.com/ru/)
1. По возможности, задавайте вопросы в комментариях к коду.
1. Начинать работу над курсовым проектом как можно раньше! Чтобы было больше времени на правки.
1. Делайте проект частями, а не всё сразу. Если сделать всё сразу, то количество комментариев от руководителя может вас деморализовать.

Что может стать источником проблем:

1. Вопросы вида «Ничего не работает. Не запускается. Всё сломалось.». Руководитель курсового проекта не сможет ответить на на такой вопрос без дополнительных уточнений. Цените своё время и время других.
2. Откладывание курсового проекта на последний момент.
3. Ожидание моментального ответа на свой вопрос. Руководители курсового проекта - работающие разработчики, которые занимаются, кроме преподавания, своими проектами. Их время ограничено, поэтому постарайтесь задавать правильные вопросы, чтобы получать быстрые ответы.

## Часто задаваемые вопросы

> 1. Можно ли не использовать Photoshop?
> 2. Можно ли использовать технологии и программы, которые мы не разбирали в курсе?

Если у вас нет достаточной уверенности и опыта, выполняйте работу в Photoshop.

Если вы:
1. Обеспечите точное соответствие требованиям этапов
2. Уложитесь в срок сдачи работы

вы можете использовать любую технологию и инструмент. При этом:

1. Ваша работа удобна для последующей доработки
2. Код легко и приятно читать вам и руководителю курсового проекта
3. Вы в состоянии обосновать руководителю необходимость применения технологии в проекте

Задача современного разработчика - подобрать подходящий проекту набор инструментов, 
а не выбрать наугад или его самые любимые.

Если вы выбираете технологии и инструменты, которые не рассматриваются: 
- В курсе
- Описании этой дипломной работы

перед началом курсового проекта обсудите возможность их применения с вашим руководителем.
