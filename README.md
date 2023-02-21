# Django-Rest-Framework - Escola
Uma simples API utilizando a linguagem Python e Django Rest Framework, além de integrar os dados a um banco de dados.

<h4 align="center"> 
  <a href="#Tecnologias-e-ferramentas">Tecnologias e ferramentas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp; 
  <a href="#Sobre-o-projeto">Sobre o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Demonstração">Demonstração</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  </br>
  <a href="#Como-usar">Como usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Licença">Licença</a>
</h4>

<br/>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>

<div id='Tecnologias-e-Ferramentas'/>

# Tecnologias e ferramentas 

O projeto foi desenvolvido com as seguintes tecnologias e ferramentas:

- [Python 3.7.4](https://www.python.org/downloads/release/python-374/) - linguagem de programação.
- [Django 3.0.7](https://github.com/django/django/releases/tag/3.0.7) - framework para desenvolvimento rápido para web, escrito em Python.
- [Django REST Framework 3.14.0](https://www.django-rest-framework.org/) - kit de ferramentas para construir APIs da Web.
- [Visual Studio Code 1.71.1](https://code.visualstudio.com) - editor de código-fonte.
- [DBeaver 21.3.4](https://dbeaver.io/download/) - ferramenta que tem por objetivo conectar e manipular vários tipos de banco de dados.       

<div id='Sobre-o-projeto'/>

# Sobre o projeto

Este projeto é uma API de uma escola capaz de criar, visualizar, atualizar e deletar tanto alunos quanto cursos; e com isso ser capaz de vincular esses dois recursos, permitindo as matrículas dos alunos. Foram criados os modelos, serializers, viewsets, configuração de urls, vinculação do Admin do Django com a API e inclusão de atuenticação para disponibilizar os recursos. A documentação da API foi gerada tanto pelo Swagger quanto pelo Redoc.

# Demonstração

A figura abaixo mostra a visualização da API padrão.

<p align="center">
  <img src="https://github.com/renanegobbi/django-rest-framework/blob/main/docs/prints/print_django_rest_framework.PNG"/>
</p>

A figura abaixo ilustra a interface da API documentada com Swagger.

<p align="center">
  <img src="https://github.com/renanegobbi/django-rest-framework/blob/main/docs/prints/print_swagger.PNG"/>
</p>

A figura abaixo ilustra a interface da API documentada com Redoc.

<p align="center">
  <img src="https://github.com/renanegobbi/django-rest-framework/blob/main/docs/prints/print_redoc.PNG"/>
</p>

# Como usar

### Preparando o ambiente:

* Instalar o Python:                  
```
https://www.python.org/downloads/release/python-374/
```

* Instalar o Django através do comando:                     
```
pip install Django==3.0.7  
```

* Instalar o Django Rest Framework através do comando:                      
```                    
pip install djangorestframework              
```                         

* Instalar o Markdown através do comando:                        
```
pip install markdown                                                        
```

* Entre na pasta do repositório clonado e crie um ambiente virtual com o seguinte comando:
```
python3 -m venv ./venv 
```

* Ative seu ambiente virtual com o seguinte comando: 
                                           
Para MAC e Linux:
```
source venv/bin/activate
```         

Em caso de Windows, utilize o comando:
```
venv\Scripts\activate.bat
```

* Instale o Django nesse ambiente virtualizado:                        
```
pip install django
```

* Na raiz do projeto, execute o comando para subir o servidor:                        
```
python manage.py runserver
```

* Insira a seguinte url:

Para visualizar pelo browser a API de maneira simples:
```
http://localhost:8000/
```

Para visualizar a API pela documentação do Swagger:
```
http://localhost:8000/swagger/
```

Para visualizar a API pela documentação do Redoc:
```
http://localhost:8000/redoc/
```

# Licença
Este projeto está sob a licença do MIT. Consulte a [LICENÇA](https://github.com/TesteReteste/lim/blob/master/LICENSE) para obter mais informações.
