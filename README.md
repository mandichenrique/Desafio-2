Este é uma automação para criação e configuração
do wordpress em bases Ubuntu com Nginx.

Para utilizar são necessarias 3 passos, sendo eles: Consigurar o IP no hosts e
no server_hostname em Group_vars ( Onde pode ser o seu domain name) e rodar o comando na pasta raiz.

ansible_playbook playbook.yml -i hosts
