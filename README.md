# ansible

Create Freestyle project in jenkins and add following parameters:

target_servers ( Give as Choice parameter and add server choices)
http_host
username
password
mysql_db
mysql_user
mysql_password

Shell command

ansible-playbook -i /home/jenkins/ansible/inventory /home/jenkins/ansible/playbook.yml -e "target_servers=$target_servers http_host=$http_host mysql_db=$mysql_db mysql_user=$mysql_user mysql_password=$mysql_password username=$username password=$password" -u ubuntu -v
