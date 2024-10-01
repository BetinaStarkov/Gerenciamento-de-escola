# Sistema de Registro de Alunos e Notas

Este projeto é um sistema simples para gerenciar o registro de alunos, cursos e suas respectivas notas. Ele foi desenvolvido utilizando comandos SQL e pode ser usado para inserir, consultar, atualizar e excluir dados de um banco de dados relacional.

## Tecnologias Utilizadas
- MySQL ou qualquer sistema de gerenciamento de banco de dados SQL compatível.

## Funcionalidades
1. **Criação do Banco de Dados e Tabelas:**
   - Criação de um banco de dados chamado `Escola`.
   - Tabelas:
     - `Alunos`: Armazena os dados dos alunos.
     - `Cursos`: Armazena informações sobre os cursos.
     - `Notas`: Relaciona os alunos com suas respectivas notas em cursos específicos.

2. **Inserção de Dados:**
   - Insere alunos, cursos e notas na base de dados.

3. **Consultas:**
   - Consulta para listar todos os alunos com suas respectivas notas por curso.
   - Consulta para calcular a média das notas de cada curso.
   - Consulta para encontrar o aluno com a maior nota em cada curso.

4. **Atualizações:**
   - Atualiza a nota de um aluno em um curso específico.
   - Atualiza o endereço de um aluno.

5. **Exclusão:**
   - Exclui um aluno e suas notas associadas.
   - Remove um curso e suas notas associadas.

## Como Utilizar

### Pré-requisitos:
- MySQL instalado e configurado.
- Acesso a um terminal ou interface gráfica para executar comandos SQL.

### Passos:
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/sistema-registro-alunos-notas.git
