# mokushozen.bg
## Указания за редакторите

### Въведение
Сайтът има две страници: главна (index.md) и архив (past_events.md). Събитията се постват на главната в секция *Предстоящи събития*. След като дадено събитие отмине, със cut и paste се премества от главната най-горе в архива. Това е важно, защото първо търсачките ни ранкират по-високо, и второ, хората могат да придобият представа за каква практика иде реч.

### Как се редактира

1. Цъкате на файла по-горе, напр `index.md`
2. Цъквате на иконката с моливче в горния десен ъгъл над текста
3. Той е прост текстов файл, в който форматирането се прави със зведдички, диезчета и други символи, ограждащи текста който желаете да форматирате.
3.1. Заглавие: 
```

# Заглавие

```
Забележете новите редове преди и след заглавието! Без тях няма да се покаже коректно!
3.2. *Получер*: `*получерен текст`
3.3. _Курсив_: `_курсивен текст_`
3.4. Връзка:  [Мокушо дзен Румъния](http://mokushozen.ro/) `[Мокушо дзен Румъния](http://mokushozen.ro/)`
3.5. Таблица: 

|понеделник|7:00-8:20|
|вторник|7:00-8:20|
|сряда|19:30-20:50|
|петък|7:00-8:20|

```
|понеделник|7:00-8:20|
|вторник|7:00-8:20|
|сряда|19:30-20:50|
|петък|7:00-8:20|
```
3.5. За повече форматирания: https://github.github.com/gfm/

4. Когато сте готови, цъкате на зеления бутон *Commit* под формата. Github ще генерира уеб страницата наново и след около десетина секунди промяната ще е видима на сайта. Preview-то (иконката в горния ляв ъгъл) не работи коректно, за това не го ползвам.

5. Задължително проверете как изглежда сайта след промяна, защото вероятността нещо да се обърка не е малка (-;
