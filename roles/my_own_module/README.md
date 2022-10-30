Role Name
=========

Роль для тестирования `my_own_module`

Role Variables
--------------

`test_file` - имя тестового файла
`test_content` - данные для заполнения в `test_file`

Example Playbook
----------------

```yaml
---
- hosts: all
  roles:
    - my_own_module:
      path: 'test_path'
      content: 'test string'
```
