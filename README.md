# LB4
изучить назначение распределённой системы управления версиями, освоить процесс создания репозитория и основы управления версиями файлов.
Выполнил: Горохов Кирилл Александрович

Основные команды git:
1) git init - создает в папке гит репозиторию.
2) git config user.name - создает имя автора изменений (локальные, на уровне проекта).
3) git config user.email - создает почту атвора изменеий (локальные, на уровне проекта).
4) git config --global user.name - создает имя атвора изменеий (глобальные, на уровне пользователя) // нужно что бы измения .применялись ко всем проектам текущего пользователя.
5) git config --global user.email - создает почту атвора изменеий (глобальные, на уровне пользователя).
6) cat .git/config - просмотр дирректории гит.  
7) git config --unset user.name - удаляет локальные параметры (имя пользователя).
8) git config --unset user.email - удаляет локальные параметры (почту пользователя) // тоже самое с флагом --global для. уровня пользователя. 
9) git config --list - выводит список значений параметров кофигураций // с флагом --global для уровня пользователя.
10) git config --global alias.c config - создает псевдоним для команды (git config).
12) gti config --global core.editor ''.
13) git config -h - выводит все команды config и их описание.
14) git help config - выводит подробную информацию о комманде config. 
15) git status - выводит "взгляд со стороны гит" // неотслежимаемые файлы помечаются как "Untracked files".
16) git add "название файла" - проиндексирование файла (отслеживание).
17) git commit - добавление файла в репозиторий.  