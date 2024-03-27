# Kit de Projeto de Dados

Kit de Ferramentas padrões para projeto de dados.

## STACK

- Python
- Pyenv
- Poetry
- Black
- Isort
- Pip-Audit
- Pre-Commit
- Pydocstyle


## Como utilizar

1. Clonando Projeto
```bash
git clone https://github.com/luhborba/datakit_start.git
cd datakit_start
```

2. Rodando Projeto com Pyenv e Poetry 
```bash
pyenv install 3.11.5
pyenv local 3.11.5
poetry env use 3.11.5
poetry shell
poetry install
```
Você pode utilizar a versão do Python desejada.

3. Instalando Pre-Commit
```bash
pre-commit install
```

4. Realizando Formatação dos arquivos .py
```bash
task format
```

5. Realizando Checagem de DocStrings e Vulnerabilidades de Bibliotecas
```bash
task check
```