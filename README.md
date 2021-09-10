# luxone_teste
Criar uma API Web com o ASP.NET Core que ofereça os dados dos times e jogadores que foram cadastrados. Não é necessário fazer conexão com banco de dados, os dados serão salvos na memória.
Serão necessárias duas rotas para cada entidade, uma rota para GET (recuperar dados) e uma rota para fazer POST (criar) todos aceitando e retornando em formato JSON.

Para o GET será necessário
- fazer uma busca de time com uma lista de jogadores cadastrados para cada time.
- fazer uma busca que retorna todos os jogadores
- fazer uma busca de jogadores pelo Id do time
- fazer uma busca de jogadores por idade

Para o POST
- todos os campos serão obrigatórios, não deixar cadastrar se faltar um dos campos.

 - Time -

Id (Gerado Automaticamente)
Nome (no máximo 10 caracteres);
Data de inclusão no cadastro;
Média de idade dos jogadores (Valor calculado e não cadastrado);

 - Jogador -

Id (Gerado Automaticamente)
Nome Completo (no máximo 20 caracteres);
Idade;
TimeId;
