# git common commands🖇️
##### I present a set of basic commands that allowed me to create a portfolio on GitHub.
## Task 1
#### Creating, cloning, pushing and pulling repositories  
```git
git init leonidzhuravlev                                          # Создать свой репозиторий в таким же именем, как и имя пользователя 
git clone git@github.com:leonidzhuravlev/leonidzhuravlev.git      # Склонировать его на свой компьютер в отдельную папку
git clone git@github.com:testrusau/testrusau.git                  # Склонировать себе следующий репозиторий в отдельную папку https://github.com/testrusau/testrusau
cd testrusau                                                      # Запушить данные из репозитория artichokeee в ваш репозиторий из шага 2
git push git@github.com:leonidzhuravlev/testrusau.git main:main
git commit -m "commited change description"                       # Открыть файл README.md и поочередно заменить каждый блок на вашу информацию. Каждое изменений блока сделать через отдельный коммит.
git push 

```
## Task 2
#### Creating, adding remote repositories  
```git
git init sql                                                      # Поочередно создать репозитории для каждого выполненного задания по прошедшим модулям и загрузите туда ваши решения ДЗ
git remote add sql https://github.com/leonidzhuravlev/7_bash .git # Cоздать локальный репозиторий на компьютере + объявить его удаленно
README.md edited manually                                         # Добавить ссылку к репозиторию к файлу README.md 
git commit -m "commited change description"                       # Запушить изменения на удаленный репозиторий
git push                                                     

```
