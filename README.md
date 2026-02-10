# O que é o projeto?

Este projeto é uma aplicação web desenvolvida em Django, voltada para o gerenciamento de um repositório acadêmico. A plataforma permite o cadastro de usuários, organização dos trabalhos e controle de acesso, possibilitando uma melhor gestão das produções científicas da instituição.

# Instalação de dependências

### Requisitos
- [Python 3.1 ou acima.](https://www.python.org/downloads/)
- [Pycharm](https://www.jetbrains.com/pycharm/download/) ou outro editor de codigo.
 
### Instalação do Django

 - No terminal do PyCharm (ou em um terminal comum do seu Sistema Operacional), execute:
 
    `pip install django`

# Rodando o servidor local

### Aplicar migrations para rodar o banco de dados:
`python manage.py migrate`  

### Criar superadmin:
`python manage.py createsuperuser`

  No terminal apareceram os campos para definir: usuário, e-mail e senha.

### Executar servidor:

`python manage.py runserver`

*Apos isso para acessar o programa entre em:* http://127.0.0.1:8000/

## Observação Importante

Muitas vezes ao trocar de máquina ou apagar o projeto, os dados do banco de dados não são preservados, incluindo o usuário administrador. Nesses casos, será necessário executar novamente
` python manage.py migrate ` e
` python manage.py createsuperuser `
Exibindo Oq falta no sistema.txt.
