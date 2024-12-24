Вариант 5: Приложение "Книга рецептов"
###
Задача: Разработать приложение для получения списка рецептов с возможностью отображения детализации по каждому из рецептов
Функциональные требования:
1. Данные по текущим рецептам и шагам по приготовлению необходимо запросить с сервера по URL https://v78qr.wiremockapi.cloud/recipes
2. Рекомендуется использовать RecyclerView для отображения списка рецептов, а ConstraintLayout или LinearLayout для экрана с деталями рецепта.
3. Использовать компоненты Material Design, такие как CardView и FloatingActionButton, для удобного интерфейса и навигации.
4. Отображать карточку с деталями рецепта на отдельном экране с детализацией при нажатии на конкретный элемент списка 
5. Обработать корректные и некорректные HTTP-ответы, показывая Snackbar или диалог при ошибках.
6. Использовать асинхронные запросы к API без блокировки UI с библиотекой Retrofit и Kotlin Coroutines.
7. Иметь возможность обновлять пользовательский интерфейс каждые 60 секунд и получать новые данные по рецептам
    1. Можно использовать coroutine с thread sleep в качестве одного из решений
###
