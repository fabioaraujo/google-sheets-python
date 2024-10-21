# Comandos para configuração inicial do projeto

```bash
    pip install uv
    uv init
    uv add google-api-python-client google-auth-httplib2 google-auth-oauthlib
    uv add pre-commit
    uv sync
    pre-commit install
```

Para criar / atualizar a versão do python dentro do venv

```bash
    uv venv --python 3.10.7
```

## Seguindo guia

https://developers.google.com/sheets/api/quickstart/python?hl=pt-br

Exemplo de leitura de uma planilha do google
