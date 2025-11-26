 # genfocus-api

> API em django para cadastro, consulta, atualização e exclusão de usuários.

## Índice
- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Instalação](#instalação)
- [Uso](#uso)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Sobre o Projeto
    API RESTful desenvolvida para gestão corporativa de recursos humanos, focada em escalabilidade e organização de dados.
### Entidade "Pessoa"
Cada pessoa cadastrada na API possui os seguintes atributos:
- Nome Completo
- Data de nascimento
- Endereço
- CPF
- Estado Civil

## Funcionalidades

- **Cadastro de Pessoas**: Permite adicionar novas pessoas ao sistema.
- **Consulta de Pessoas**: Exibe as informações das pessoas cadastradas.
- **Atualização de Pessoas**: Permite atualizar dados de um cadastro existente.
- **Exclusão de Pessoas**: Permite remover registros de pessoas.

## Tecnologias Utilizadas

- **Linguagem**: Python
- **Framework**: Django
- **Banco de Dados**: SQLite

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/LuigiBMacario/caseBackEnd.git
2. Acesse o diretório do projeto:
   ```bash
   cd caseBackEnd
3. Crie um ambiente virtual e ative-o:
    ```bash
    python3 -m venv venv
    source venv/bin/activate # Para sistemas Unix
    venv\Scripts\activate # Para Windows
    # Será necessario ter o python instalado. Você pode instalar o python pela Microsoft Store ou pelo site oficial: https://www.python.org/downloads/
4. Instale as dependências:
   ```bash 
   pip install -r requirements.txt

## Uso

1. Execute a aplicação:
   ```bash
   python manage.py runserver
   
2. Acesse a API em:
   http://127.0.0.1:8000
