# Рубежный контроль

1.
```sh
 Тремя:
  $ cd ..
  $ cd ~
  $ cd home/user
```
2.
```sh
 $ grep -lRv "aaa"  //где "ааа" - подстрока
```
3.
```sh
  $ mkdir ~/workspace/test | cd ~/workspace/test
  $ touch text.txt
```
4.
```sh
  $ tar -cf archive.tar test.txt
```
5.
```sh
  $ grep -Rl 'aaa&&bbb'
```
6.
```sh
  $ ls -d -L 1
```
7.
```sh
  $ du -ahx ~ | sort -rh | head -20 //выведет 20 самых больших файлов
```
## Вторая часть
1.
```sh
  $ git init  
  $ git clone <url>
```
2.
```sh
   Будет зафиксирована версия файла с изменением 1
```
3.
```sh
 patch1 -> master
```
4.
```sh
  patch1 -> master 
```
5.
```sh
  Выдасть ошибку при сливании двух разных файлов в одной ветке у того, кто запушит ошибку
```
6.
```sh
  Это выглядит так:
  <<<<<<< HEAD
<<<<<<< ours
  getline(std::cin, str); 
  std::cout<< "Hello world  from "<< str <<endl; // Вывод должен выглядеть: Hello world for <name>
@@ -14,6 +15,11 @@ main(int argc, char** argv)
  std::cout << "Hello world  from " << str
            << endl; // out'll be: Hello world <name>
>>>>>>> theirs
 Т.е. Git помечает файл как конфликтный и не дает 'замержить'
```
## Часть №3
1.
```sh
В каталоге должен присутсвовать файл CMakeLists.txt
```
