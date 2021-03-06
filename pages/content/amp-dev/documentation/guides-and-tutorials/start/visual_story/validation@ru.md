---
'$title': Валидация кода AMP HTML
$order: 8
description: Валидацию кода AMP HTML следует выполнять во всех создаваемых AMP-cтраницах. Есть несколько методов, которые можно использовать для валидации AMP-страниц...
author: bpaduch
---

Поскольку веб-истории пишутся на AMP, вы всегда должны проверять правильность кода AMP HTML. Есть [несколько методов, которые можно применять для валидации AMP-страниц](../../../../documentation/guides-and-tutorials/learn/validation-workflow/validate_amp.md). В данном уроке мы активируем AMP-валидатор, включив режим разработчика. Чтобы включить режим разработчика, добавьте к своему URL-адресу следующий фрагментный идентификатор (после чего перезагрузите страницу):

```text
#development=1
```

Например:

```text
http://localhost:8000/pets.html#development=1
```

Откройте [консоль разработчика](https://developer.chrome.com/devtools/docs/console) в Chrome (или в предпочитаемом вами браузере) и убедитесь, что ошибки AMP отсутствуют. Возможно, чтобы увидеть сообщения валидации, вам потребуется обновить страницу в браузере. Если на вашей странице ошибок нет, должно отобразиться следующее сообщение:

```text
 AMP validation successful.
```
