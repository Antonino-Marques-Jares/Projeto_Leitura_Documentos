# Projeto_Leitura_Documentos #
>*PROJETO FINAL* para o curso *"Business Intelligence e Ciência de Dados"* disponibilizado em parceria da Escola de Contas do TCE/AC e Universidade Federal da Paraíba - UFPA
>
>## 🚀 OBJETIVO:
>* Fazer a leitura de Acórdãos do TCE/AC
>* extrair informações relativas a número do acórdão, data do julgamento, e conteúdo do Acórdão.
>* Criar a indexação com base no conteúdo dos Acórdãos para filtragem posterior.
>* Ao final apresentar um gráfico QUANTIDADE DE ACÓRDÃOS que tratem do assunto por ANO
>-----------
>## 👨‍🏫 Professores
>
> MSc. André Luiz Firmino Alves - Professor/Orientador
>
> Dr. Geraldo Braz Junior - Professor/Orientador
>
>>-----------
>## ✒️ Integrantes do Grupo
>
>-----------
>
> [Antonino Marques Jares](https://www.linkedin.com/in/antonino-marques-jares-b447a734/) - TCE/AC
>
> Jamile Santos do Vale - TCE/AC
>
> José Coca Carrascosa Neto - MP/AC
>
> [Wallison Santos Ferreira](https://www.linkedin.com/in/wallisonferreira09/) - MP/AC
>
>-----------
## 📄 Licença
> Todos os Acórdãos do TCE/AC utilizados neste projeto já foram publicados
> 
>-----------
> ## 📦 Implantação
> utilizaremos Python , PANDAS, Expressão Regular
> 
## A) Etapas do pré-processamento

1) Fazer a leitura dos Acórdãos que estão em pdfs e exportar para uma planilha xls.
   A planilha terá as seguintes colunas ID, ACORDAO, DIA, CONTEUDO.
2) Retirar NAN'S - utilizando o dataset do PANDAS
3) Retirar registros que não foram encontrados Data do Acórdão e Número do Acórdão
4) Corrigir o indice após a exclusão de registros para que este seja sequêncial e facilite o laço (for) na próxima etapa
5) Retirar texto inicial e final no conteúdo, restringindo o texto que será objeto do estudo
   
## B) Normalização
7) Transformar em letras minúsculas
8) Remover pontuação e caracteres especiais do campo conteudo

## C) Tokenização
9) dividir em palavras 

## D) N-Grams
10) Definir o número de GRAMS

## E) StopWords
11) Retirar palavras não relevantes ao treinamento de máquina

## F) Stemming e Lemmatization

## G) Bag of Words
>
## 🎁 Agradecimento
> 1) Agradecemos nosso colega [Wisley de Oliveira Bandeira](https://www.linkedin.com/in/wisleybandeira/) por ter conseguido os PDF's dos Acórdãos que possibilitou sairmos na frente neste projeto, sem isso não seria possível trabalharmos, estudar e ainda coletarmos os Acórdãos nescessários ao projeto.
> 2) Agradecemos a todos os professores do curso *"Business Intelligence e Ciência de Dados"* por compartilhar seus conhecimentos, em especial nossos orientadores e o professor Dr. [Cláudio de Souza Baptista](https://www.linkedin.com/in/claudio-de-souza-baptista-07257721a/).
> 3) Ao
> ![<img src= "https://tceac.tc.br/site/wp-content/uploads/2023/05/LOGO-VERSAO-PREFERENCIAL.png" width="250"/>](LOGO-VERSAO-PREFERENCIAL.png)
[Tribunal de Contas do Estado do Acre](https://tceac.tc.br/site/), a
[Universidade Federal da Paraíba](https://www.ufpb.br/) e a
[Escola de Contas Conselheiro Alcides Dutra de Lima](https://moodle.tceac.tc.br/) que possibilitaram o curso *"Business Intelligence e Ciência de Dados"*
> 



