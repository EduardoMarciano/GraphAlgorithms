# Implemetação de Algoritmos Clássicos de Grafos com Python.
 
 ### Este repositório apresenta a implementação de 20 algoritmos clássicos da Teoria de Grafos, que foram abordados na disciplina CIC0199 - Teoria e Aplicação de Grafos da Universidade de Brasília. Cada algoritmo é desenvolvido utilizando uma abordagem orientada a objetos, buscando promover a organização e a facilidade da estruturas dos algorítmos.

# Algoritmos Implementados:

### Os algoritmos implementados abrangem diversas áreas da Teoria de Grafos, oferecendo uma ampla gama de soluções para problemas do mundo real. Para cada algoritmo, são fornecidos exemplos de sua aplicação, simuando situações comuns encontradas na sociedade e que podem ser úteis para empresas de diversos setores.
  
  ## Algoritmo de Busca em Profundidade
  método de travessia de grafos que começa em um vértice inicial e explora o máximo possível ao longo de cada ramificação antes de retroceder. Esse algoritmo é implementado de forma recursiva ou com o auxílio de uma pilha e é amplamente utilizado em problemas de caminhos, conectividade e identificação de componentes conectados em um grafo.

  Repositório do Algoritmo:
  
  ## Algoritmo de Busca em Largura
  A busca em largura é um algoritmo de travessia de grafos que explora todos os vértices vizinhos de um vértice inicial antes de se mover para os vértices adjacentes a esses vizinhos. Ele utiliza uma estrutura de fila para rastrear os vértices a serem visitados, garantindo que todos os vértices acessíveis a partir do ponto inicial sejam alcançados. É frequentemente usado para encontrar o caminho mais curto entre dois vértices ou para identificar a existência de um caminho em um grafo.

  Repositório do Algoritmo:
  
  ## Algoritmo de Dijkstra
  O algoritmo de Dijkstra é um algoritmo de busca de caminho mais curto em um grafo ponderado não direcionado ou direcionado com pesos não negativos. Ele determina o caminho mais curto de um vértice de origem para todos os outros vértices no grafo, fornecendo uma árvore de caminho mínimo. É amplamente aplicado em problemas de roteamento de rede, transporte e otimização de caminhos.

  Repositório do Algoritmo:
  
  ## Algoritmo de Bellman-Ford
  O algoritmo Bellman-Ford é usado para encontrar o caminho mais curto entre um vértice de origem e todos os outros vértices em um grafo ponderado, permitindo a existência de pesos negativos nas arestas. Ele itera repetidamente através de todas as arestas, relaxando-as, até garantir que todas as distâncias possíveis tenham sido otimizadas. É uma escolha eficaz quando o grafo contém arestas de peso negativo, mas requer mais tempo de execução em comparação com o algoritmo de Dijkstra.

  Repositório do Algoritmo:
  
  ## Algoritmo de Floyd-Warshall
  O algoritmo Floyd-Warshall é usado para encontrar os caminhos mais curtos entre todos os pares de vértices em um grafo ponderado, inclusive para grafos com pesos negativos. Ele cria uma matriz de distâncias mínimas, onde cada elemento representa a menor distância entre dois vértices. O algoritmo é adequado para pequenos grafos, pois possui uma complexidade de tempo de O(V^3), sendo V o número de vértices no grafo.

  Repositório do Algoritmo:
  
  ## Algoritmo de Bron-Kerbosch
  usado para encontrar todos os cliques máximos em um grafo não direcionado. Ele utiliza uma abordagem de busca recursiva que explora todas as combinações possíveis de cliques enquanto evita a formação de cliques inválidos, garantindo uma complexidade razoável em grafos relativamente pequenos.
  
  Repositório do Algoritmo:
  
  ## Algoritmo de Ordenação Topológica Kahn’s (BFS)
  O algoritmo de ordenação topológica de Kahn é usado para encontrar uma ordenação linear dos vértices de um grafo direcionado acíclico (DAG), de modo que todas as arestas sigam a direção estabelecida pela ordenação. Ele utiliza uma abordagem baseada em fontes, onde os vértices sem dependências (sem arestas de entrada) são processados primeiro e removidos do grafo, resultando em uma sequência topológica válida.

  Repositório do Algoritmo:
  
  ## Algoritmo de Ordenação Topológica (DFS)
  O algoritmo de ordenação topológica baseado em busca em profundidade (DFS) é uma abordagem alternativa ao algoritmo de Kahn. Ele também é usado para encontrar uma ordenação linear dos vértices em um grafo direcionado acíclico (DAG), mas em vez de usar fontes, esse algoritmo explora os vértices em profundidade, marcando-os como visitados após a exploração completa de seus descendentes. A ordem inversa de visitação é a ordenação topológica desejada.

  Repositório do Algoritmo:
  
  ## Algoritmo de Caminho Crítico
  O algoritmo de caminho crítico é comumente aplicado em gerenciamento de projetos e programação linear. Ele determina o caminho mais longo (duração máxima) em um gráfico ponderado direcionado acíclico (DAG), representando a sequência de atividades em um projeto e suas dependências. Ao identificar o caminho crítico, é possível identificar as atividades que possuem o maior impacto na duração total do projeto.

  Repositório do Algoritmo:
  
  ## Algoritmo Kosaraju-Sharir
  O algoritmo de Kosaraju-Sharir é utilizado para encontrar componentes fortemente conectados em um grafo direcionado. Ele emprega duas passagens de busca em profundidade: na primeira, a ordem topológica é determinada; na segunda, os componentes fortemente conectados são identificados com base na ordem inversa da primeira passagem. É uma ferramenta essencial para resolver problemas relacionados a conectividade e análise de redes complexas.

  Repositório do Algoritmo:
  
  ## Algoritmo de Prim
  O algoritmo de Prim é utilizado para encontrar a árvore geradora mínima em um grafo conexo e não direcionado com pesos. Ele começa com um vértice inicial e adiciona iterativamente a aresta de menor peso que conecta um vértice na árvore ao vértice fora da árvore, expandindo a árvore gradualmente até que todos os vértices estejam incluídos. É uma abordagem eficiente para encontrar o caminho mais curto em uma rede conectada.

  Repositório do Algoritmo:
  
  ## Algoritmo de Kruskal
  O algoritmo de Kruskal também é usado para encontrar a árvore geradora mínima em um grafo conexo e não direcionado com pesos. Em vez de começar com um vértice específico, ele ordena todas as arestas por peso e as adiciona à árvore geradora se não formarem ciclos. O processo continua até que todos os vértices estejam conectados em uma única árvore, resultando na árvore geradora mínima. É uma abordagem eficiente para conectar nós em um grafo de maneira econômica, como em problemas de projeto de redes de comunicação ou transporte.

  Repositório do Algoritmo:
  
  ## Algoritmo de determinação de Grafos Bipartidos
  O algoritmo para determinar se um grafo é bipartido é geralmente baseado em uma abordagem de busca em largura (BFS) ou busca em profundidade (DFS). Ele atribui cores alternadas aos vértices enquanto os explora, garantindo que nenhum vértice vizinho tenha a mesma cor. Se o algoritmo conseguir colorir todos os vértices sem violar essa regra, o grafo é considerado bipartido. Caso contrário, ele contém um ciclo ímpar e, portanto, não é bipartido.

  Repositório do Algoritmo:
  
  ## Algoritmo de Emparelhamento
  O algoritmo de emparelhamentos é utilizado para encontrar emparelhamentos máximos (ou máximos-cardinalidade) em um grafo não direcionado. Ele busca combinar o máximo possível de arestas sem que elas compartilhem vértices em comum. Os algoritmos para encontrar emparelhamentos podem ser eficientes, como o algoritmo de Edmonds e o algoritmo de Hopcroft-Karp.

  Repositório do Algoritmo:
  
  ## Algoritmo de Gale-Shapley
  O algoritmo de Gale-Shapley, também conhecido como o algoritmo de casamento estável, é usado para resolver o problema de casamento estável em teoria dos jogos e teoria dos casamentos. Ele permite que um grupo de homens e mulheres indiquem suas preferências para formar pares estáveis, onde nenhum homem e mulher prefeririam estar juntos a estar com outros parceiros com base em suas preferências individuais.
  
  Repositório do Algoritmo:
  
  ## Algoritmo Húngaro
  O algoritmo húngaro é uma técnica para resolver o problema de atribuição, que envolve encontrar o melhor emparelhamento entre dois conjuntos de elementos com base em seus custos ou pesos. Ele utiliza programação dinâmica para determinar o emparelhamento ótimo, com complexidade de tempo eficiente. O algoritmo também é conhecido como o algoritmo de Kuhn-Munkres.
  
  Repositório do Algoritmo:
  
  ## Algoritmo de Caminhos aumentados
  O algoritmo de caminhos aumentados é usado em problemas de fluxo máximo em redes. É uma das variantes do algoritmo Ford-Fulkerson. A abordagem consiste em encontrar caminhos aumentados, que são caminhos da fonte ao sumidouro ao longo dos quais o fluxo pode ser aumentado. Repetidamente encontrando caminhos aumentados e ajustando o fluxo, o algoritmo encontra o fluxo máximo na rede.

  Repositório do Algoritmo:
  
  ## Algoritmo de Ford-Fulkerson
  O algoritmo Ford-Fulkerson é um método clássico para resolver o problema de fluxo máximo em uma rede. Ele aumenta o fluxo de forma iterativa, encontrando caminhos aumentados que vão da fonte ao sumidouro, modificando o fluxo ao longo desses caminhos para aumentar o fluxo total. O algoritmo termina quando não há mais caminhos aumentados, resultando no fluxo máximo na rede.

  Repositório do Algoritmo:
  
  ## Algoritmo de Edmonds-Karp
  O algoritmo Edmonds-Karp é uma variação do algoritmo Ford-Fulkerson que utiliza a busca em largura (BFS) para encontrar caminhos aumentados de forma mais eficiente. Ele é usado para calcular o fluxo máximo em uma rede com capacidades nas arestas. A busca em largura ajuda a garantir que a capacidade do caminho aumentado encontrado seja totalmente utilizada, o que melhora a convergência do algoritmo em comparação com o Ford-Fulkerson tradicional.
  
  Repositório do Algoritmo:
  
  ## Algoritmo de Coloração Guloso
  Os algoritmos gulosos, também conhecidos como algoritmos de coloração, são uma classe de algoritmos de otimização que fazem escolhas localmente ótimas em cada etapa com a esperança de alcançar uma solução global ótima. No contexto da coloração de grafos, o algoritmo guloso é usado para atribuir cores a vértices de um grafo de forma que vértices adjacentes não tenham a mesma cor. Ele faz isso selecionando cada vértice e atribuindo a menor cor possível que não entra em conflito com as cores de seus vizinhos já coloridos. O algoritmo continua até que todos os vértices sejam coloridos. Embora seja fácil de implementar, o resultado pode não ser sempre o ótimo, mas é uma heurística rápida e eficiente para muitos problemas de coloração.
  
  Repositório do Algoritmo:
  
  
