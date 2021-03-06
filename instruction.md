# Инструкция по GIT

Для того чтобы начать пользоваться GIT, его нужно скачать и установить. Скачать его можно <code>[ЗДЕСЬ](https://git-scm.com/downloads "Ссылка на файл")
</code>

Также, нам понадобится какой-нибудь редактор кода или IDE. Я буду писать на своём либимом  PHPSTORM, а вы можете использовать  VSC, скачать его можно <code>[ЗДЕСЬ](https://code.visualstudio.com/ "Ссылка на файл")
</code> 

Итак, поехали...
Будем считать, что мы установили GIT, инициализировали его...

<code>![Фото GIT](/img/git.png "Фото GIT")
</code>

Создадаём файл с разрешением .md, к примеру instruction.md, и давай писать на Markdown, на облегчённом языке разметки.


Индексируем файл командой **git add .\instruction.md**, кстати, можно ввести только команду и начальные буквы файла - типа, **git add in...**, нажать Tab, остаток команды подставится автоматически.

Сохраняем (фиксируем) изменения командой и в обязательном порядке, не забываем добавить коммент. Пример: **git commit -m"Added a new line"**

Для того чтобы переключиться на интересующий нам коммит, нужно узнать его хэш. Узнать его можно командой **git log**. Копируем первые символы хэша и подставляем в конце команды, должна получиться примерно такая строка **git checkout 797a**

## Основные  команды

**git add .\instruction.md -** *индексация*  
**git commit -m"Добавили новую строку" -** *Сохранение*  
**git log -** *Журнал изменений*  
**git checkout 797a -** *переключиться на коммит с указанным хешем*  
**git diff -** *Сравнение именений*   
**git status -** *Отображает состояние рабочего каталога и раздела проиндексированных файлов*

## Продолжение следует.....


