1. Прописать IP адрес хоста, которым будем управлять  в:
    hosts
2. Прописать имя пользователя и путь к ключу. 
Логины и ключи в каталоге:
    group_vars
3. Список доверенных IP для доступа по SSH в :
    defaults/main.yml
4. Запуск:
    ansible-playbook  playbook.yaml  -i hosts  -vD
    