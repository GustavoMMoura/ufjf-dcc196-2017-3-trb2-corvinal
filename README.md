# ufjf-dcc196-2017-3-trb2-corvinal

Fernanda Nunes Dutra 201476001 fernandanunesdutra96@gmail.com

Gabriel Lomba Aguiar Costa 201376011 gabriellomba@hotmail.com

O aplicativo tem como objetivo registrar as informações das pessoas que entram no evento - bienal - , 
dos livros disponíveis para reservas e as reservas realizadas por cada pessoa.

O projeto possui três classes principais:

    1. Livro: A classe livro guarda a informação do livro (id, título, editora e ano de publicação) 
    2. Pessoa: A classe pessoa guarda a informação da pessoa (id, nome, email, horário de entrada e saída da bienal)
    3. Reserva: A classe reservar, guarda a informação da pessoa e a lista de livros que ela reservou.

As informaçes do aplicativo são armazenadas no banco de dados. O banco possui as mesmas tabelas que o model e os mesmos campos: livro, pessoa e reserva. Reserva é uma tabela gerada pela relação n para n das tabelas pessoa e livro. 
