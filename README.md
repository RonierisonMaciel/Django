# Iniciando um projeto e uma aplicação utilizando o framework Django

<br>

## Estruturação do Projeto
---

<details>
<summary>Passo a passo</summary>

```bash
python3 -m venv .venv
```

```bash
source .venv/bin/activate
```

```bash
pip install -r requirements.txt
```

```bash
django-admin startproject config .
```

```bash
django-admin startapp application
```

```bash
touch application/urls.py
```

```bash
mkdir application/templates
```

```bash
touch application/templates/index.html
```

```bash
touch application/templates/contato.html
```
</details>

<br>

## Execução da aplicação
---

<details>
<summary>Passo a passo</summary>

1. Crie o ambiente virtual

```bash
python3 -m venv .venv
```

2. Ative o ambiente virtual

```bash
source .venv/bin/activate
```

3. Instale os requerimentos para a aplicação

```bash
pip install -r requirements.txt
```

4. Crie a migrações necessárias

```bash
python3 manage.py makemigrations
```

5. Realize as migrações

```bash
python3 manage.py migrate
```

6. Rode a aplicação

```bash
python3 manage.py runserver
```

</details>

<br>
<br>
