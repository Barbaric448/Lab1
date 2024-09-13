После установки Linux Ubintu можно сразу приступать к выполнению задания.

1. Открываю терминал комбинацией клавиш **Ctrl+Alt+T**:
<p>
  <img width='600px' height='350px' src='scr1.png'>
</p>


2. Для создания файла использую команду *touch*, "script.bash" - название файла:
<p>
  <img width='600px' height='350px' src='scr2.png'>
</p>

Файл создан и готов к работе. Чтобы убедиться в этом, достаточно открыть головную директорию:
<p>
  <img width='600px' height='350px' src='scr3.png'>
</p>

3. Теперь млжно начинать писать код, для этого в терминале пишу *"gedit script.bash"*, но вижу ошибку:
<p>
  <img width='600px' height='350px' src='scr4.png'>
</p>

Оказалось, у меня не установлен редактор Gedit. Тогда использую команду, которую подсказал мне терминал:
<p>
  <img width='600px' height='350px' src='scr5.png'>
</p>

Gedit установлен и готов к работе, открываю файл.

4. Написание и тест первого скрипта:
<p>
  <img width='800px' height='150px' src='scr6.png'>
</p>
<p>
  <img width='600px' height='350px' src='scr7.png'>
</p>
Отлично! Все работает!

5. Теперь создам скрипт, который будет выводить **"Welcome, *x* *y* *z*.."** при запуске в виде
```bash
bash script.bash x y z
```

Для ознакомоения с базовыми командами терминала я воспользовался [этим сайтом](https://habr.com/ru/companies/ruvds/articles/326328/)
<p>
  <img width='850px' height='200px' src='scr8.png'>
</p>
Теперь проверка:
<p>
  <img width='850px' height='200px' src='scr9.png'>
</p>
Как видно, скрипт успешно справляется с любым кол-вом переданных аргуметов.


На этом можно завершить работу. Задание выполнено успешно.
