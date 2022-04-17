# 1_desafio_Compass
1º Desafio sprint 1 da equipe Spectrum/ Lucas Gonçalves Araújo

Perguntas e Respostas: 
1.	Para que serve o método Scrum? 
 Resposta : Scrum é método ágil que utilizamos  para termos o controle sobre o que precisa ser feito, qual o meu papel no time e como meus métodos diários podem influenciar o resultado final do projeto, ele tem como base três princípios fundamentais: Transparência no processo, requisitos de entregas e status, Inspeção constante de tudo que está sendo feito e Adaptação tanto no processo, quanto do produto as mudanças.

2.	Como funciona o método Scrum? 
Resposta : O scrum é dividido entre Scrum máster, Product Owner e Dev team, cada um possui  funções diferentes em relação ao andamento do projeto, por exemplo o Scrum máster é responsável em focar no processo e assegurar que o time esteja tirando o maior proveito possível dele, o Po é o representante do cliente dentro do projeto e os desenvolvedores  tem a função de decidir a abordagem técnica para os problemas apresentados. Dentro do Scrum temos a Sprint, ela  pode ser definida em  um período de tempo de  1 à 4 semanas, chamada de Sprints longa e curta isso depende do  time e do projeto que esta equipe está desenvolvendo, ou seja, é o período que o time tem para entregar os resultados solicitados, também temos as Daily que são reuniões diárias em que todo time participa para informar: O que foi feito ontem, o que eu vou fazer hoje e se tive algum impeditivo, essas perguntas são feitas para se obter o controle do que cada membro do time está trabalhando. O método Scrum também possui o, planning meeting ,  review meeting e a retrospectiva, onde o planning  meeting é tarefa que vai produzir a Sprint backlog  e definir a lista de prioridades do projeto, ela possui um time box de 5% da Sprint, já a review meeting possui um time box curto de 2,5%  do tempo da Sprint , no qual sua função é uma reunião com cliente e o time de desenvolvimento para esclarecer as dúvidas do projetos e por último a retrospectiva com um time box de 5% da sprint é uma reunião que visa a melhoria continua do time, ela tem como objetivo sanar os erros para a próxima sprint.

3.	O que é Git? 
Resposta : É um repositório que tem como função o  controle de versões.

4.	O que é um scrum Product Owner? 
Resposta : É o representante do cliente no projeto, mas ele faz parte da equipe, sua função é de entregar mais ou menos o valor ao cliente, ele também é responsável pelo Product Back: Lista ordenada das coisas a fazer em um projeto (Mantém atualizada).

5.	Qual o comando para criação de um novo repositório no Git? 
Resposta : git init.

6.	O que é o HTTP? 
Resposta :É um protocolo (conjunto de regras) que define as regras de comunicação entre cliente ,internet e servidor.

7.	Como funciona o HTTP?
Resposta : Segue o modelo Requisição-Resposta , sempre o cliente inicia a comunicação, o cliente faz a solicitação através de navegadores como, Chrome e Firefox , essas informações navegam pela internet até chegarem na requisição do servidor(Usando PHP,.NET, Java ou outros).  Uma requisição precisa ter todas as informações para o ser vido gerar a resposta, o HTPP é stateless, ou seja, não  mantém informações entre requisições.

8.	Com o Git Você pode propor mudanças (adicioná-las ao Index) usando um comando. Qual é esse comando? 
Resposta : git add.

9.	O que é a Branch master e para que serve? 
Resposta : É o nosso repositório principal, onde normalmente estão alocados os projetos em produção.

10.	Quais são os comandos usados para atualizar um repositório local e fazer merge de um outro branch ao seu branch ativo?
Resposta :  git pull local; git merge <branch>.

11.	Pensando em Bases de dados, sendo elas, Relacionais (SQL) e Não Relacionais (NoSQL). Quais alternativas abaixo estão corretas? 
a.	MySQL = MongoDB 
b.	PostgreSQL = Redis 
c.	Oracle = CouchDB 
d.	Todas as alternativas estão corretas. // alternativa correta, letra D

12.	O que é MongoDB?
Resposta : É um gerenciamento Open Source de bancos de dados não relacionais (NoSQL) pois sua recuperação e armazenamento de dados não são feitas no formato de tabelas, ele utiliza  documentos semelhantes ao  formato de um Json.

13.	O que é o MySQL?
Resposta : É um gerenciamento de  banco de dados relacional que utiliza o SQL(Linguagem query structured)  para organizar dados e informações para consultas.

14.	Qual a diferença entre git e github?
Resposta :   O  git é um sistema de controle de versões  já o Github é um servidor  que  nos disponibiliza criar repositórios usando git , com ele, conseguimos compartilhar  remotamente  os arquivos  pela internet.

