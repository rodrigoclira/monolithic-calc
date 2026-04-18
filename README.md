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

Para executar a aplicação no servidor de desenvolvimento, use o comando `runserver`
```
python manage.py runserver
```

Se estiver executando na AWS, use ``python manage.py runserver 0.0.0.0:8080`` ou alguma outra porta que esteja acessível. 

<img width="891" height="247" alt="image" src="https://github.com/user-attachments/assets/3ab728b6-b8e0-484e-8448-84eb7386a2cd" />


Os endpoints disponíveis no código são: 
- http://DNS_AWS:PORTA/api/calc
- http://DNS_AWS:PORTA/api/soma
- http://DNS_AWS:PORTA/api/sub

Lembre-se que os endpoints soma e sub possuem variáveis como entrada (`op1` e `op2`)
<img width="462" height="109" alt="image" src="https://github.com/user-attachments/assets/3bc9cfa2-d306-4952-86ef-31f009f20244" />
