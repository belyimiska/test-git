# test-git
Основные команды:
1. git status - проверяет статус файла
2. git add files names. или git add . - чтобы добавить все файлы проекта. git add - добавляет файлы в stage (промежуточная область). файл подсвечивается зеленым, если он добавлен в stage
3. git commit -m "коммент (какую работу сделали)" - производит запись изменений 
4. git log - показывает полную информацию о записях (коммитах)
git log --oneline - показывает краткую информацию о записях (коммитах)
5. git push [rep_link (ссылка на репозиторий)] [branch_name (название ветки)] - отправляет файлы/изменения на гитхаб

Дополнительные команды:
1. git reset - позволяет удалить некоторые файлы из промежуточной области (stage)
2. git diff - пзволяет просмотреть измененные или добавленные строки. можно добавить название файла и посмотреть изменения конкретно по нему
3. git reset --hard - откатывает изменения назад до последнего git commit