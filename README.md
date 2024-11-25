# Лабораторная работа №6
## Шаги выполнения
---
### 1. Создание аккаунта на GitHub
![](PrtSc/12.png)

### 2. Fork репозитория
![](PrtSc/13.png) 

### 3. Установка Git
![](PrtSc/1.png)

### 4. Настройка Git
```bash
git config --global user.name "В3441 <Башкиров Д.В."
git config --global user.email "daniaivanov10@gmail.com"
```
![](PrtSc/1.1.png)

### 5. Клонирование репозитория
```bash
git clone https://github.com/Avokadiik/LR6.git
```
![](PrtSc/2.png)

### 6. Добавление файла через интерфейс GitHub и подтяжка его в локальный репозиторий
```bash
git pull
```
![](PrtSc/2.2.png)

### 7. Получение истории операций
```bash
git log
```
![](PrtSc/3.png)

### 8. Просмотр последних изменений
```bash
git diff
```
![](PrtSc/3.png)

### 9. Слияние в ветку master и разрешение конфликта
```bash
git merge branch1
```   
![](PrtSc/4.png)
![](PrtSc/5.png)
![](PrtSc/6.png)

### 10. Удаление побочной ветки
```bash
git branch -d branch1
```
![](PrtSc/7.png)

### 11. Фиксация изменений
```bash
git add .
git commit -m "comment"
```
![](PrtSc/8.png)

### 12. Откат коммита
```bash
git reset --hard HEAD~1
```
![](PrtSc/9.png)

### 13. Создание ветки для отчёта
```bash
git checkout -b report
```
![](PrtSc/11.png)

### 14. Оформление отчёта
Скриншоты помещены в папку PrtSc.

### 15. История операций
```bash
git log --pretty=format:"%h %ad %an %s" --date=short
```
![](PrtSc/10.png)

### Лог команд
```bash
git clone https://github.com/Avokadiik/LR6.git
git pull
git log
git diff
git merge branch1
git branch -d branch1
git add .
git commit -m "comment"
git reset --hard HEAD~1
git checkout -b report
git log --pretty=format:"%h %ad %an %s" --date=short
git push
```
