Install: 
 



`ansible-playbook -i hosts -b -e ansible/vars.yml playbook.yml`

`ansible-playbook -i hosts -b -e ansible/vars.yml playbook.yml --ask-become-pass`





If use mariadb, pls check link :

 Set username/password for current server

 https://stackoverflow.com/questions/42511474/check-mk-installation-failed-dependencies-mariadb-python-reportlab-libgsf/42550101#42550101





Something have to do manually: 