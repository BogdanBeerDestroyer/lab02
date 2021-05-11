# Лабораторная 2. Шумилишский Богдан. ИУ8-22.
## Часть 1
### Задание 1
Ссылка на репозиторий:
```https://github.com/BogdanBeerDestroyer/for-lab02.git```
### Задание 2
Инструкцию не нашел, но вот, как я сделал первый комит(За одно его и запушил):
```
1. mkdir for-lab02
2. git init
3. git checkout -b master
4. touch test.txt
5. git add test.txt
6. git commit -m "Added test.txt"
7. git push origin master
```
### Задание 3, 4
```touch hello_world.cpp``` <br>
```git add hello_world.cpp```<br>
Написал код
### Задание 5
```git commit -m "Added hello_world.cpp"```
### Задание 6
Ну тут я просто переписал код через clion
### Задание 7
```git commit -am "hello_world.cpp was changed"``` <br>
Здесь я пользуюсь ```-a```
### Задание 8
```git push origin master```
### Задание 9
Комиты на месте.
## Часть 2
### Задание 1
```git checkout -b patch1```
### Задание 2
Внёс изменения
### Задание 3
```
git commit -am "hello_world.cpp was corrected"
git push origin patch1
```
### Задание 4
Ветка доступна на гитхабе.
### Задание 5
Сделал пул реквест
### Задание 6
Добавил комментарии 
### Задание 9
```
git commit -am "Added comments to hello_world.cpp"
git push origin patch1
```
### Задание 8
Изменения появились в пул реквесте
### Задание 9
Слил ```patch1->master``` и удалил ```patch1```
### Задание 10
```git pull origin master```
### Задание 11
Посмотрел лог
### Задание 12
```git branch -D patch1```
## Часть3
### Задание 1
```git checkout -b patch2```
### Задание 2
```clang-format -i -style=Mozilla hello_world.cpp```
### Задание 3
```
git commit -am "Clang-format"
git push origin patch2
```
Сделал пул реквест
### Задание 4
Поменял комментарии
```
git commit -am "Comments translated"
git push origin master
```
### Задание 5
Конфликты есть
### Задание 6
```
git checkout master
git pull origin master
git checkout patch2
git rebase master
```
Заходим в ide и исправляем конфликты вручную
```
git add hello_world.cpp
git rebase --continue
 ```
### Задание 7
```git push -f origin patch2```
### Задание 8
Конфликтов больше нет
### Задание 9
Делаем мердж на удаленном репозитории. <br>
Вмерджить на локальном можно так:
```
git checkout master
git merge patch2
```
