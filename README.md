Работа номер 4.
стек: react + node + axios.

Сайт реализован на localhost через порт 3000. 
На сайте в вертикальном направление выводится таблица, содержащая все ToDo с сервера из задания два, и две кнопки - Add Card, Delete All. 
В таблице отображаются: id, title, description, isDone - свойства ToDo, а также добавлен столбец для действий с каждым элементом - Action.

Описание раздела Action: есть три кнопки:
1) Edit (редактировать) - при нажатие перехадим на страницу (http://localhost:3000/update/:id, где id соответсвует todo.id), где можем редактировать поля todo.title и
todo.description; можем принять изменения, нажав на кнопку Update, и автоматически вернуться на главную страницу либо отказаться от изменений и выйти, нажав на кнопу Back;
2) Delete (удалить) - при нажатие появляется окно, в котором подтверждают наше рвение в удалении данного Todo 
3) View (отображение) - можем просмотреть содержимое данного элемента (http://localhost:3000/view/:id, где id соответсвует todo.id) на отдельной странице. Так же имеется
кнопка возврата.

Кнопка Add Card переводит нас http://localhost:3000/addCard. На данной станице мы можем создать новую карточку ToDo, введя title и description. Другие атрибуты задаются
по умолчанию. Если попробоваться создать пустую карточку, то вылезит предупреждение. После создания автоматически возвращаемся на главную, либо можем ничего не создавать и
вернуться обратно стукнув по кнопке Back.

Кнопка Delete All удалает все ToDo карточки (перед этим повляется окно, требующие от нас подтверждение).


!!! Поля Id никак не изменяются при удалении и добавлении, так как по умолчанию это поле считается мною таким же не изменяющимся автоматически, как и другие поля.
(По условию задания).
