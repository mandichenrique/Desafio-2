Este é uma automação para criação e configuração
do wordpress em bases Ubuntu com Nginx.

Para utilizar são necessarias 3 passos, sendo eles: Consigurar o IP no hosts e
no server_hostname e, Group_vars, e rodar o comando na pasta raiz.

ansible_playbook playbook.yml -i hosts