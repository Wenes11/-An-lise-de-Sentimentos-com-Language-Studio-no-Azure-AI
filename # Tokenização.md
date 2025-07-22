**# Tokenização**



é o processo de dividir um texto em partes menores chamadas tokens, que podem ser palavras, subpalavras ou até mesmo caracteres, dependendo da abordagem.



**Por exemplo, a frase:**



**"Eu amo jogar futebol igual eu amo a minha família"**



**Pode ser tokenizada como:**

**\["eu", "amo", "jogar", "futebol", "igual", "eu", "amo", "a", "minha", "família"]**



Em algumas aplicações de NLP, como o uso de embeddings ou redes neurais, cada palavra recebe um identificador numérico com base em um vocabulário\*\*:\*\*



**{"eu":1, "amo":2, "jogar":3, "futebol":4, "igual":5, "a":6, "minha":7, "família":8}**



**Então, o texto vira uma sequência de inteiros:**

**\[1, 2, 3, 4, 5, 1, 2, 6, 7, 8]**



Esse processo é essencial para que o texto possa ser processado computacionalmente, permitindo a manipulação, análise e treinamento de modelos de linguagem.

