# Desafio para Analista Desenvolvedor da AEVO

Olá candidato,

Primeiramente parabéns por ter chegado até aqui! 

Esse desafio consiste em uma pequena implementação para avaliarmos seu conhecimento em back-end (.NET, C#) e Front-End (HTML5, CSS, JavaScript e Angular)

Para realizar o desafio, você deve dar um fork neste repositório e depois clona-lo em alguma pasta de sua preferencia na máquina que está realizando o teste.

Crie um branch com seu nome a aprtir da master, e quando finalizar todo o desenvolvimento, você deverá enviar um pull-request com sua versão.<br>

Neste repositório existe um projeto base em .NET Core 3.1 baseado em um tutorial do Macorrati (referência quando o assunto é .NET) http://www.macoratti.net/19/10/ang7_apinc1.htm 
Fiquem a vontade para explorar o tutorial com os detalhes da configuração do projeto. Apesar do projeto deste respositório estar atualizado para a versão 3.1, a estrutura é a mesma do tutorial.

# O Desafio
## Back-End/.NET
A primeira etapa será o desenvolvimento backend!

Descrição:

Neste respositório já existe uma implementação básica com o CRUD para o objeto Aluno.
Você deverá desenvolver novos métodos para a 'mini api' ou reutilizar métodos existentes do projeto base, para as implementações necessárias.

Cada Aluno possui as propriedades AlunoId, Nome e Email
Sugerimos o retorno dessa 'mini api' nas seguinte urls:

/alunos      -[GET] deve retornar todos os alunos cadastrados.<br>
/aluno       -[POST] deve cadastrar um novo aluno. <br>
/aluno/{id}  -[GET] deve retornar o aluno com ID especificado. <br>
/aluno/{id}  -[PUT] deve atualizar os dados do aluno com ID especificado. <br>
/aluno/{id}  -[DELETE] deve apagar o aluno com ID especificado. <br>

Você pode utilizar um banco de dados local SQL Server para a persistência dos dados. Utilizar a migration existente no projeto .NET base para gerar a base de dadospode ajudar bastante!

## Front-End /Angular
Para a segunda etapa do teste, você deverá desenvolver uma SPA (Single Page Application) utilizando Angular e nela deve ser possível:

- Ver a lista de alunos cadastrados
- Criar um novo aluno
- Editar um aluno existente
- Pesquisar um aluno pelo nome
- Pesquisar um aluno pelo ID
- Reordenar a lista de Alunos por ordem alfabética


### Observações importantes:
A base para o projeto Front-End não está neste repositório. Você deverá criar a sua baseado na versão do Angular de sua preferência.<br>
Você não deve se prender somente aos arquivos do repositório. Fique a vontade para criar outros.<br>
Você pode usar ferramentas de automação, mas deverá informar o uso completo para funcionamento do desafio.<br><br>

- Será considerado ponto positivo a utilização de testes de unidade, boas práticas de orientação a objetos, design patterns e rotinas para testes.<br>
- Será considerado ponto positivo a utilização de documentação para o mini projeto.<br>
- Será considerado ponto positivo e diferencial a publicação do projeto em algum ambiente online.<br>

Estamos sempre em busca de melhoria, por isso, caso tenha alguma sugestão fique a vontade pra compartilhar conosco! Boa sorte! 💛




