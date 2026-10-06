# Modelagem Dimensional - Star Schema (DIO)

Repositório criado para entregar o desafio de modelagem de banco de dados da DIO. O objetivo foi pegar num modelo relacional de uma universidade e transformá-lo num modelo dimensional (Star Schema) focado na análise do corpo docente.

## O que foi feito:
- **Tabela Fato Central:** Criei a `fato_professor` para centralizar as métricas de turmas e carga horária.
- **Foco no requisito:** Dados de alunos e matrículas foram ignorados, seguindo estritamente as regras do desafio.
- **Dimensão de Tempo:** Adicionei a tabela `dim_data` para permitir futuras análises de oferta de disciplinas por ano, semestre e mês.
- **Diagrama Automatizado:** Escrevi o script SQL com as restrições de chaves estrangeiras (`FOREIGN KEY`) e usei a funcionalidade de Engenharia Reversa do MySQL Workbench para desenhar o diagrama EER automaticamente.

## Arquivos:
- Script `.sql` com a criação das tabelas Fato e Dimensão.
- Imagem `.png` com o diagrama final do Star Schema.
