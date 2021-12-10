# wsrskillscloudmoscow-Savinov
Для правильной работы необходимо подхватить скрипт базовой настройки сервера Deploy
git clone https://github.com/BloodmasterIV/wsrskillscloudmoscow-Savinov/ /base
/base/BaseScript.sh
Далее можно запустить
ansible-playbook /base/WsrAnsiblePlaybook.yml
Для настройки сайта, можно запустить
ansible-playbook /base/WsrAnsibleWebPlaybook

