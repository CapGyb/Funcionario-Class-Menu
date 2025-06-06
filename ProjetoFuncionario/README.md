# Funcionario Class Menu

Este projeto é um sistema de gerenciamento de funcionários desenvolvido em Java, utilizando o padrão de arquitetura MVC (Model-View-Controller).

## Estrutura do Projeto

- `Funcionario.java`: Classe modelo que representa um funcionário.
- `FuncionarioDAO.java`: Camada de acesso a dados.
- `FuncionarioRepository.java`: Repositório intermediário entre DAO e Controller.
- `FuncionarioController.java`: Controla a lógica de negócios.
- `FuncionarioView.java`: Interface de menu com o usuário via terminal.
- `Main.java`: Classe principal que inicia a aplicação.

## Requisitos

- Java JDK 8 ou superior
- Terminal ou IDE (ex: IntelliJ, Eclipse, VSCode)

## Compilação

Abra o terminal no diretório do projeto e execute:

```bash
javac *.java
