## Задание

1. Развернуть Laravel (commit init)
2. Установить на него voyager (commit voyager)
3. Сделать кастомный контроллер для новости (posts), наследованный от контроллера админ-панели по умолчанию + кастомный шаблон редактирования
4. При сохранении типа ввода поля title  (Text), изменить формат отображения именно этого поля на странице редактирования в качестве Textarea. (commit edit title)
5. Логика работы механизма BREAD не должна пострадать, любые изменения/добавления полей в админ-панели должны применяться к пользовательскому интерфейсу, как это работает по умолчанию

Запуск: на странице "*/admin/bread/posts/edit" в поле "Controller Name" необходимо добавить "\App\Http\Controllers\Voyager\PostCustomController"