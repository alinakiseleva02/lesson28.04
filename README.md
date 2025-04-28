## Cоздание
1) Создали репозиторий:
git init
2) Связали с удаленным репозиторием:
git remote add origin https://github.com/alinakiseleva02/lesson28.04.git 
3) Создали файл:
touch less
4) Открыли директорий(папку) в explorer:
explorer .
5) Добавили изменения в stage и закоммители:
git add .
git commit "random file"
6) Запушили на удаленный репозиторий:
git push -u origin master
## Ошибки
У меня не пушились изменения. Чтобы это исправить, я прописал:
git config user.name "Alina"
git config credentials.username "alinakiseleva02"
  
