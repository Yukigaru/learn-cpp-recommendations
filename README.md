# Как обучаться C++

## Введение

В этом тексте я изложил свой взгляд на то, как лучше обучаться языку C++ новичку. Текст написан исходя из более десятка лет работы в компаниях, самообучения и преподавания. Помимо изучения нового в рамках работы, я пробовал разные способы: самообучение, курсы, проекты, ментор, преподавание, чтение сотен статей и просмотр видео — и могу их сравнить, проанализировать свой опыт, чтобы выдать вам гайд, как обучаться быстрее, эффективнее, чтобы вы могли меньше тратить своего времени на то, что работает плохо.
Однако всё написанное здесь — субъективно. Способы обучения индивидуальны: кому-то лучше подходит одно, кому-то другое. Пробуйте и ищите, что лучше работает лично для вас.

В списках ресурсов я перечислил только 1-3 наименования, выбрав только самое лучшее (на свой взгляд), чтобы вам можно было сфокусироваться, и не тратить время на выбор и перескакивание с одного на другое.

## Принципы

0. Поставьте цель. На мой взгляд, самая понятная и очевидная цель — это получение оффера от компании с нормальной (средней) оплатой, но существуют и другие.

1. Практика — самый полезный для обучения вид деятельности. В процентном соотношении практики должно быть больше всего по сравнению с остальными видами обучения. Без практики не будет обучения, только иллюзия. Еще раз (не последний): чем больше пишете кода своими руками, тем лучше.

2. Чем больше вы тратите времени на обучение, тем быстрее достигнете качественного результата (например, получения первой работы). Идеально тратить 8 часов в день, как полноценный рабочий день. Даже с таким темпом обучения достижение цели займёт несколько месяцев. Если тратите меньше, то масштабируйте сроки соответственно.

3. Существует порог времени в день, меньше которого нет смысла заниматься. Всё индивидуально, но я бы сказал, что порог где-то 30-60 минут. Если занимаетесь меньше этого, то вы не успеете глубоко погрузиться в задачу.

4. Вам должно быть интересно. Если вы изучаете программирование, потому что слышали, что за это хорошо платят, но вам приходится преодолевать себя, то будет сложно. Скорее всего, это не сработает.

5. В своих программах пробуйте разное, экспериментируйте, задавайте вопросы, выходите за рамки заданий. Например, после выполнения задачи спросите себя и свой код: а что, если еще вот так? А если ещё вот это попробовать?

6. Лучше фокусироваться несколько дней на определенной теме или определенном проекте и изучать все по этой теме, чем изучать разрозненную информацию. Хорошо: вы говорите себе "сейчас я изучаю TCP/IP" и начинаете читать гайды по сетевым технологиям, книги, практиковать, писать различные программы (клиенты, сервера, сетевые чаты и т.п.), гуглить конкретные темы и вопросы по TCP. Хуже: смотрю видео про строки, потом читаю про concurrency, потом про исключения, потом про сеть.


## Ресурсы

### Книги

- Б. Липпман, Язык программирования C++. Базовый курс. 5-е издание.
- Siddhartha Rao, C++ in One Hour a Day, Sams Teach Yourself.

С книгами есть два нюанса:
- авторы стараются описать в каждом разделе сразу всё, что есть в языке, таким образом выдавая читателю большой объем информации, которая может быть и не нужна на текущем этапе изучения языка.
- многие популярные книги написаны до C++11, и в лучшем случае новый стандарт для них является дополнительной главой либо правками в новом издании.

### Курсы

