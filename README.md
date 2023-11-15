# qa_python

Список тестов:

1) test_add_new_book_add_two_books - проверка добавления книг
2) test_add_new_book_incorrect_len_name_no_add - книга не добавляется, если название 0, 41 и более 41 символа
3) test_add_new_book_correct_len_name - книга добавляется, если название более 0 и менее 41 символа
4) test_add_new_book_no_duplicate_book - проверка добавления книги без дубликата
5) test_set_book_genre - проверка установки книге жанра
6) test_get_book_genre - проверка получения книги по её жанру
7) test_get_book_genre_incorrect_genre_no_add - жанр книги не добавляется, если его нет в списке жанров
8) test_get_books_with_specific_genre - проверка вывода списка книг с определенным жанром
9) test_get_books_genre - проверка, что жанр добавляется в словарь books_genre
10) test_get_books_for_children - проверка возвращения детских книг
11) test_get_books_for_children_adult_genre_no_add - взрослые книги не добавляются в детские
12) test_add_book_in_favorites - проверка добавления книги в избранное
13) test_add_book_in_favorites_no_duplicate_favorites - книги не дублируются в избранном
14) test_delete_book_from_favorites - удаление книги из избранного
15) test_get_list_of_favorites_books - добавление избранной книги в список favorites