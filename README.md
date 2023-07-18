**Для работы с коллекцией необходимо:**
1. Скачать файл коллекции - GitHub issues.postman_collection.
2. Импортировать коллекцию в Postman.
<img src="image/task_list.jpg">
3. Сгенерировать на Гитхабе свой Personal access tokens (classic).<br> 
4. Вставить этот токен  в поле авторизации колекции, как показано на рисунке. Сохранить изменения.
<img src="image/insert_token.jpg">
5. Cоздание задачи.
<img src="image/create_task.jpg">
6. Получение списка задач.
<img src="image/get_list.jpg">
7. Изменение задачи.
<img src="image/change_task.jpg">
8. Блокировка задачи.
<img src="image/block_task.jpg">
9. Разблокировка задачи.
<img src="image/unblock_task.jpg">
10. Удаление задачи.<br> 
В документации нет описания метода удаления issue.<br> 
В запросе сервера на удаление задачи видно, какие данные уходят.
<img src="image/server_delete.jpg">
<img src="image/server_delete 2.jpg"><br> 
Но ввиду постоянной смены этого токена и не имея возможности определить его положение (в куках нет)<br>
оставлю этот запрос так.....
<img src="image/delete_task_qwestion.jpg">
11. Аналогичные запросы можно отправить с негативными проверками.