- [Educative](https://www.educative.io/courses/learn-cpp-from-scratch) — english, бесплатно, текстовый курс с задачами.
- [Programiz](https://app.programiz.pro/course/learn-cpp-basics/) — english, бесплатно, текстовый курс с задачами.
- [Яндекс.Практикум](https://practicum.yandex.ru/cpp/) — платно, обучение по книгам, нет видеолекций, много практики.
- [ШАД](https://shad.yandex.ru/) — бесплатно, но строгий отбор с экзаменом, поступление один раз в год, серьезное обучение.
- [Otus](https://otus.ru/lessons/cpp-basic/) — платно, видеолекции и практика.
- [LearnCpp](https://learncpp.com/) — english, бесплатно, текстовый курс без задач.

### Практика

0. Небольшие программы, чтобы изучить или проверить какую-то функцию, особенность языка или библиотеку. Вы просто пишете программу, понимаете, как работает функциональность, а потом идёте дальше.
Если это что-то небольшое, то удобно использовать для этого (1) repl.it (простой) или (2) godbolt.org (посложнее для новичка), иначе храните локально или в git.

1. Практико-ориентированные ресурсы — веб-сайты, где вам дают задачу, и вы пишете программу либо прямо на том же сайте, либо локально у себя.
  - [Codewars](https://codewars.com/kata/search/cpp)
  - [Leetcode](https://leetcode.com) — задачи на алгоритмы.
  - [Hackerrank](https://hackerrank.com/domains/cpp)
  - [Edabit](https://edabit.com/challenges)

2. Учебные проекты.

Программы большего размера, большей сложности, и нацеленные на предоставление какой-то функциональности пользователю. Идею придумываете вы сами, как и цели. Пользователем будете только вы (в лучшем случае), и это нормально.

3. Участие в open-source.

Уважаемая деятельность. Если вашу работу приняли в проект, значит вы проделали серьезную работу, ваш код проверили, приняли, и он будет приносить пользу. Однако сделать это очень непросто, потому что некоторые взрослые проекты очень сложны, а стартовые требования высоки. Рекомендации:
  - ищите молодые проекты, которые активно развиваются и уже имеют некую популярность (звёзд больше сотни, есть форки, issues, pull requests и свежие коммиты).
  - не брезгуйте помощью не по основному коду, а по документации, конфигам и доп. скриптам, это поможет вам плавно вникнуть в проект, а мейнтейнерам ознакомиться с вами.
  - ищите на GitHub issues с тегом `good-first-issue`.
  - спрашивайте мейнтейнеров, с чем можно помочь новичку.
  - не распыляйтесь, лучше выберите один проект и сконцентрируйтесь на нём, потому что вам потребуется несколько дней, чтобы понять код, и столько же, чтобы сделать что-то полезное.


### Справочник

Обязательный к применению, наилучший ресурс на данный момент: [C++ reference](https://en.cppreference.com/w/). Если во время написания программы у вас появился вопрос по конкретному классу/функции, консультируйтесь с cppreference.


### Текстовые статьи

Хороший материал для обучения. Полезно и работает:
- вы читаете статьи по той теме, которую сейчас изучаете и которая для вас сейчас актуальна. Когда читаете, стараетесь это практиковать.

Менее полезно и хуже работает:
- вы читаете всё подряд, без общей тематики. Не практикуете то, о чем прочитали. У вас в сохраненных несколько сотен статей.


### Видео

То же самое, что со статьями, полезно и работает:
- вы смотрите видео по той теме, которую сейчас изучаете и которая для вас сейчас актуальна. Когда видите что-то новое, стараетесь это практиковать.

Менее полезно и хуже работает:
- вы смотрите почти всё, что выходит у блогеров, на которых подписаны. Нет общей тематики. Вы не пробуете то, что увидели. У вас в сохраненных несколько сотен видео.



### Ментор

На мой взгляд, работа с ментором — это весьма ценная деятельность. Ментор — это опытный разработчик, который направляет ученика. Исходя из своего опыта, ментор видит то, что пока не видит обучаемый, поэтому он может направить его в правильную сторону, поможет срезать углы, сэкономить время, глубже погрузиться в тему. Он даёт рекомендации, направление, задаёт сложные вопросы, даёт задачи, но не разжевывает и не дает готовых инструкций. Поэтому важно не путать ментора с преподавателем. Видео на Youtube или лектор на курсе — именно преподаватель, а ментор ищется в других местах.

Есть два сайта:
  - [GetMentor](https://getmentor.dev/) - можно обратить внимание.
  - [Solvery](https://solvery.io/) - с осторожностью, более рассчитан на извлечение прибыли.

Важно помнить два нюанса:
 - Некоторые менторы или наставники на самом деле являются преподавателями (т.е. они рассказывают вам учебный материал).
 - Если вам предлагают услугу подбора ментора, не соглашайтесь, выбирайте сами.

И всё же я порекомендую просто написать тому человеку, которого вы приметили в блоге, на конференции или в каком-либо сообществе. Напишите ему о себе, своих целях, на что вы готовы в рамках обучения и что можете дать взамен (оплата - тоже нормально). Попробуйте, это работает.

