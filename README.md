emprestimo CREATE table tbemprestimo( emprestimoid int, nome_livro varchar(30), data_emprestimo int, data_devolucao int (30), PRIMARY KEY (emprestimoid) );

bibliotecario CREATE table tbbibliotecario( bibliotecarioid int, nome varchar(30), cpf int, idade int (30), PRIMARY KEY (bibliotecarioid) );

livros CREATE table tblivros( livrosid int, titulo varchar(30), autor char, genero char (30), PRIMARY KEY (livrosid) );

leitor CREATE table tbleitor( leitorid int, nome varchar(30), endereco int, telefone int (30), PRIMARY KEY (leitorid) );
