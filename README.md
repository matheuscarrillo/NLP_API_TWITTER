# NLP_API_TWITTER
Projeto de NLP utilizando dados do Twitter. A ideia do projeto é, utilizar conceitos de NLP e tratamento de dados, além da tecnologia de Python. 

Neste projeto, é extraído cerca de 5000 twittes via API, que foi criada pelo site https://developer.twitter.com/, onde é necessário criar uma aplicação que gera um client_id, client_secret e um bearer_token, para realizar a autenticação na ferramenta. 

Ao executar o notebook, o usuário insere qual será a hashtag a ser procurada e N tópicos focais, no qual será utilizado pela aplicação. Em seguinda, o script demonstra a quantidade de menções para cada tópico, evolução durante os dias, wordcloud para cada tópico, considerando as principais palavras e por fim, é gerado um LDA de N grupos (definido pelo usuário no inicio) com as top15 palavras que foram utilizadas para a criação dos grupos.
