# Lista de Tarefas com Django

Este é um projeto de exemplo de uma Lista de Tarefas desenvolvida utilizando o framework Django. O projeto permite que você crie, visualize, edite e exclua tarefas de uma lista.

## Funcionalidades

- Adicionar novas tarefas com título e descrição.
- Marcar tarefas como concluídas.
- Editar detalhes de uma tarefa existente.
- Excluir tarefas da lista.

## Pré-requisitos

Certifique-se de ter o seguinte instalado em sua máquina:

- Python (versão 3.x)
- Django (versão 3.x)

## Como Executar o Projeto

1. Clone este repositório em sua máquina local:

```bash
git clone https://github.com/matheus-hrm/taskproject.git
```

2. Abra o prompt de comando dentro do repositório

```bash
cd taskproject
cd Tasklist_project
```

2. Instale as dependências do projeto:

```bash
pip install -r requirements.txt
```

3. Execute as migrações do banco de dados:

```bash
python manage.py migrate
```

4. Inicie o servidor web
```bash
python manage.py runserver
```

5. Abra no seu browser pelo localhost
```
   http://127.0.0.1:8000/ 
