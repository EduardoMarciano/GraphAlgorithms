# Implemetação de Clássicos Algoritmos de Grafos.
 
  Este repositório apresenta a implementação de 20 algoritmos da Teoria de Grafos, os quais foram abordados na disciplina CIC0199 - Teoria e Aplicação de Grafos da Universidade de Brasília. Cada algoritmo é desenvolvido utilizando uma abordagem orientada a objetos, buscando promover a organização e a facilidade da estruturas dos algoritmos. Todos os grafos foram implementados utilizando a linguagem de programação python.

## Algoritmos Implementados:

 Os algoritmos implementados abrangem diversas áreas da Teoria de Grafos, oferecendo uma ampla gama de soluções para problemas do mundo real. Para cada algoritmo, são fornecidos exemplos de sua aplicação, simualando situações comuns encontradas na sociedade e que podem ser úteis para empresas de diversos setores.
  
  ### Algoritmo de Busca em Profundidade
 Método de travessia de grafos, o qual percorre todos os vêrtices de um grafo descobrindo seus vêrtices. Ao começar em um vértice inicial, explora o máximo possível de cada ramificação antes de realizar um backtrack. Esse algoritmo é implementado de forma recursiva com o auxílio de uma pilha sendo amplamente utilizado em problemas de caminhos, conectividade e identificação de componentes conectados em um grafo.

  Ordem de Complexabilidade: O(V + E)
  
  Repositório do Algoritmo:
  
  ### Algoritmo de Busca em Largura
 Método de travessia de grafos, o qual explora todos os vértices vizinhos de um vértice inicial antes de se mover para os vértices adjacentes a esses vizinhos. Ele utiliza uma estrutura de fila para rastrear os vértices a serem visitados, garantindo que todos os vértices acessíveis a partir do ponto inicial sejam alcançados sendo amplamente utilizado em problemas de caminhos, conectividade e identificação de componentes conectados em um grafo.

  Ordem de Complexabilidade: O(V + E)

  Repositório do Algoritmo:
  
  ### Algoritmo de Dijkstra
 Algoritmo de busca do caminho mais curto em um grafo ponderado não direcionado ou direcionado com pesos não negativos. Ele determina o caminho mais curto de um vértice de origem para todos os outros vértices no grafo, fornecendo uma árvore de caminho mínimo. É amplamente aplicado em problemas de roteamento de rede, transporte e otimização de caminhos.

  Ordem de Complexabilidade: O(V^2)
  
  Repositório do Algoritmo:
  
  ### Algoritmo de Bellman-Ford
  É usado para encontrar o caminho mais curto entre um vértice de origem e todos os outros vértices em um grafo ponderado, permitindo a existência de pesos negativos nas arestas. Ele itera repetidamente através de todas as arestas, relaxando-as, até garantir que todas as distâncias possíveis tenham sido otimizadas. É uma escolha eficaz quando o grafo contém arestas de peso negativo.
  
  Ordem de Complexabilidade: O(V * E)
  
  Repositório do Algoritmo:
  
  ### Algoritmo de Floyd-Warshall
  O algoritmo é usado para encontrar os caminhos mais curtos entre todos os pares de vértices em um grafo ponderado, inclusive para grafos com pesos negativos. Ele cria uma matriz de distâncias mínimas, onde cada elemento representa a menor distância entre dois vértices.

  Ordem de Complexabilidade: O(V^3) 

  Repositório do Algoritmo:
  
  ### Algoritmo de Bron-Kerbosch
  Usado para encontrar todos os cliques máximos em um grafo não direcionado. Ele utiliza uma abordagem de busca recursiva que explora todas as combinações possíveis de cliques enquanto evita a formação de cliques inválidos.

  Ordem de Complexabilidade: O(3^(V/3))
  
  Repositório do Algoritmo:
  
  ### Algoritmo de Ordenação Topológica Kahn’s (BFS)
  Usado para encontrar uma ordenação linear dos vértices de um grafo direcionado acíclico (DAG), de modo que todas as arestas sigam a direção estabelecida pela ordenação. Ele utiliza uma abordagem baseada em fontes, onde os vértices sem dependências (sem arestas de entrada) são processados primeiro e removidos do grafo, resultando em uma sequência topológica válida.

  Ordem de Complexabilidade: O(V + E)
  
  Repositório do Algoritmo: https://github.com/EduardoMarciano/Topological-path-of-a-Graph-DAG-BFS/tree/main
  
  ### Algoritmo de Ordenação Topológica (DFS)
  É uma abordagem alternativa ao algoritmo de Kahn. Ele também é usado para encontrar uma ordenação linear dos vértices em um grafo direcionado acíclico (DAG), mas em vez de usar fontes, esse algoritmo explora os vértices em profundidade, marcando-os como visitados após a exploração completa de seus descendentes. A ordem inversa de visitação é a ordenação topológica desejada.

  Ordem de Complexabilidade: O(V + E)
  
  Repositório do Algoritmo: https://github.com/EduardoMarciano/Topological-path-of-a-Graph-DAG-DFS
  
  ### Algoritmo de Caminho Crítico
  É comumente aplicado em gerenciamento de projetos e programação linear. Ele determina o caminho mais longo (duração máxima) em um gráfico ponderado direcionado acíclico (DAG), representando a sequência de atividades em um projeto e suas dependências. Ao identificar o caminho crítico, é possível identificar as atividades que possuem o maior impacto na duração total do projeto.

  Ordem de Complexabilidade: O(V + E)
  
  Repositório do Algoritmo: https://github.com/EduardoMarciano/Critical-Path-Method-CPM
  
  ### Algoritmo Kosaraju-Sharir
   É utilizado para encontrar componentes fortemente conectados em um grafo direcionado. Ele emprega duas passagens de busca em profundidade: na primeira, a ordem topológica é determinada; na segunda, os componentes fortemente conectados são identificados com base na ordem inversa da primeira passagem. É uma ferramenta essencial para resolver problemas relacionados a conectividade e análise de redes complexas.

  Ordem de Complexabilidade: O(V + E)
  
  Repositório do Algoritmo:
  
  ### Algoritmo de Prim
 É utilizado para encontrar a árvore geradora mínima em um grafo. Ele começa com um vértice inicial e adiciona iterativamente a aresta de menor peso que conecta um vértice na árvore ao vértice fora da árvore, expandindo a árvore gradualmente até que todos os vértices estejam incluídos. É uma abordagem eficiente para encontrar o caminho mais curto em uma rede conectada.

  Ordem de Complexabilidade: O(V^2)
 
  Repositório do Algoritmo:
  
  ### Algoritmo de Kruskal
  É usado para encontrar a árvore geradora mínima em um grafo conexo. Em vez de começar com um vértice específico, ele ordena todas as arestas por peso e as adiciona à árvore geradora se não formarem ciclos. O processo continua até que todos os vértices estejam conectados em uma única árvore, resultando na árvore geradora mínima. É uma abordagem eficiente para conectar nós em um grafo de maneira econômica, como em problemas de projeto de redes de comunicação ou transporte.

  Ordem de Complexabilidade: O(E * log E)

  Repositório do Algoritmo:
  
  ### Algoritmo de determinação de Grafos Bipartidos
  É baseado em uma abordagem de busca em largura (BFS). Ele atribui cores alternadas aos vértices enquanto os explora, garantindo que nenhum vértice vizinho tenha a mesma cor. Se o algoritmo conseguir colorir todos os vértices sem violar essa regra, o grafo é considerado bipartido. Caso contrário, ele contém um ciclo ímpar e, portanto, não é bipartido.

  Ordem de Complexabilidade: O(V + E)
  
  Repositório do Algoritmo:
  
  ### Algoritmo de Emparelhamento
  É utilizado para encontrar emparelhamentos máximos (ou máximos-cardinalidade) em um grafo não direcionado. Ele busca combinar o máximo possível de arestas sem que elas compartilhem vértices em comum.

  Ordem de Complexabilidade: O(E * V)

  Repositório do Algoritmo:
  
  ### Algoritmo de Gale-Shapley
  É usado para resolver o problema de casamento estável em teoria dos jogos e teoria dos casamentos. Ele permite que um dois grupos escolham os melhores candidatos para si, permitindo trocas entre os vêrtices, até que se encontre uma combinação estável onde nehuma troca mais seja aceita. 

  Ordem de Complexabilidade: O(V^2)
  
  Repositório do Algoritmo:
  
  ### Algoritmo Húngaro
 É usado para resolver o problema de atribuição, que envolve encontrar o melhor emparelhamento entre dois conjuntos de elementos com base em seus custos ou pesos. Ele utiliza programação dinâmica para determinar o emparelhamento ótimo.
  
  Ordem de Complexabilidade: O(V^3)
  
  Repositório do Algoritmo:
  
  ### Algoritmo de Caminhos aumentados
  É usado em problemas de fluxo máximo em redes. A abordagem consiste em encontrar caminhos aumentados, que são caminhos da fonte ao sumidouro ao longo dos quais o fluxo pode ser aumentado. Repetidamente encontrando caminhos aumentados e ajustando o fluxo, o algoritmo encontra o fluxo máximo na rede.
  
  Ordem de Complexabilidade: O(E * V)
  
  Repositório do Algoritmo:
  
  ### Algoritmo de Ford-Fulkerson
  É um método clássico para resolver o problema de fluxo máximo em uma rede. Ele aumenta o fluxo de forma iterativa, encontrando caminhos aumentados que vão da fonte ao sumidouro, modificando o fluxo ao longo desses caminhos para aumentar o fluxo total. O algoritmo termina quando não há mais caminhos aumentados, resultando no fluxo máximo na rede.

  Ordem de Complexabilidade: O(E * max_flow)
  
  Repositório do Algoritmo:
  
  ### Algoritmo de Edmonds-Karp
  É uma variação do algoritmo Ford-Fulkerson que utiliza a busca em largura (BFS) para encontrar caminhos aumentados de forma mais eficiente. Ele é usado para calcular o fluxo máximo. A busca em largura ajuda a garantir que a capacidade do caminho aumentado encontrado seja totalmente utilizada, o que melhora a convergência do algoritmo em comparação com o Ford-Fulkerson tradicional.

  Ordem de Complexabilidade: O(V * E^2)
  
  Repositório do Algoritmo:
  
  ### Algoritmo de Coloração Guloso
  É usado para atribuir cores a vértices de um grafo de forma que vértices adjacentes não tenham a mesma cor. Ele faz isso selecionando cada vértice e atribuindo a menor cor possível que não entra em conflito com as cores de seus vizinhos já coloridos. O algoritmo continua até que todos os vértices sejam coloridos. Embora seja fácil de implementar, o resultado pode não ser sempre o ótimo, mas é uma heurística rápida e eficiente para muitos problemas de coloração.

  Ordem de Complexabilidade: O(V + E)
  
  Repositório do Algoritmo:
