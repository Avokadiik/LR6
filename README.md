# LR6
Лабораторная работа №6
Шаги выполнения
1. Создание аккаунта на GitHub
 

2. Fork репозитория
 

3. Установка Git


4. Настройка Git
Настроен клиент git:
git config --global user.name "В3441 <Башкиров Д.В."
git config --global user.email "daniaivanov10@gmail.com"


5. Клонирование репозитория
git clone https://github.com/Avokadiik/LR6.git


6. Добавление файла через интерфейс GitHub и подтяжка его в локальный репозиторий
git pull

  
7. Получение истории операций
История операций для каждой ветки получена:

git log


8. Просмотр последних изменений
git diff


9. Слияние в ветку master и разрешение конфликта
git merge branch1
    

10. Удаление побочной ветки
git branch -d branch1


11. Фиксация изменений
git add .
git commit -m "comment"


12. Откат коммита
git reset --hard HEAD~1


13. Создание ветки для отчёта
git checkout -b report


15. Оформление отчёта


16. История операций
git log --pretty=format:"%h %ad %an %s" --date=short


Лог команд
