# sisaluno
Sistema de cadastro de alunos

1 - Colocar layout com CSS em todas as paginas e seguir modelo disponibilizado.

2 - fazer os formularios para permitir inserir, excluir e alterar professor.

3 - fazer os formularios para permitir inserir, excluir e alterar disciplinas.

4 - criar pagina inicial para permitir acessar as paginas de professor, aluno e disciplinas.

## Dados para banco de dados:

Database: sisaluno
tabelas: Aluno, professor, disciplinas.
Atributos das tabelas:
   # 2AI
      Aluno ->
      id smallint primary key auto_increment
      nome, varchar(100)
      idade,  smallint
      datanascimento,  date
      endereco varchar(100)
       estatus   char(20)


      professor ->
      id smallint primary key auto_increment
      nome, varchar(100),
      cpf, varchar(11)
      idade,  smallint
      datanascimento,  date
      endereco varchar(100)
       estatus   bool


       disciplina ->
       id smallint primary key auto_increment
      nomedisciplina varchar(100),
      ch varchar(3)
      semestre varchar(5)
      idprofessor smallint


      # 2BI 
      Aluno ->
      idaluno smallint primary key auto_increment
      nome, varchar(100)
      idade,  smallint
      datanascimento,  date
      endereco varchar(100)
       estatus   bool
       matricula: varchar(11)


      professor ->
      idprofessor smallint primary key auto_increment
      nomeprof, varchar(100),
      cpf, varchar(11)
      siape varchar(10),  smallint
      idade smallint


       disciplina ->
       iddisciplina smallint primary key auto_increment
      disciplina varchar(80),
      ch char(3)
      semestre varchar(5)
      idprofessor smallint
          
