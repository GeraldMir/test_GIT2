# Основные команды Git по рабое с ветками
Чтобы вывести список всех веток на экран необходимо использовать команду:
>git branch

Чтобы создать новую ветку - мы используем команджу:
> git branch branch_name - без скобочек и кавычек
Для того, чтобы перейти в другую ветку, необходимо ввести команду:
> git checkout <название ветки>

Чтобы создать ветку и сразу перейти в неё, можно ввести команду:
>git checkout -b <название ветки>
Для того, чтобы удалить ветку - необходимо ввести команду (находится необходимо не в удаляемой ветке):
> git branch -d <название ветки>
Для того, чтобы объединить ветки - необходимо ввести команду
:
> git merge <название ветки>

Ветка <название ветки> - добавляется в текущую ветку. В случае появления конфликта (по-разному записаны одинаковые строки) - программа предложит 4 варианта - оставить текущую версию, оставить добавляемую версию, объединить версии файла и сравнить версии файла (визульно подсвечиваются отличия)

Для того, чтобы вывести на экран историю всех веток и их коммитов, необходимо ввести команду (будет также визульное графическое отображение ветвления)
:
> git log --graph
