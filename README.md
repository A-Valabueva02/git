# 📌 git

Git — это система контроля версий, доступная на компьютере, что позволяет легко разветвлять и объединять. В то же время GitHub значительно упрощает использование Git для контроля версий и совместной работы отдельными людьми и командами

Хочу поделиться некоторыми командами git, которые использовала для создания своего портфолио на GitHub.

## Задание 1

##### Создание, клонирование, отправка и извлечение репозиториев  
```git
git init A-Valabueva02                                       # Создайте репозиторий с тем же именем, что и ваше имя пользователя
git clone git@github.com:A-Valabueva02/A-Valabueva02.git      # Клонируйте репозиторий на своем компьютере в отдельную папку
git clone git@github.com:testrusau/testrusau.git            # Клонируйте github.com/testrusau/testrusau на своем компьютере в отдельную папку
cd testrusau                                               # Переносим данные из репозитория testrusau в свой собственный
git push git@github.com:A-Valabueva02/testrusau.git master:main
git commit -m "commited change description"                 # Откройте файл README.md и замените каждый блок отдельным коммитом
git push

```
## Задание 2

##### Создание, добавление удаленных репозиториев
```git
git init sql                                                # Создайте отдельный репозиторий для элемента портфолио
git remote add sql https://github.com/A-Valabueva02/sql.git  # Объявляем репозиторий удаленно
README.md edited manually                                   # Добавьте ссылки на ваши репозитории в файл README.md
git commit -m "commited change description"                 # Отправляем изменения в удаленный репозиторий
git push                                                     


```
