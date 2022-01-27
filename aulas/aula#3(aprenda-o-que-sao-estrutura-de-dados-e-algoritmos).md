# ⭐Aula 3 - Aprenda o que são Estrutura de Dados e Algoritmos

- [x] Assistida

**Data:** 25/01/2022 | **Tempo:** 2h 

**Tópicos:**

- 1 - Conceitos iniciais sobre estrutura de dados, arrays e registro 
- 2 - Entenda o que são Listas, Pilhas e Filas 
- 3 - Estrutura de dados do tipo Árvore, Tabelha Hash e Grafos



## Tópico 1

**Estrutura de dados -** Estrutura organizada de dados na memória de um computador ou em qualquer dispositivo de armazenamento, de forma que os possam ser utilizados de forma correta.

**Principais estruturas de dados -** Vetores e matrizes (arrays, uni-dimensional e multi-dimensional), registro, lista, pilha, fila, árvore, tabela hash, grafos.

**Arrays -** Auxiliam quando há muitas variáveis do mesmo tipo em um algoritmo.

numeros[ ] = {1, 2, 3, 4} 

**Registro -** Estrutura que fornece um formato especializado para armazenar informações em memória. Nos permite armazenar mais de um tipo de dado. Composto por campos que especificam cada uma das informações que o compõem. Cada registro e campo tem seu nome e podem ser acessados por ponto (livro.preco).

estrutura_livro = registro 
    nome : caracter 
    preco : real 
    pagina : inteiro



## Tópico 2

**Listas -** Armazenam dados de um determinado tipo e ordem específica. A diferença entre arrays é que as listas possuem tamanho ajustável, arrays possuem tamanho fixo. Vai recebendo valores, crescendo ou diminuindo. Existem as ligadas e duplamente ligadas.

- **Ligadas:** Formada por nós (índices) onde cada um deles conhece o valor que está sendo armazenado em seu interior, além de conhecer o próximo elemento posterior a ele. 
- **Duplamente ligadas:** Variação das listas ligadas. Bidirecional. Sabem qual é o próximo elemento e o elemento anterior, permitindo navegação reversa.

**Pilhas (Stack) -** Serve como coleção de elementos e permite acesso a somente um dos dados armazenados. Acesso restrito, somente um item pode ser lido ou removido por vez. Há dois tipos, LIFO ou UEPS e FIFO ou PEPS.

- **LIFO (last in first out):** O primeiro elemento a ser retirado é o último que tiver sido inserido. 
- **FIFO (first in first out):** O primeiro elemento a ser retirado é o primeiro que tiver sido inserido.

**Filas -** Admite a remoção de elementos e inserção de novos elementos com a regra: o elemento removido é o que está na estrutura há mais tempo, ou seja, o primeiro objeto inserido na fila é também o primeiro a ser removido (conceito FIFO).



## Tópico 3

**Árvores -** Organiza seus elementos de forma hierárquica, onde existe um elemento que fica no topo da ávore, chamado de raiz, tendo subelementos, que são chamados de nós ou folhas. Facilita a busca.

**Tabelas Hash -** Dispersão ou espalhamento. Associa chaves de pesquisa a valores. Generalização da ideia do array. Utiliza função Hashing para espalhar os elementos, fazendo com que os mesmos fiquem de forma não ordenada dentro do “array” que define a tabela. Espalhar facilita a busca, pois a partir de uma chave podemos acessar o valor mais facilmente. Cada valor recebe uma chave.

**Grafos -** Permitem programar a relação entre objetos. Os objetos são vértices ou nós do grafo. Os relacionamentos são as arestas. Permite fazer qualquer tipo de estrutura e qualquer tipo de busca.
