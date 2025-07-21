Создание файла `lab2.bash`, запуск его и вывод верного результата:

<img width="579" height="49" alt="Screenshot 2025-07-21 at 18 23 15" src="https://github.com/user-attachments/assets/476126b6-e08b-4c37-a520-fe1cf154f870" />

Скрипт в файле `lab2.bash`:

<img width="602" height="186" alt="Screenshot 2025-07-21 at 18 21 40" src="https://github.com/user-attachments/assets/767b0d49-e964-4957-a7b6-a84d86cdfd3b" />

Объяснение используемых функций:
- `#!/bin/bash` shebang, скрипт должен исполняться /bin/bash
- `ip=$1` сохраняет первый аргумент командной строки в переменную ip
- `IFS` internal field separator. теперь точка-разделитель
- `read -r o1 o2 o3 o4` читает строку и разделяет ее на 4 переменные
