# Projeto Módulo 4: Sistema Resilia

## Proposta

'A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos'

### ⇨ Existem outras entidades além dessas três?

Matriculas;
Disciplinas; 
Professores; 
Notas.

### ⇨ Quais são os principais campos e tipos?

ID's int PK das entidades e ID's FK de alunos_cursos

### ⇨ Como essas entidades estão relacionadas?


Aluno está relacinado a cursos, podendo estar em múltiplos cursos;

Cursos está relacionado a turmas;

Disciplinas está relacionado a professores;

Matriculas está relacionado a alunos_cursos (um aluno terá matrículas diferentes em cada 
curso);

Notas está relacionado a alunos_cursos (um aluno terá notas diferentes em cada curso matriculado).

## Diagrama

![Tux, the Linux mascot](https://raw.githubusercontent.com/matheusel/SistemaResilia/main/db.png)
