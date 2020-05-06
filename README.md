# Storex
Loja Virtual de Stickers

(Em breve link do projeto em uma hospedagem)

##Tecnologias Utilizadas
- Front-end: Angularjs
- Back-end: Django
- Database: MySQL

##Requisitos para rodar o projeto
- Python (testado a partir da v. 3.8.2);
- Django (testado a partir da v. 3.0.5);
- PIP (testado a partir da v. 20.1);
- MySQL Server (testado a partir da v. 8.0.19);
- [MySQL client for python (testado a partir da v. 1.4.6)](https://www.lfd.uci.edu/~gohlke/pythonlibs/);
- Python Decouple: `pip install python-decouple`
- Nodejs (testado a partir da v. 12.16.1)
- Npm (testado a partir da v. 6.13.4)
- Angular (testado a partir da v. 9.1.0)

##Estrutura
O projeto está dividido em 2 módulos separados (backend e frontend), onde os 2 serviços rodam em portas diferentes e se
comunicam através da política de CORS

##Instalando o  projeto
###Frontend

###Backend
No diretório `backend`, faça uma cópia do arquivo `.env.example`, renomeie-o para `.env` e edite-o com os dados de acesso
do seu banco de dados. 

Após isso, basta rodar o seguinte comando no terminal, na mesma pasta:
>python manage.py migrate

##Rodando o projeto
Utilize os seguintes comandos, em 2 terminais diferentes: 


|             |  Angular   |    Django                   |
| :---        |  :---:     |          :---:              |
| Diretório   | frontend   | backend                     |
| Comando     | `ng serve` | `python manage.py runserver`|

