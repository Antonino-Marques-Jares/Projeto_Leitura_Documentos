# Projeto_Leitura_Documentos #
>*PROJETO FINAL* para o curso *"Business Intelligence e Ciência de Dados"* disponibilizado em parceria da Escola de Contas do TCE/AC e Universidade Federal da Paraíba - UFPA
>-----------

## 🚀 OBJETIVO:
>* Fazer a leitura de Acórdãos do TCE/AC
>* Extrair informações relativas a número do acórdão, data do julgamento, e conteúdo do Acórdão.
>* Criar a indexação com base no conteúdo dos Acórdãos para filtragem posterior.
>* Ao final apresentar um gráfico QUANTIDADE DE ACÓRDÃOS que tratem do assunto por ANO
>-----------

## 👨‍🏫 Orientadores
>
> MSc. André Luiz Firmino Alves - Professor, Orientador e Coordenador do Curso
>
> Dr. Geraldo Braz Junior - Professor e Orientador
>
>-----------

## ✒️ Integrantes do Grupo
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

## 📦 Implantação
> Python, PANDAS, Expressão Regular
>
>-----------

## A) Etapas do pré-processamento
>
>1) Fazer a leitura dos Acórdãos que estão em pdfs e exportar para uma planilha xls.
>   A planilha terá as seguintes colunas ID, ACORDAO, DIA, CONTEUDO.
>2) Retirar NAN'S - utilizando o dataset do PANDAS
>3) Retirar registros que não foram encontrados Data do Acórdão e Número do Acórdão
>4) Corrigir o indice após a exclusão de registros para que este seja sequêncial e facilite o laço (for) na próxima etapa
>5) Retirar texto inicial e final no conteúdo, restringindo o texto que será objeto do estudo
   
## B) Normalização
>7) Transformar em letras minúsculas
>8) Remover pontuação e caracteres especiais do campo conteudo

## C) Tokenização
>9) dividir em palavras 

## D) N-Grams
>10) Definir o número de GRAMS

## E) StopWords
>11) Retirar palavras não relevantes ao treinamento de máquina

## F) Stemming e Lemmatization
>
## G) Bag of Words
>
## H) Plotagem de Gráfico
>
## i) Conclusões Finais
> Fazer sugestões na padronização dos Acórdãos, com o objetivo a contribuir na extração futura de informações em Acórdãos do TCE/AC e outros Tribunais de Contas.

>-----------
## 🎁 Agradecimento pessoal
> 1) Agradecemos nosso colega [Wisley de Oliveira Bandeira](https://www.linkedin.com/in/wisleybandeira/) por ter conseguido os PDF's dos Acórdãos que possibilitou sairmos na frente neste projeto, sem isso não seria possível trabalharmos, estudar e ainda coletarmos os Acórdãos nescessários ao projeto.
> 2) Agradecemos a todos os professores do curso *"Business Intelligence e Ciência de Dados"* por compartilhar seus conhecimentos, em especial à nossos orientadores André Luiz Firmino Alves, Geraldo Braz Junior e ao professor Dr. [Cláudio de Souza Baptista](https://www.linkedin.com/in/claudio-de-souza-baptista-07257721a/).
> 
## 🎁 Agradecimentos as Instituições
[<img src= "https://tceac.tc.br/site/wp-content/uploads/2023/05/LOGO-VERSAO-PREFERENCIAL.png" width="150" alt="Tribunal de Contas do Estado do Acre"/>](https://tceac.tc.br/site/)
[<img src= "https://www.ufpb.br/ufpb/image-base/brasaooficial.png/@@images/1abe9a91-1d77-4443-898e-f14c006fbc43.png" width="110" alt="Universidade Federal da Paraíba"/>](https://www.ufpb.br/)
[<img src= "https://moodle.tceac.tc.br/pluginfile.php/1/theme_adaptable/favicon/1706543109/WhatsApp%20Image%202020-01-30%20at%2009.49.09.jpeg" width="130" alt="Escola de Contas Conselheiro Alcides Dutra de Lima"/>](https://moodle.tceac.tc.br/)
> Agradecemos ao Tribunal de Contas do Estado do Acre, a Escola de Contas Conselheiro Alcides Dutra de Lima e a Universidade Federal da Paraíba que possibilitaram o curso *"Business Intelligence e Ciência de Dados"* (2023-2024).
>
## Módulos do Curso "Business Intelligence e Ciência de Dados"
1. INTRODUÇÃO A BI E CIÊNCIA DE DADOS 
2. INTRODUÇÃO À PROGRAMAÇÃO COM PYTHON 
3. PROGRAMAÇÃO PYTHON PARA CIÊNCIA DE DADOS 
4. GESTÃO DE DADOS RELACIONAIS EM CIÊNCIA DE DADOS 
5. INTRODUÇÃO À INTELIGÊNCIA ARTIFICIAL - IA 
6. PREDIÇÃO E CLASSIFICAÇÃO e SÉRIES TEMPORAIS 
7. REDES NEURAIS ARTIFICIAIS E REGRAS DE ASSOCIAÇÃO 
8. BUSINESS INTELLIGENCE COM POWER BI 
9. INTRODUÇÃO À PROCESSAMENTO DE LINGUAGEM NATURAL 
10. RECUPERAÇÃO DA INFORMAÇÃO
11. APRENDIZAGEM PROFUNDA (DEEP LEARNING) 
12. PROJETO EM CIÊNCIA DE DADOS



