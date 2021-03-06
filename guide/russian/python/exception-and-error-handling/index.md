---
title: Exceptions and Errors Handling
localeTitle: Исключения и ошибки Обработка
---
## Исключения и ошибки Обработка

При создании программы мы можем делать ошибки, которые заканчиваются ошибками и худшими программами, которые мы делаем, было бы еще более раздражать, если бы мы не смогли найти ошибок в коде, который мы сделали, или что было не так. Простыми словами, ошибки - это то, что программисты избегают при создании программы. Чтобы решить эту проблему в python, мы можем использовать `try` и `except`

Пример:

```shell
>>> try: 
 >>> . . . print "this is not a string "+1 
 >>> except: 
 >>> . . . print "error" 
 error 
```

и если вы хотите получить сообщения об ошибках более подробно из своего кода, вы можете добавить аргументы, `except Exception as err`

```shell
>>> try: 
 >>> . . . print "this is not a string "+1 
 >>> except Exception as err: 
 >>> . . . print "error:\n"+str(err) 
 error: 
 cannot concatenate 'str' and 'int' objects 
```

Дополнительная информация:

[Документация по](https://docs.python.org/2/tutorial/errors.html) ошибкам и исключениям.