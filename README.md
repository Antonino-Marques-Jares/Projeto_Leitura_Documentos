# Projeto_Leitura_Documentos #
>*PROJETO FINAL* para o curso *"Business Intelligence e Ciência de Dados"* disponibilizado em parceria da Escola de Contas do TCE/AC e Universidade Federal da Paraíba - UFPA
>
>*OBJETIVO:* Fazer a leitura de Acórdãos do TCE/AC todos já publicados, extrair destes Acórdãos informações relativas a numero do acórdão, data do julgamento, regularidade, ressalva e irregularidade.


## A) Etapas do pré-processamento - utilizaremos Python , PANDAS, Expressão Regular ##

1) Fazer a leitura dos Acórdãos que estão em pdfs e exportar para uma planilha csv.

   A planilha terá as seguintes colunas iniciais ACORDAO e CONTEUDO.
   
   No primeiro momento não poderemos pegar o número do Acórdão, para isso devemos eliminar textos iniciais do conteúdo.

   Na coluna ACORDAO será colocado um número sequnêncial para verificar se todos os arquivos foram lidos e adicionados na planilha.
   
3) Fazer a leitura do csv que foi criado na etapa anterior e retirar NAN'S - utilizando o dataset do PANDAS  
4) Fazer a leitura do csv anterior e retirar texto inicial e final que não será objeto do estudo
5) Fazer a leitura do csv anterior e pegar o número do acórdão para colocar na coluna "acordao" da planilha
6) Deixar na coluna CONTEUDO o texto excencial

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


