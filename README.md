# *Introdução MVC* 🕹️

### O que é MVC?
- M: Model
- V: View
- C: Controler
É um padrão de arquitetura, usado para organizar o código, de forma clara, separando a lógica em 3 partes.

#### ESQUEMA MVC
usuários(navegador) -> requisição -> controler -> model -> controler -> view -> usuários

|  CAMADA     |   FUNÇÃO                                    |   EXEMPLO                         | EXEMPLO             |
|:-----------:|:-------------------------------------------:|:---------------------------------:|:-------------------:|
|   MODEL     |         Gerencia os dados e regras          |      Dados alunos e professores   | aluno php           |
|   VIEW      | Responsável pela interface: o que o user vê |           Exibição da página      | alunosView.php      |
| CONTROLER   |         Intermedia o model e a view         | Recebe o pedido para mostrar algo | alunoController.php |

 
