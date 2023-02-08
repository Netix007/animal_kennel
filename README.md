# animal_kennel

# __Итоговая аттестация__

## Задание 1
- Используя команду cat в терминале операционной системы Linux, создать
два файла: Домашние животные (заполнив файл собаками, кошками,
хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и
ослы), а затем объединить их. Просмотреть содержимое созданного файла.
Переименовать файл, дав ему новое имя (Друзья человека).

_Список команд для выполнения задания:_
```
cat > Домашние_животные.txt
собаки, кошки, хомяки
(для сохранения и выхода нажать Ctrl+D)

cat > Вьючные_животные.txt
лошади, верблюды, ослы
(для сохранения и выхода нажать Ctrl+D)

cat Домашние_животные.txt Вьючные_животные.txt > test.txt

cat test.txt

mv test.txt Друзья_человека.txt
```
## Задание 2
- Создать директорию, переместить файл туда.

_Список команд для выполнения задания:_
```
mkdir Animals
mv Друзья_человека.txt Animals/
```
