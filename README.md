# HANGMAN - игра "Виселица"
Консольная версия знаменитой игры ["Виселица"](https://ru.wikipedia.org/wiki/Виселица_(игра)), написанная на языке [Ruby](https://ru.wikipedia.org/wiki/Ruby).

#### Правила:

Программа "загадывает" слово, оно является именем существительным, нарицательным в именительном падеже единственного числа, либо множественного числа при отсутствии у слова формы единственного числа. Игрок вводит предполагаемую букву. Если такая буква есть в слове, то она отображается столько раз, сколько она встречается в слове. Если такой буквы нет, то к виселице добавляется часть туловища. Игрок побеждает в случае, если отгадал слово, не допустив при этом более 6-ти ошибок.

#### Инструкция по запуску:
1. Склонируйте репозиторий
```
$ git clone git@github.com:phobco/hangman.git
```
2. Установите необходимые приложению гемы
```
$ bundle
```
3. Запустите файл **main.rb**
```
$ bundle exec ruby main.rb
```
## Добавление собственных слов в игру:
Свои слова вы можете добавлять в файл `words.txt`, лежаший в папке `data`.

##### Внимание!
На одной строке может находится только одно слово.
