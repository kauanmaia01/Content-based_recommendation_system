# Sistema de recomendação(Content-Based Filtering)

A filtragem baseada em conteúdo em sistemas de recomendação utiliza algoritmos de aprendizado de máquina para prever e sugerir itens novos que sejam semelhantes aos que o usuário já demonstrou interesse. Para que seja possível recomendar produtos com base em suas características, é necessário dispor de um conjunto claro de atributos do produto e uma lista das escolhas prévias do usuário.

Utilizei o **TfidfVectorizer** para fazer o pré-processamento dos dados que faz parte da biblioteca Scikit-Learn é uma técnica estatística que calcula a importância relativa das palavras em um documento com base em quantas vezes aparecem nesse documento e em quantos documentos da coleção a palavra ocorre.

E também usei o **cosine_similary** da biblioteca Scikit-Learn que utiliza uma métrica que calcula a semelhança entre dois vetores, medindo o cosseno do ângulo entre eles. No meu caso, a similaridade cosseno foi calculada com base na representação TF-IDF gerada pelo TfidVectorizer.

Veja o contexto e objetivo do projeto no meu [LinkedIn](https://www.linkedin.com/in/kauanmaia/)

O objetivo deste projeto foi práticar minhas habilidades com a biblioteca [Scikt-Learn](https://scikit-learn.org/stable/index.html#).

## Utilização

Para executar o algoritmo, siga os seguintes passos:

1. Execute as células do arquivo `notebook.ipynp`.

2. Coloque o nome do filme desejado.

![exemplo](image/code.png)

Muito obrigado! Para mais projetos, confira meu repositório.

[Link para o repositório](https://github.com/kauanmaia01)
