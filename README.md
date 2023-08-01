# 🚀 Extraindo dados do CSV com APACHE HOP

Construido um Pipeline de tratamento de dados com [Apache HOP](https://hop.apache.org/) e extraindo dados de um arquivo CSV.

### 📋 Pré-requisitos
Vamos precisar,
* [Java JDK 11 instalando no Computador](https://www.oracle.com/br/java/technologies/javase/jdk11-archive-downloads.html)
* [Apache HOP 2.5.0](https://hop.apache.org/)

* ![pipelineDados](https://github.com/riversdiniz/PipelineTratamentoDadosVinho/assets/27660298/05158e03-2bf7-489d-b304-201728760732)

### 📋 Plugin utilizado nesse projeto.
1. CSV FILE INPUT - Para Ler arquivo em CSV
2. VALUE MAPPER - Para tratar o dados
3. FILTER ROWS - Para fazer um filtro em quaisquer campo selecionado
4. TEXT FILE OUTPUT - Onde iremos gravar o dados em TXT
5. DUMMY (DO NOTHING) - Para direcionar os dados que não forem selecionados(lixo)
6. SELECT VALUES - Seleciona campos que no qual vamos fazer alteração
7. SORT ROWS - Para colocar em ordem decrescente
8. GROUP BY - Juntar o campos

⌨️ 🚀 por [River Diniz](https://gist.github.com/riversdiniz) 🧑‍🚀
