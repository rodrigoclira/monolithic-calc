# Projeto com Arquitetura Monolítica (Django) 


## Pré-requisitos
| Instalar dependências informadas no arquivo 'requirements.txt' 


Criando e ativando um ambiente virtual chamado `venv`
```
python3 -m venv venv
source venv/bin/activate
```

Instalando o arquivo de requirements do projeto
```
pip3 install -r requirements.txt
```

Realizando as migrações
```
python manage.py makemigrations
python manage.py migrate
```

Rodando o servidor
```
python manage.py runserver 0.0.0.0:8000
```

Caso a porta 8000 não esteja disponível, execute na porta 80 seguinto os comandos abaixos:
```
sudo su
source venv/bin/activate
python manage.py runserver 0.0.0.0:80

```

Endpoints disponíveis
- http://DNS_AWS:PORTA/api/calc
- http://DNS_AWS:PORTA/api/soma
- http://DNS_AWS:PORTA/api/sub

