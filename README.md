# Homework

1. Скачайте библиотеку *boost* с помощью утилиты **wget**. Адрес для скачивания `https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz`.
2. Разархивируйте скаченный файл в директорию `~/boost_1_69_0`
3. Подсчитайте количество файлов в директории `~/boost_1_69_0` **не включая** вложенные директории.
4. Подсчитайте количество файлов в директории `~/boost_1_69_0` **включая** вложенные директории.
5. Подсчитайте количество заголовочных файлов, файлов с расширением `.cpp`, сколько остальных файлов (не заголовочных и не `.cpp`).
6. Найдите полный пусть до файла `any.hpp` внутри библиотеки *boost*.
7. Выведите в консоль все файлы, где упоминается последовательность `boost::asio`.
8. Скомпилирутйе *boost*. Можно воспользоваться [инструкцией](https://www.boost.org/doc/libs/1_61_0/more/getting_started/unix-variants.html#or-build-custom-binaries) или [ссылкой](https://codeyarns.com/2017/01/24/how-to-build-boost-on-linux/).
9. Перенесите все скомпилированные на предыдущем шаге статические библиотеки в директорию `~/boost-libs`.
10. Подсчитайте сколько занимает дискового пространства каждый файл в этой директории.
11. Найдите *топ10* самых "тяжёлых".

## Реализация

1)
![image](https://user-images.githubusercontent.com/92674699/156945930-7ebf9b36-9c38-4db5-8b68-4794b9ed153a.png)

2)
> tar -xvf /home/imdmitry/boost_1_69_0.tar.gz

3, 4)

![image](https://user-images.githubusercontent.com/92674699/156945973-d74ab67c-c851-4b17-b889-bb4f6a667625.png)

5)
![image](https://user-images.githubusercontent.com/92674699/156945990-fed91447-50dd-4981-bb01-691c1e8058f5.png)
![image](https://user-images.githubusercontent.com/92674699/156945996-444a7531-0c5d-414b-a3dd-709a17b4dbf7.png)

6)
![image](https://user-images.githubusercontent.com/92674699/156946006-c59a94d3-b96f-4b3b-b08b-537056828215.png)
![image](https://user-images.githubusercontent.com/92674699/156946012-9e089cb8-08d6-4e07-9da2-8162d2e4e9e2.png)

7)
![image](https://user-images.githubusercontent.com/92674699/156946027-c366cc28-0035-4faf-98b0-6a9f5acafbb9.png)
-l – вывод только файлов с совпадением а не все строчки файла 
-r – рекурсивный поиск

8)
![image](https://user-images.githubusercontent.com/92674699/156946037-15f26b08-0a03-460e-909e-f1f084b86740.png)
![image](https://user-images.githubusercontent.com/92674699/156946038-3478c5f0-6644-44b1-b95d-2d02d88a4832.png)

9)
> mv /home/imdmitry/boost_1_69_0/boost_1_69_0/tools/build/boots /home/imdmitry/boost_1_69_0/boost_1_69_0/boost-libs

10)
![image](https://user-images.githubusercontent.com/92674699/156946070-13f5885f-6315-4b65-a422-070ef670c33f.png)

11)
![image](https://user-images.githubusercontent.com/92674699/156946074-f83eb3f6-d265-4f19-8d6e-bf1e93ad32ba.png)
