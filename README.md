# HelpDesk Telegram Bot


**Новые возможности: v0.4 beta**

> - Отправка уведомлений о задачах как пользователям, так и администраторам.
> - Добавлена кнопка выполнения задачи внутри уведомления.
> - Список истории задач с пагинацией.

![История заявок](https://github.com/prasx/HelpDesk/assets/33151983/9111ab96-6199-4d89-a79b-8e700907aa5a)![Исполнение заявок](https://github.com/prasx/HelpDesk/assets/33151983/80c75a73-d3d0-48f4-9fe3-f0c325855b04)



## Описание
Этот проект представляет собой Telegram бота, который предоставляет функционал HelpDesk системы. В текущей версии реализованы следующие функции:

- **Анкетирование:** Пользователи могут заполнять анкету, предоставляя информацию о наименовании организации, адресе заявки и контактном номере телефона.

- **Хранение заявок в базе данных:** Все созданные заявки сохраняются в базе данных. Информация о заявках доступна как администратору, так и пользователю в соответствующем разделе бота.

- **Уведомления о новых заявках:** Администратор получает уведомление с подробностями о новой заявке, что помогает оперативно реагировать на запросы пользователей.

- **База данных:** Проект использует базу данных, состоящую из таблицы заявок и таблицы пользователей для хранения информации.

- **Административная панель:** Администратору доступен вывод всех заявок в очереди, а также изменение статуса с "В работе" на "Завершён".

  
Необходимые пакеты:
```  pip install aiogram==2.25.2 ```

Запуск:
```  python main.py ``` 

## Репозиторий
Этот репозиторий является первым публичным для проекта. Здесь содержится исходный код бота, документация, и другие файлы, необходимые для развертывания и работы бота. Разработка ведется с акцентом на обеспечение удобства пользователей и оперативного реагирования на заявки.

## Примечание
Этот README.md может быть дополнен дальнейшей информацией о конфигурации, установке, использовании и других функциях бота по мере развития проекта.


