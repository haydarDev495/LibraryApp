# Library
1) для того что бы запустить проект на устройстве скачайте проект и установите поды. 
2) после запуска появится экран с коллекцией(BooksViewController), в методе viewWillAppear вызываю функцию(checkOnbording) которая  берет значение с UserDefaults под ключем onbording если значение true то код не зайдет в этот блок если значение false то зайдет и экран покажется с помошью present(vc)  
2) onbording после второго нажатия значение true сохранится в UserDefaults и экран скроется с помошью метода dissmiss
3) далее экран с коллекцией(BooksViewController) при запуске VC в методе viewDidload получаем данные пока они грузятся на экране будет label с меняющимся текстом Loading. , Loading.. , Loading... после загрузки данных label исчезнет и коллекция обновиться 
4) так же при прокрутки коллекции до последней ячейки вызывается метод загрузки книг и мы добавим еще 5 книг в коллекцию 
5) по нажатию на ячейку переходим на экран с более подробной информацией о книге
6) на ТЗ было потрачени 7 часов, больше всего времени было потрачено на поиск подходящей ссылки и на реализацию пагинации, после уже думал немного о дизайне приложения. 
7) спасибо за внимание  и хорошего дня!



![Запись экрана 2023-04-15 в 19 22 03 (2)](https://user-images.githubusercontent.com/97893617/232245225-bcb9ef04-e959-4547-b8dd-1fbab2e585dd.gif)
