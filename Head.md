# Head  
## Файл HEAD  
Файл HEAD (англ. «голова», «головной») — один из служебных файлов папки *.git*. Он указывает на коммит, который сделан последним (то есть на самый новый).  
Внутри HEAD — ссылка на служебный файл: refs/heads/master (или refs/heads/main в зависимости от названия ветки). Если заглянуть в этот файл, можно увидеть хеш последнего коммита.  
При работе с Git указатель **HEAD** используется довольно часто. Если нужно передать последний коммит, то вместо его хеша можно просто написать слово **HEAD** — Git поймёт, что вы имели в виду последний коммит.  
## Итоги:  
* В числе прочих файлов в папке *.git* есть служебный файл **HEAD**. Он указывает на самый свежий коммит.
* Вместо хеша последнего коммита можно написать слово **HEAD** — Git вас поймёт.