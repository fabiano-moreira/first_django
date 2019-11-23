# first_django

Projeto simples em Django.

Feito com base no tutorial do rg3915.

Segue o github dele e o video no Youtube:

[rg3915/django-simples](https://github.com/rg3915/django-simples)

[Django: projeto simples ](https://www.youtube.com/watch?v=DEhzECzf7_g&t=305s)

1 - Clone esse repositório;

```
https://github.com/fabiano-moreira/first_django

```

2 - Crie um ambiente virtual para instalar os pacotes e não misturar com a estrutura do seu sistema* Ative o virtualenv;

```
$ cd first_django
$ python3 -m venv .venv
$ source .venv/bin/activate
```

3 -  Instale as dependências;

```
(.venv)$ pip install -r requirements.txt

```

4 - Rode as migrações:

```
(.venv)$ python contrib/env_gen.py
(.venv)$ python manage.py migrate

```