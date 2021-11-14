# Projeto e-diarista

## Instando o projeto

### Clonar o projeto

`git clone https://github.com/helitonns/backend-ediarista.git`

### Instalar as dependências

`pip install -r requiriments.txt`

### Alterar os valores das variáveis de ambiente no arquivo `/ediarista/.evn`

```
SECRET_KEY= ...
DEBUG=True
DATABASE_NAME=...
DATABASE_HOST=...
DATABASE_PORT=...
DATABASE_USER=...
DATABASE_PASSWORD=...
EMAIL_HOST_USER=...
EMAIL_HOST_PASSWORD=...
```

### Migrar o banco de dados

`python manage.py migrate`

### Iniciar o servidor

`python manage.py runserver`
