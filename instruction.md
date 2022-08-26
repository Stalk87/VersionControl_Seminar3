## 1. Что такое Git?

Git - это одна из реализаций распределённых систем контроля версий, имеющая как локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире. 

## 2. Подготовка репозитория

Для создания репозитория необходимо выполнить команду *git init* в папке с репозиторием

## 3. Git add

Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add*, напишите *git add <имя_файла>*

## 4. Создание коммитов

Для того, чтобы создать коммит (сохранение), необходимо выполнить команду *git commit -m "Сообщение"*

## 5. Создание ветки

Для того, чтобы создать ветку, нужно использовать *git branch <имя_ветки>* или *git checkout -b <имя_ветки>*

## 6. Переход между ветками

Чтобы перейти из одной ветки в другую необходимо использовать команду *git checkout <имя_ветки>*

## 7. Слияние веток

Для того, чтобы слить ветки необходимо перейти в ту ветку в которую будем сливать изменения и выполнить команду *git merge <имя_ветки_из_которой_сливаем_изменения>*

## 8. Удаление ветки

Для того, чтобы удалить ветку, нужно использовать *git branch -d <имя_ветки>*

## 9. Просмотр древа

Чтобы посмотреть древо коммитов необходимо выполнить комманду *git log --graph*

## 10. .gitignore

Чтобы добавить какой то файл в исключения необходимо в корневике создать файл *.gitignore* и в нем прописать название файла, который необходимо игнорировать

## 11. Клонирование репозитория

Чтобы клонировать удаленный репозиторий себе на компьютер выполнить команду *git clone <адрес репозитория>*

## 12. Отправить изменения в удаленный репозиторий

Чтобы отправить изменения в удаленный репозиторий выполнить команду *git push*

## 13. Забрать изменения с удаленного репозитория

Чтобы отправить изменения в удаленный репозиторий выполнить команду *git pull*

## 14. Создание копии чужого открытого репозитория в своем акке github

Жмем *fork* в чужом репозитории, далее в модальном окне кнопку *create fork*