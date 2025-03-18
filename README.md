# Sistema Acadêmico para Universidade

![Diagrama de Entidade-Relacionamento](diagram.png)

## Contexto do Projeto
Este projeto consiste em criar um esquema conceitual para a gestão acadêmica de uma universidade, abrangendo alunos, professores, cursos e disciplinas.

## Entidades Principais
- **Aluno**: Representa o estudante matriculado em cursos.
- **Professor**: Detalha os docentes vinculados a disciplinas e departamentos.
- **Departamento**: Agrupa cursos e disciplinas por área acadêmica.
- **Curso**: Refere-se aos programas acadêmicos oferecidos pela universidade.
- **Matriculado**: Registra a relação entre os alunos e os cursos em que estão matriculados.
- **Disciplina**: Representa as matérias oferecidas no curso.
- **Pré-Requisitos**: Estabelece a relação de dependência entre disciplinas.

## Relacionamentos
- Um **Aluno** pode se matricular em vários **Cursos**.
- Um **Professor** é vinculado a um **Departamento**.
- Um **Curso** pertence a um **Departamento**.
- Uma **Disciplina** pode estar associada a um **Curso** e ter outros **Pré-Requisitos**.

## Estrutura do Repositório
- `README.md`: Explicação do esquema conceitual.
- `diagram_universidade.png`: Imagem do diagrama de entidade-relacionamento (ER) do cenário.

## Observação
O modelo permite fácil manutenção e expansão conforme necessário.
