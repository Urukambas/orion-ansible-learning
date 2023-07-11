## Команды, которые были пройдены
Проверка перед запуском Playbook:
```SHELL
ansible-playbook playbook.yaml --check
```
Проверка изменения (поддерживается не всеми модулями):
```SHELL
ansible-playbook playbook.yaml --diff
```
Можно использовать совместно:
```SHELL
ansible-playbook playbook.yaml --check --diff
```