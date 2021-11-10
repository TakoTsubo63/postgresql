## INSTALL PostgreSQL  
  
#### Описание:  
  
В данном репозитории хрантся изменения Ansible playbook по установке PostgreSQL.  
  
#### Использованные технологии:  
  
Ansible  
  
#### краткое описание использования:  
  
данный репозиторий используется Jenkins для установки, на виртаульную машину AWS,  
пакета с программи для запуска PostgreSQL  
  
#### описание содержимого директории:  
  
**group_vars** - директория содержит имя user для виртуальной машины с PostgeSQL  
**roles** - директория roles содержит роли для ansible playbook  
**ansible.cfg** - файл конфигурации ansible  
**host_postgres** - это inventory файл, содержащий значение url виртуальной машины  
 на которую будет установлен PostgreSQL  
**main.yml** - сам playbook ansible  
