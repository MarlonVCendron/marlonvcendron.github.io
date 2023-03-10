Armazenar senhas com segurança é um aspecto crítico de segurança de dados. Existem diversas práticas a serem aplicadas tanto na senha, como na base dados e na conexão com a base de dados que maximizam a segurança das senhas armazenadas.

## Hash

Uma das práticas mais importantes para a segurança de senhas, salvar o hash das senhas faz com que caso algum atacante que consiga acesso à base de dados não seja capaz de descobrir a senha. O hash é irreversível, ou seja, não é possível descobrir qual é a senha utilizada a partir do hash.

Quando o usuário digite sua senha para logar, é gerado o hash da senha digitada e então é comparado com o hash salvo na base de dados. Assim, só é possível saber se o usuário acertou a senha ou não.

É importante também utlizar as funções hash mais fortes, como SHA-256 ou SHA-512. Versões antigas de SHA (Secure Hashing Algorithm), como SHA-1 e SHA-2 usavam menos bits para gerar o hash, e hoje 
é muito fácil de quebrá-los.

Para tornar o hash ainda mais forte, é boa prática adicionar um salt aleatório, que é uma string de caracteres aleatória gerada para cada senha. Isso evita que, no caso de vazamento do hash, um atacante possa descobrir a senha através de tabelas de hashes já conhecidos. Existem bancos de senhas comuns e seus hashes já calculados (chamadas rainbow tables), quando não há salt um atacante pode descobrir a senha ao encontrar no banco o mesmo hash. O salt faz com que o atacante tenha que gerar uma rainbow table para cada senha diferente, já que cada uma tem seu próprio salt. Uma forma ainda mais segura é usar vários rounds de salt. Os salts são armazenados junto da senha no banco de dados, para que seja possível reutilizá-lo para verificar se o usuário digita a senha correta.


## Obrigar o usuário a usar senhas fortes

Quanto maior a senha e mais caracteres especiais usar, mais difícil é de quebrá-la, pois as combinações de senhas possíveis aumentam exponencialmente. É uma boa prática impedir que os usuários digitem senhas pequenas, com menos de 10 caracteres mais ou menos, e obrigá-lo a usar letras maiúsculas, números e caracteres especiais.

Outra prática normalmente utilizada mais comumente por sistemas de bancos é impedir que o usuário digite senhas que contenham o nome de usuário, email, nome de familiares, datas de aniversário, senhas comuns como "senha123" etc. Já que essas são senhas extremamente comuns e são as primeiras a serem testadas por atacantes.  


## Restringir acesso à base de dados

É importante também que poucas pessoas tenham acesso à base de dados e que cada uma tenha suas funções restritas. Algum desenvolvedor que precise de acesso à base de dados somente para testar algumas tabelas do sistema não precisa de acesso à tabela de senhas. Isso diminui a quantidade de pessoas que podem acessar as senhas, diminuindo então o número de potenciais vítimas de ataques como engenharia social entre outros.

Também é necessário que a empresa tenha uma ótima política de segurança para que essas poucas pessoas com acesso à base possam ser comprometidas por atacantes.

## SSL

É importante usar um protocolo de redes seguro na comunicação com o banco, assim os dados são criptografados, impedindo ataques Man-in-the-Middle.
