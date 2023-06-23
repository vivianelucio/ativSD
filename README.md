Este projeto foi desenvolvido pelos alunos Ranniher da Silva Rosa e Viviane de Nazaré Coelho Lúcio, do 3º semestre (noturno) do curso de Tecnologia em Desenvolvimento e Análise de Sistemas do IFPA.

Para a execução do projeto, devem ser seguidos os seguintes passos: 
1. Extrair zip
2. Importar no Netbeans
   File > Import Project > From zip
3. Buildar o projeto
   Botão direito > Clean and Build project

Passos do projeto:

Instalar e rodar o ActiveMQ.

A classe que inicia o projeto é a que tá no pacote principal: atividade.fila (AtividadeFilaApplication.java). Execute-a.

localhost:8080/home - url pra acessar a listagem
localhost:8080/home/adicionar - url pra adicionar veículo

O botão adicionar na página home já direciona pra url responsável por adicionar o veículo.

Depois de adicionar os dados do veiculo e salvar, vai ser redirecionado pra listagem de novo, e os dados vão ser enviados como mensagem pra fila, quando for redirecionado para a página de listagem são consumidas as mensagens da fila e ele salva no banco de dados e aparece já na listagem.
