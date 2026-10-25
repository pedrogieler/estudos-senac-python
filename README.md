# Estudos Senac — Python e Django

Registro dos meus estudos no curso **Python II — desenvolvendo aplicações web**, realizado no **Senac em 2025**.

Durante o curso, nem todos os arquivos e alterações foram registrados em commits e enviados para o GitHub. Por isso, este repositório reúne apenas parte dos exercícios e uma versão inicial do projeto em Django. O histórico disponível não representa todo o trabalho desenvolvido nas aulas.

O projeto publicado ficou incompleto e é mantido como **material de estudo e registro do meu aprendizado**.

## Conteúdo disponível

- Exercícios de Python, incluindo adivinhação de números e pedra, papel e tesoura.
- Listas de palavras para exercícios de jogo da forca.
- Projeto inicial **MotorWeb**, em Django, com página principal e página de contato.

## Organização

- `exercicios/`: exercícios de Python e listas de palavras em `exercicios/forca/`.
- `django/motor/`: projeto MotorWeb das aulas.
- `requirements.txt`: dependências do projeto Django.

## Executar o projeto Django

Na raiz do repositório, com Python instalado:

```bash
python -m venv .venv
```

Ative o ambiente no Windows:

```bat
.venv\Scripts\activate
```

No Linux ou macOS, use `source .venv/bin/activate`. Depois:

```bash
python -m pip install -r requirements.txt
python django/motor/manage.py migrate
python django/motor/manage.py runserver
```

Abra `http://127.0.0.1:8000/`. A página de contato está em `/contato`.

Os exercícios podem ser executados individualmente com Python, por exemplo:

```bash
python exercicios/ex3-PedraPapelTesoura.py
```

