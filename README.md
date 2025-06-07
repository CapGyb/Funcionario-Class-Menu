Sistema de Cadastro de Funcionários

Projeto final da disciplina Programação de Soluções Computacionais, com objetivo de implementar um sistema CRUD completo em Java com persistência em arquivo texto.

📌 Funcionalidades

Criar novo funcionário

Listar todos os funcionários

Buscar funcionário por ID

Atualizar dados de um funcionário

Deletar um funcionário

Persistência dos dados em arquivo funcionarios.txt

Interface limpa via console

📁 Estrutura de Pastas

├── Funcionario.java
├── FuncionarioController.java
├── FuncionarioRepository.java
├── FuncionarioView.java
├── Main.java
├── funcionarios.txt (gerado automaticamente)

💡 Requisitos

Java 11 ou superior

Terminal ou IDE com suporte a execução de projetos Java


✅ Validações

-Nome não pode ser vazio

-Salário não pode ser negativo

📌 Observações

O arquivo funcionarios.txt será criado na primeira execução caso não exista.

Toda modificação (criação, edição ou exclusão) atualiza o arquivo imediatamente.
