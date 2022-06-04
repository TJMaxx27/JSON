# JSON
1. Создать внешний репозиторий c названием JSON.
```bash
New --> Repository name "JSON" --> Public --> add README file --> Create repository 
```
2. Клонировать репозиторий JSON на локальный компьютер.
```bash 
git clone + link repository && cd JSON
```
3. Внутри локального JSON создать файл “new.json”.
```bash 
touch new.json
```
4. Добавить файл под гит.
```bash 
git add new.json
```
5. Закоммитить файл.
```bash 
git commit -m "Version 1.0"
```
6. Отправить файл на внешний GitHub репозиторий.
```bash 
git push
```
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```bash 
vim new.json --> i --> text --> ESC + :wq
```
8. Отправить изменения на внешний репозиторий.
```bash 
git add new.json && git commit -m 'v.2' && git push
```
9. Создать файл preferences.JSON
```bash 
touch preferences.json
```
10. В файл preferences.JSON” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```bash 
vim touch preferences.json --> i --> text --> :wq
```
11. Создать файл sklls.JSON добавить информацию о скиллах которые будут изучены на курсе в формате JSON
```bash 
touch skills.json && vim skills.json
```
12. Сделать коммит в одну строку.
```bash 
git add . && git commit -m "added file: preferences and skills" 
```
13. Отправить сразу 2 файла на внешний репозиторий.
```bash 
git push	
```
14. На веб интерфейсе создать файл bug_report.JSON.
```bash 
add file --> create new file --> Name your file "bug_report.json"
```
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash 
Click the button "Commit directly to the main branch"
```
16. На веб интерфейсе модифицировать файл bug_report.JSON, добавить баг репорт в формате JSON.
```bash 
Choose bug_report.json --> Edit this file --> Text 
```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash 
Click the button "Commit changes"
```
18. Синхронизировать внешний и локальный репозиторий JSON
```bash 
git pull
```