15.	Quais os dois verbos http que podemos utiizar para realizar um update? Explique a diferença entre eles.
Resposta : Post adiciona as informações usando o recurso da URI passada e o Put adiciona ou modifica usando o recurso da URI passada. 

16.	Qual o status code que pode ser usado na criação de um novo usuário? 
Resposta : Post

17.	Quais são os três status code que modem ser utilizados para realizar o delete? 
Resposta : Status 202, quando a ação teve sucesso mas  ainda não foi realizada .(Accepted)
	Status 204 quando a ação foi realizada e nenhuma outra informação deve ser fornecida(No Content).
	Status 200 quando a mensagem foi realizada e a mensagem de resposta inclui uma representação descrevendo o status (ok).

	
18.	Qual a extensão ".xxx" contêm as definições da tabela? 
a.	Commands.myi 
b.	Commands.frm 
c.	Commands.myd // Alternativa correta é a letra C
d.	{mysqlDirectory}/data 
	
19.	A pasta "C:\ProgramData" é uma pasta oculta, portanto, você deve digitá-la no endereço do Windows Explorer para chegar lá.  
Nessa pasta de dados, quais opções apresentam o caminho correto para acessar os bancos de dados que foram denominados? 
a.	/{database_name_folder}/{database_tables_and_files}. 
b.	C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.frm 
c.	C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.ibd // Alternativa correta é a letra C
d.	C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\data-recovery 

20.	Qual a extensão ".xxx" que contêm os dados da tabela? 
	Resposta : SQL Text File (.sql) 
	
21.	Qual comando usa-se para extração de arquivos em MongoDB durante a instalação? 
	Resposta : mongod --dbpath <path to data directory>  

22.	Para que usamos o MongoDB? 
	Resposta: Quando queremos guardar dados em documentos, ao contrario de usar os  padrões das tabelas como nos bancos relacionais, desta forma podemos alterar os registros. Sendo assim, conseguimos alterar a estrutura que no mongodb é tratada como documento. Podemos fazer isso adicionando novos campos ou deletando os campos que já foram adicionados anteriormente, esse recurso do mongo é bem usado e faz com que as relações hierárquicas possam ser representadas com sucesso.


23.	Exemplifique para que serve os metódos http 1xx, 2xx, 3xx, 4xx e 5xx. De uma forma macro (geral)! 
	Resposta : O código 200 significa OK, ou Sucesso, que não houve nenhum problema no processamento da requisição e ela foi bem sucedida. Existem mais códigos que começam com 2xx. No entanto 200 é de longe o mais utilizado, principalmente no desenvolvimento de uma aplicação web.
Resposta : 25.	O código 200 significa OK, ou Sucesso, que não houve nenhum problema no processamento da requisição e ela foi bem sucedida(successful responses).
Existem mais códigos que começam com 2xx. No entanto 200 é de longe o mais utilizado, principalmente no desenvolvimento de uma aplicação web.
3xx normalmente significa que o navegador precisa fazer algo a mais (o cliente precisa agir).pois algo mudou ou um recurso não existe mais. Orientamos a redirecionar os sites(Redirection messages)
404 é o código clássico que indica que o recurso não foi encontrado. Em geral, a classe 4xx indica que o cliente errou algo na requisição.(cliente error responses)
A classe 5xx significa que houve algum problema no servidor.
Por exemplo: 500 - Internal Server Error, ou outro famoso: 503 - Service Unavailable.
O código 500 acontece com frequência quando estamos desenvolvendo uma aplicação web e, ao testar, percebemos que erramos algo na lógica que gerou um problema no servidor(server error responser).

24.	Conta pra gente como foi sua experiência na Sprint#01 do programa de bolsa @node.js_mar22 e quais suas expectativas a partir de agora ?
	Resposta : Foi uma experiência única, tive a oportunidade de aprender e compartilhar conhecimentos que são muito importantes no dia a dia  de um desenvolvedor e sua equipe, como tudo o que é novo no inicio tive uma adaptação ao ambiente, aos assuntos e principalmente aos gestores  e aos meus colegas mas isso foi questão de tempo, hoje já me sinto muito a vontade com todos, a forma com que fui tratado por todos no inicio, foi o fator crucial para me preparar, aprender  e ajudar ainda para a próxima sprint, nela pretendo adquirir o máximo de conhecimento nas aulas e acima de tudo  compartilhar com meus colegas esse conhecimento que ,por mais que seja o mesmo assunto estudado por nós sempre temos novas ideias e novas formas de encarar e solucionar um problema.
