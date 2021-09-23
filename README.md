# Trabalho da disciplian teste de software 2020.2
### Aluno: John Victor Farias de Omena
### Professor: Willy Tiengo

## Descrição

Basicamente é uma aplicação que disponibiliza um sistema de gerenciamento de atividades pessoais, ou seja, um TO DO list, é possivel criar diferentes contas e grupos de TODO's lists, o usuário poderá adicionar as tarefas pendentes e confirmar sua conclusão quando finalizada.

## Tecnologias usadas

- [x] Python
- [x] Django
- [x] Sqlite
- [x] HTML
- [x] Javascript
- [x] Jquery
- [x] Css

## Testes realizados

- [x] Testes de API com APITestCase do framework Rest
- [x] Testes unitários com TestCase do framework Django

```
Por ser tratar de uma aplicação que não possui muita complexidade nas regras de negócio foi investido
bastante tempo na criação dos testes, tentando extrair o máximo de possibilidade das opções disponiveis,
ao total foram implementados 54 testes, incluindo testes de API.
```

## Execução da aplicação

Primeiramente, precisamos instalar os requerimentos, e depois realizar a chamada para iniciar o servidor

    pip install -r requirements.txt

    python3 manage.py migrate

    python3 manage.py runserver

## Execução dos testes

    python3 manage.py test
    
```
Caso encontre algum problema com a execução desse comando, tente usar o comando abaixo antes
```

    python3 manage.py collectstatic
  
