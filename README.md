# Projeto_Leitura_Documentos #
>*PROJETO FINAL* para o curso *"Business Intelligence e Ciência de Dados"* disponibilizado em parceria da Escola de Contas do TCE/AC e Universidade Federal da Paraíba - UFPA
>
>## 🚀 OBJETIVO:
>* Fazer a leitura de Acórdãos do TCE/AC
>* extrair informações relativas a número do acórdão, data do julgamento, e conteúdo do Acórdão.
>* Criar a indexação com base no conteúdo dos Acórdãos para filtragem posterior.
>* Apresentar um gráfico quantidade sobre o assunto por ano ao final
>-----------
>## 👨‍🏫 Professores
>
> André Luiz - Professor/Orientador
>-----------
> Geraldo Braz - Professor/Orientador
>## ✒️ Integrantes do Grupo
>
>-----------
>
> Antonino Marques Jares - TCE/AC
>
> Jamile Santos do Vale - TCE/AC
>
> José Coca Carrascosa Neto - MP/AC
>
> Wallison Santos Ferreira - MP/AC
>
>-----------
## 📄 Licença
> Todos os Acórdãos do TCE/AC utilizados neste projeto já foram publicados
> 
>-----------
## A) Etapas do pré-processamento - utilizaremos Python , PANDAS, Expressão Regular ##

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


