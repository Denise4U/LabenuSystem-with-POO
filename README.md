# LabenuSystem-with-POO
Sistema beckend que representa o básico de uma organização educacional.


Ele possui, ao menos, 3 entidades importantes:

### 1. Estudantes

Representa estudantes da instituição. Eles possuem: id, nome, email, data de nascimento e os principais hobbies do estudante.

### 2. Docente

Representa docentes da instituição. Eles possuem: id, nome, email, data de nascimento e todas as especialidades dele. Há 7 especialidades: React, Redux, CSS, Testes, Typescript, Programação Orientada a Objetos e Backend.

### 3. Turma

Toda turma é composta das seguintes características: id, nome, data de início, data de término, lista de professores responsáveis, uma lista de alunos e módulo atual em que a turma está.

O módulo pode assumir os valores de 1 a 7 ou undefined, indicando que as aulas dessa turma ainda não começaram.   Considere que existam dois tipos de turma: integral ou noturna. Há uma restrição para o nome das turmas noturnas: tem que terminar com -na-night.

As funcionalidades básicas são:

→ Criar estudante;

→ Criar docente;

→ Criar turma;

→ Adicionar estudante na turma;

→ Adicionar docente na turma;

→ Pegar a idade de algum estudante a partir do id
