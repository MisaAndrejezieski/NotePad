# == Programação ==

# Comandos pip para python:

. Instalar um pacote: pip install nome_do_pacote

. Desinstalar um pacote: pip uninstall nome_do_pacote

. Atualizar um pacote: pip install --upgrade nome_do_pacote

. Listar pacotes instalados: pip list

. Mostrar informações de um pacote: pip show nome_do_pacote

. Procurar um pacote: pip search nome_do_pacote

. Instalar pacotes a partir de um arquivo de requisitos: pip install -r requirements.txt

. Gerar um arquivo de requisitos: pip freeze > requirements.txt


# Comando venv para windows:
## Instalação do módulo venv:
pip install virtualenv

## Criação de um ambiente virtual:
python -m venv /caminho/para/novo/ambiente/virtual
<p>ou</p>
python -m venv venv_name

## Ativação do ambiente virtual:
venv_name\Scripts\activate.bat
<p>ou</p> se estiver utilizando o PowerShell:
.\venv\Scripts\activate.ps1

## Desativação do ambiente virtual:
deactivate
