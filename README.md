# Projeto Leitura de Documentos

> ## 🎓 Trabalho Final do Curso: 
> - Business Intelligence e Ciência de Dados

> ## 🚀 Objetivo:
> - [x] Fazer a leitura de Acórdãos do Tribunal de Contas do Estado do Acre, que inicialmente encontram-se em PDF's
> - [x] Extrair informações relativas a número do acórdão, data do julgamento, e conteúdo do Acórdão.
> - [X] Criar a indexação com base no conteúdo dos Acórdãos para filtrar por assunto abordado.
> - [X] Apresentar um gráfico que apresente a QUANTIDADE DE ACÓRDÃOS que tratou do assunto (filtro) por ANO
> - [X] Comentar o que podemos apurar com o gráfico apresentado
> - [X] Sugestões para uma padronização de Acórdão 

> ## 💼 Orientadores:
>   - MSc. André Luiz Firmino Alves - Coordenador do Curso
>   - Dr.  [Geraldo Braz Júnior](https://www.linkedin.com/in/geraldo-braz-junior-4821778b/) 

> ## 👨‍🏫 Professores:
>   - André Luiz Firmino Alves (Coordenador do Curso)
>   - Anderson Almeida Firmino
>   - Anselmo Cardoso de Paiva
>   - Cláudio de Souza Baptista
>   - [Geraldo Braz Júnior](https://www.linkedin.com/in/geraldo-braz-junior-4821778b/) 
>   - João Dallyson Sousa de Almeida
>   - Mateus Queiroz Cunha

> ## ✒️ Integrantes do Grupo:
>   - [Antonino Marques Jares](https://www.linkedin.com/in/antonino-marques-jares-b447a734/)
>   - [Jamile Santos do Vale](https://www.linkedin.com/in/jamille-santos-3a9b76183/?originalSubdomain=br)  - TCE/AC
>   - José Coca Carrascosa Neto - MP/AC
>   - [Wallison Santos Ferreira](https://www.linkedin.com/in/wallisonferreira09/) - MP/AC


> ## 📄 Licença:
>   - Todos os Acórdãos do TCE/AC utilizados neste projeto já foram publicados

> ## 📦 Implantação:
>  [<img src= "https://freepngimg.com/thumb/python_logo/7-2-python-logo-free-download-png.png" width="60" alt="Python"/>](https://www.python.org/)
>  [<img src= "https://miro.medium.com/v2/resize:fit:720/format:webp/0*RWkQ0Fziw792xa0S" width="80" alt="Pandas"/>](https://pandas.pydata.org/) 
>  [<img src= "https://static.javatpoint.com/tutorial/regex/images/regex-tutorial.png" width="60" alt="Expressão Regular"/>](https://pypi.org/project/regex/) 
>  [<img src= "https://icons.veryicon.com/png/o/miscellaneous/2022-complete-collection-of-alibaba-cloud/nlp-ke-headword-extraction-1.png" width="60" alt="Processamento de Linguagem Natural"/>](https://www.veryicon.com/) 
>  
>  **Python**, **Pandas**, **Expressão Regular** e **Processamento de Linguagem Natural**


> ## 👥 Plataforma de código-fonte compartilhado em nuvem:
>  [<img src= "https://github.githubassets.com/assets/GitHub-Mark-ea2971cee799.png" width="60" alt="Expressão Regular"/>](https://github.com/) 
>  
>  **GitHub**

> [!TIP]
> 
> Para evitarmos confitos no GitHub, cada módulo criou um arquivo csv como resultado e **definimos o responsável por cada módulo**.
> 
> Desta forma fizemos um **tipo de linha de montagem**, onde cada módulo ficou independente de influência externas mas **podendo acessar as informações do módulo anterior por um arquivo csv**.
> 
> Este processo **garante que não teremos conflitos em linhas de código** e com isso ganhamos tempo na implementação.

> ## Etapa 01 - Antonino Marques Jares:
> - [X] Fazer a leitura dos Acórdãos que estão em pdfs e exportar para uma planilha csv.
> - [X] A planilha terá as seguintes colunas ID, ACORDAO, DIA, CONTEUDO.
> - [X] Retirar NAN'S - devido a PDF's ainda estarem scaneados como imagens - utilizando o dataset do PANDAS
> - [X] Retirar registros que não foram encontrados Data do Acórdão e Número do Acórdão
> - [X] Corrigir o indice após a exclusão de registros para que este seja sequêncial e facilite o laço (for) na próxima etapa
> - [X] Retirar texto inicial e final no conteúdo, restringindo o texto que será objeto do estudo
> - [X] Normalização - Transformar em letras minúsculas
> - [X] Normalização - Remover pontuação e caracteres especiais do campo conteudo

> [!IMPORTANT]
> 
> PDF's que estejam ainda em imagem podem ser lidos pela biblioteca Tesseract com Python, contudo, optamos neste projeto dar continuidade com os Acórdãos restantes.
> 
> Tendo em vista que temos Acórdãos suficientes que conseguimos fazer a leitura do texto e nosso foco no projeto está na analise NLP.

> [!Caution]
> 
> A ordem em que é executado as Expressões Lineares é muito importante.
>
> Esta etapa deve ser bem planejada, para conseguir o melhor resultado.

> [!TIP]
> 
> Recomendamos o site [regular expressions 101](https://regex101.com/) para fazer testes de Expressão Regular

> [!IMPORTANT]
> 
> Nesta fase de Expressões Regulares perceberemos que a falta de padrões no texto muitas vezes inviabilizam ou dificultam a extração das informações.
>
> Ao final do projeto falaremos das dificuldades encontradas.

> ## Etapa 02 - Wallison Santos Ferreira:
> - [ ] Tokenização
> - [ ] N-Grams
> - [ ] StopWords
> - [ ] Stemming e Lemmatization
> - [ ] Bag of Words
> ## Etapa 03 - José Coca Carrascosa Neto:
> - [ ] Plotagem de Gráfico apresentando QUANTIDADE DE ACÓRDÃOS que tenham o ASSUNTO (**filtro**) por ANO
> ## Etapa 04 - Apresentação - Jamile Santos do Vale:
> - [ ] Conferência
> - [ ] Slides da apresentação
> ## Etapa Final - Conclusão com todos os integrantes:
> - [ ] Analise em relação ao gráfico apresentado


> ## 🎁 Nosso agradecimento pessoal:
>  1) Agradecemos nosso colega [Wisley de Oliveira Bandeira](https://www.linkedin.com/in/wisleybandeira/) por ter conseguido os PDF's dos Acórdãos que possibilitou sairmos na frente neste projeto, sem isso não seria possível trabalharmos, estudar e ainda coletarmos os Acórdãos nescessários ao projeto.
>  2) Agradecemos a todos os professores do curso *"Business Intelligence e Ciência de Dados"* por compartilharem seus conhecimentos, em especial à nossos orientadores André Luiz Firmino Alves, [Geraldo Braz Júnior](https://www.linkedin.com/in/geraldo-braz-junior-4821778b/)  e ao professor Dr. [Cláudio de Souza Baptista](https://www.linkedin.com/in/claudio-de-souza-baptista-07257721a/), que sempre foram muito atenciosos.


 
> ## 🎁 Nosso agradecimento as Instituções:
[<img style="color:blue" src= "[https://tceac.tc.br/site/wp-content/uploads/2023/05/LOGO-VERSAO-PREFERENCIAL.png](https://www.paqtc.org.br/images/logo.png)" width="150" alt="Parque Tecnológico da Paraíba"/>](https://www.paqtc.org.br/images/logo.png)
[<img src= "https://tceac.tc.br/site/wp-content/uploads/2023/05/LOGO-VERSAO-PREFERENCIAL.png" width="150" alt="Tribunal de Contas do Estado do Acre"/>](https://tceac.tc.br/site/)
[<img src= "https://www.ufpb.br/ufpb/image-base/brasaooficial.png/@@images/1abe9a91-1d77-4443-898e-f14c006fbc43.png" width="110" alt="Universidade Federal da Paraíba"/>](https://www.ufpb.br/)
[<img src= "https://moodle.tceac.tc.br/pluginfile.php/1/theme_adaptable/favicon/1706543109/WhatsApp%20Image%202020-01-30%20at%2009.49.09.jpeg" width="130" alt="Escola de Contas Conselheiro Alcides Dutra de Lima"/>](https://moodle.tceac.tc.br/)


> [!IMPORTANT]
> 
> Agradecemos ao **Tribunal de Contas do Estado do Acre**, a **Escola de Contas Conselheiro Alcides Dutra de Lima** e a **Universidade Federal da Paraíba** que nos possibilitaram o curso *"Business Intelligence e Ciência de Dados"* (2023-2024).

> [!NOTE]
> 
> Módulos do Curso "Business Intelligence e Ciência de Dados"
>   - INTRODUÇÃO A BI E CIÊNCIA DE DADOS 
>   - INTRODUÇÃO À PROGRAMAÇÃO COM PYTHON 
>   - PROGRAMAÇÃO PYTHON PARA CIÊNCIA DE DADOS 
>   - GESTÃO DE DADOS RELACIONAIS EM CIÊNCIA DE DADOS 
>   - INTRODUÇÃO À INTELIGÊNCIA ARTIFICIAL - IA 
>   - PREDIÇÃO E CLASSIFICAÇÃO e SÉRIES TEMPORAIS 
>   - REDES NEURAIS ARTIFICIAIS E REGRAS DE ASSOCIAÇÃO 
>   - BUSINESS INTELLIGENCE COM POWER BI 
>   - INTRODUÇÃO À PROCESSAMENTO DE LINGUAGEM NATURAL 
>   - RECUPERAÇÃO DA INFORMAÇÃO
>   - APRENDIZAGEM PROFUNDA (DEEP LEARNING) 
>   - PROJETO EM CIÊNCIA DE DADOS




