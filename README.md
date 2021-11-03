**Создание простого многопоточного сервера**

**Цель работы**

Познакомиться с приемами работы с многопоточностью на примере создания сокетного TCP-сервера, способного работать с несколькими клиентами одновременно

**Задания:**

1. Модифицировать простой эхо-сервер таким образом, чтобы при подключении клиента создавался новый поток, в котором происходило взаимодействие с ним.

![](https://github.com/dvaisluk/threaded_server-PY/raw/main/1.png)

2. Реализовать простой чат сервер на базе сервера аутентификации. Сервер должен обеспечивать подключение многих пользователей одновременно, отслеживание имен пользователей, поддерживать историю сообщений и пересылку сообщений от каждого пользователя всем остальным.

![](https://github.com/dvaisluk/threaded_server-PY/raw/main/2.png)
![](https://github.com/dvaisluk/threaded_server-PY/raw/main/3.png)
![](https://github.com/dvaisluk/threaded_server-PY/raw/main/4.png)

2. Реализовать сервер с управляющим потоком. При создании сервера прослушивание портов происходит в отдельном потоке, а главный поток программы в это время способен принимать команды от пользователя. Необходимо реализовать следующие команды:
3. 
![](https://github.com/dvaisluk/threaded_server-PY/raw/main/5.png)
![](https://github.com/dvaisluk/threaded_server-PY/raw/main/6.png)

1. Отключение сервера (завершение программы);

![](https://github.com/dvaisluk/threaded_server-PY/raw/main/7.png)

1. Пауза (остановка прослушивание порта);

![](https://github.com/dvaisluk/threaded_server-PY/raw/main/8.png)
![](https://github.com/dvaisluk/threaded_server-PY/raw/main/9.png)
![](https://github.com/dvaisluk/threaded_server-PY/raw/main/10.png)

1. Показ логов;

![](https://github.com/dvaisluk/threaded_server-PY/raw/main/11.png)

1. Очистка логов;

![](https://github.com/dvaisluk/threaded_server-PY/raw/main/12.png)

1. Очистка файла идентификации.

![](https://github.com/dvaisluk/threaded_server-PY/raw/main/13.png)
![](https://github.com/dvaisluk/threaded_server-PY/raw/main/14.png)

