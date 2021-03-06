# Отчет по лабораторной работе №10

----

# Тема:
## Текстовой редактор emacs

----

## Российский Университет Дружбы Народов

### Факультет Физико-Математических и Естественных Наук

*Дисциплина: Операционные системы*

Студент: Алших Маслем Ахмад 
Группа: НФИБД-02-20


----

### Цель работы

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

----



#### Что такое Emacs?

Emacs — один из наиболее мощных и широко распространённых редакторов, используемых в мире Unix. По популярности он соперничает с редактором vi и его клонами. В зависимости от ситуации, Emacs может быть:

* текстовым редактором;
* программой для чтения почты и новостей Usenet;
* интегрированной средой разработки (IDE);
* операционной системой;
* всем, чем угодно.



----

### Последовательность выполнения работы
1. Ознакомиться с теоретическим материалом.
2. Ознакомиться с редактором emacs.
3. Выполнить упражнения.
4. Ответить на контрольные вопросы.

----

### Ход работы:

1. Открыл emacs.

![181a7478e767479c3.png](https://ic.wampi.ru/2021/05/22/181a7478e767479c3.png)

2. Создал файл lab07.sh с помощью комбинаций Ctrl-x Ctrl-f (C-x C-f).
![24b946e802f1740ec.png](https://ic.wampi.ru/2021/05/22/24b946e802f1740ec.png)
3. Набрал текст:

>#!/bin/bash
 HELL=Hello
 function hello {
 LOCAL HELLO=World
 echo $HELLO
 }
 echo $HELLO
 hello

![3cb99f2afb9b064b6.png](https://ic.wampi.ru/2021/05/22/3cb99f2afb9b064b6.png)

4. Сохранил файл с помощью комбинаций Ctrl-x Ctrl-s (C-x C-s).

![45dd58751b9f0edb9.png](https://ic.wampi.ru/2021/05/22/45dd58751b9f0edb9.png)

5. Проделал с текстом стандартные процедуры редактирования, каждое действие осуществлял комбинацией клавиш.

* Вырезал одной командой целую строку (С-k).

![564126ef92a1c5eb4.png](https://ic.wampi.ru/2021/05/22/564126ef92a1c5eb4.png)

* Вставил эту строку в конец файла (C-y).

![67af0cb8138e19ea1.png](https://ic.wampi.ru/2021/05/22/67af0cb8138e19ea1.png)

* Выделил область текста (C-space).



* Скопировал область в буфер обмена (M-w).

* Вставил область в конец файла.


* Вновь выделил эту область и на этот раз вырезал её (C-w).


* Отменил последнее действие (C-/).

1. Научился использовать команды по перемещению курсора.

* Переместите курсор в начало строки (C-a).



* Переместите курсор в конец строки (C-e).


* Переместите курсор в начало буфера (M-<).


* Переместите курсор в конец буфера (M->).


1. Управление буферами.

* Вывел список активных буферов на экран (C-x C-b).

![7b0d09d3126d9db9e.png](https://ic.wampi.ru/2021/05/22/7b0d09d3126d9db9e.png)

* Переместился во вновь открытое окно (C-x) o со списком открытых буферов и переключился на другой буфер.



* Закрыл это окно (C-x 0).

![856bfa35aaa789caf.png](https://ic.wampi.ru/2021/05/22/856bfa35aaa789caf.png)

* Вновь переключился между буферами, но уже без вывода их списка на экран (C-x b).


1. Управление окнами.

* Поделил фрейм на 4 части: разделил фрейм на два окна по вертикали (C-x 3), а затем каждое из этих окон на две части по горизонтали (C-x 2)

![932a3a789362b3f41.png](https://ic.wampi.ru/2021/05/22/932a3a789362b3f41.png)

![10ad20b0fc2b91b6d3.png](https://ic.wampi.ru/2021/05/22/10ad20b0fc2b91b6d3.png)
* В каждом из четырёх созданных окон открыл новый буфер (файл) и ввел несколько строк текста.

![11bedaa48603824ce2.png](https://ic.wampi.ru/2021/05/22/11bedaa48603824ce2.png)

9. Режим поиска

* Переключился в режим поиска (C-s) и нашел несколько слов, присутствующих в тексте.

![12371d4bbb77e2b2e3.png](https://ic.wampi.ru/2021/05/22/12371d4bbb77e2b2e3.png)
* Переключился между результатами поиска, нажимая C-s.


* Вышел из режима поиска, нажав C-g.



* Перешел в режим поиска и замены (M-%), ввел текст, который следует найти и заменить, нажал *Enter* , затем ввел текст для замены. После подсвечивания результатов поиска, нажал ! для подтверждения замены.


* Попробовал другой режим поиска, нажав M-s o. Он отличается от обычного режима тем, что при поиске указывает номера строк в которых найдено введённое слово и выделяет их цветом. В обычном режиме выделение цветом появляется, только когда нужно подтвердить замену.



----

### Вывод

Познакомился с операционной системой Linux, получил практические навыки работы с редактором Emacs.

----

### Библиография



----

## Ответы на контрольные вопросы:

1. Emacs представляет собой мощный экранный редактор текста, написанный на
языке высокого уровня Elisp.
2. Развитие Emacs в сторону его многогранности послужило причиной того, что и без того интуитивно непонятная программа стала чрезвычайно сложной в применении. В частности, управление осуществляется при помощи различных клавиатурных комбинаций, запомнить которые будет непросто.
3. Буфер – что-то, состоящее из текста. 
Окно – область с одним из буферов.
4. В одном окне можно открыть больше 10 буферов.
5. После запуска emacs без каких-либо параметров в основном окне отображается буфер *scratch*, который используется для оценки выражений Emacs Lisp, а также для заметок, которые вы не хотите сохранять. Этот буфер не сохраняется автоматически.
6. Чтобы ввести следующую комбинацию C-c | я нажму клавиши: Control+c и Shift+\, и для C-c C-|: Control+c и Control+Shift+\.
7. Поделить текущее окно на две части можно двумя комбинациями клавиш: 
C-x 3 или C-x 2.
8. Настроить или расширить Emacs можно написав или изменив файл ~/.emacs.
9. Клавиша  выполняет функцию перемещения курсора в открытом окне также, как и многие другие клавиши её можно переназначить.
10. Редактор emacs показался мне удобнее из-за возможности открытия нескольких окон с буферами и работать комбинациями клавиш в этот редакторе мне было проще.
