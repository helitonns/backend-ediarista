# Projeto e-diarista

## Instando o projeto
### Clonar o projeto
`git clone https://github.com/helitonns/backend-ediarista.git`

### Instalar as dependências
`pip install -r requiriments.txt`
### Alterar configurações do BD no arquivo `settings.py`

```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql_psycopg2',
        'NAME': 'nome-do-db',
        'HOST': 'host-do-db',
        'PORT': 'porta-do-db',
        'USER': 'usuario-do-db',
        'PASSWORD': 'senha-do-db'
    }
}
```
### Migrar o banco de dados
`python manage.py migrate`

### Iniciar o servidor
`python manage.py runserver`

