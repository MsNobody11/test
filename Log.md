# Лог  
## Элементы описания коммита  
После вызова *git log* появляется список коммитов.  
*Элементы, из которых состоит описание:*
* строка из цифр и латинских букв после слова **commit** — это хеш коммита;
* **Author** — имя автора и его электронная почта;
* **Date** — дата и время создания коммита;
* в конце находится сообщение коммита.


---
## Получить сокращённый лог — *git log --oneline*   
Получить сокращённый лог можно с помощью команды *git log* с флагом *--oneline* (англ. «одной строкой»). В терминале появятся только первые несколько символов хеша каждого коммита и их комментарии.  
Сокращённый хеш (то есть первые несколько символов полного) можно использовать точно так же, как и полный. Для этого команда *git log --oneline* автоматически подбирает такую длину сокращённых хешей, чтобы они были уникальными в пределах репозитория и Git всегда мог понять, о каком коммите идёт  
**!!! Обратите внимание:** если выход из просмотра логов не произошёл автоматически, нажмите клавишу **Q** (от англ. Quit — «выйти») в английской раскладке клавиатуры.