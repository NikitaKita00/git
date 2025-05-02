# Основные команды терминала

Этот файл содержит примеры использования базовых команд Linux/macOS.

## 1. `cd` — переход в директорию
```bash
cd ~/Documents         # Перейти в папку Documents в домашней директории  
cd ..                  # Перейти на уровень выше (в родительскую папку)  
cd /var/www            # Перейти в абсолютный путь /var/www  
cd -                   # Вернуться в предыдущую директорию  
2. ls — вывод содержимого директории
bash
ls                     # Показать файлы и папки в текущей директории  
ls -l                  # Подробный вывод (права, владелец, размер)  
ls -a                  # Показать скрытые файлы (начинаются с точки)  
ls /etc                # Показать содержимое папки /etc  
3. pwd — показать текущую директорию
bash
pwd                    # Выведет что-то вроде: /home/user/projects  
4. mkdir — создание директории
bash
mkdir new_folder       # Создать папку "new_folder" в текущей директории  
mkdir -p dir1/dir2     # Создать вложенные папки (если dir1 не существует)  
5. touch — создание файла
bash
touch file.txt         # Создать пустой файл file.txt  
touch index.html app.js  # Создать несколько файлов  
6. cp — копирование файла
bash
cp file.txt backup/    # Скопировать file.txt в папку backup/  
cp -r folder1 folder2  # Рекурсивное копирование папки (вместе с содержимым)  
7. mv — перемещение или переименование
bash
mv old.txt new.txt     # Переименовать old.txt в new.txt  
mv file.txt ~/Downloads # Переместить file.txt в папку Downloads  
mv dir1/ /tmp/         # Переместить папку dir1 в /tmp  
8. cat — чтение файла
bash
cat file.txt           # Вывести содержимое file.txt в терминал  
cat file1.txt file2.txt > combined.txt # Объединить два файла в один  
9. git init — инициализация Git-репозитория
bash
git init               # Создать новый репозиторий в текущей папке  
git init --bare        # Создать "голый" репозиторий (для сервера)  
10. Удаление (rm, rmdir, rm -r)
bash
rm file.txt            # Удалить файл file.txt  
rm -i *.log            # Удалить все .log файлы с подтверждением (-i)  
rmdir empty_folder     # Удалить пустую папку  
rm -r old_project      # Удалить папку old_project и всё внутри (рекурсивно)  
rm -rf node_modules/   # Принудительное удаление без подтверждения (осторожно!) 