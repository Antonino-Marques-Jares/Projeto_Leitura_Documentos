# Projeto_Leitura_Documentos #
>*PROJETO FINAL* para o curso *"Business Intelligence e Ciência de Dados"* disponibilizado em parceria da Escola de Contas do TCE/AC e Universidade Federal da Paraíba - UFPA
>
>*OBJETIVO:* Fazer a leitura de Acórdãos do TCE/AC todos já publicados, extrair destes Acórdãos informações relativas a numero do acórdão, data do julgamento. Criar a indexação destes Acórdãos para fazermos consultas nestes Acórdãos.
>
>Integrantes do Grupo
>-----------
>
>Antonino Marques Jares - TCE/AC
>
>Jamile Santos do Vale - TCE/AC
>
>José Coca Carrascosa Neto - MP/AC
>
>Wallison Santos Ferreira - MP/AC
>



## A) Etapas do pré-processamento - utilizaremos Python , PANDAS, Expressão Regular ##

1) Fazer a leitura dos Acórdãos que estão em pdfs e exportar para uma planilha xls.

   A planilha terá as seguintes colunas iniciais INDICE e CONTEUDO.
   
   No primeiro momento não poderemos pegar o número do Acórdão, para isso devemos eliminar textos iniciais do conteúdo.

   Depois criaremos a coluna ACÓRDÃO onde colocaremos o número do Acórdão
   
2) Retirar NAN'S - utilizando o dataset do PANDAS  
4) Retirar texto inicial e final que não será objeto do estudo
....
?) Pegar o número do acórdão para colocar na coluna "acordao" da planilha
?) Deixar na coluna CONTEUDO o texto excencial

## B) Tokenização
1) dividir em palavras remover pontuação e caracteres especiais

## C) Normalização
1) Letras Minusculas

## D) N-Grams
1) Definir o número de GRAMS

## E) StopWords
1) Retirar palavras não relevantes ao treinamento de máquina

## F) Stemming e Lemmatization

## G) Bag of Words


