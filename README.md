# 🛣️Cálculo de Rotas
este projeto propõe o 
desenvolvimento de uma aplicação em linguagem C, capaz de calcular a melhor rota 
até o destino escolhido pelos estudantes, com base em algoritmos de grafos, 
especificamente o de Dijkstra.
Para isso, será utilizado o algoritmo de Dijkstra não direcionado em conjunto 
com uma matriz de adjacência, representando o grafo das 
rotas possíveis. Essa abordagem permite uma modelagem eficiente do problema, 
facilitando o cálculo das distâncias e conexões entre os pontos. Além de propor uma 
solução prática.

# 🔧 Funcionalidades
O projeto foi desenvolvido com o objetivo de otimizar as rotas de transporte dos alunos da Unisantos, priorizando eficiência e funcionalidade.
A implementação foi realizada em linguagem C, escolhida por sua robustez e desempenho superior em operações de baixo nível, como manipulação de estruturas de dados.
Para melhor precisão e rapidez, foram selecionados dez lugares específicos da cidade de Santos:

Rodoviária

Museu do Café

Praça da Independência

Praia do Gonzaga

Orquidário

Aquário Municipal

Estádio Vila Belmiro

Shopping Parque Balneário

Morro do José Menino

UNISANTOS

# 💻Estruturas Utilizadas
• Variáveis globais: V (número total de locais), locais[ ] (nomes dos pontos 
disponíveis), distancias[ ][ ] (matriz de adjacência representando as conexões 
entre os locais). 

• Vetores: 
dist[V]: Armazena a menor distância encontrada para cada vértice. 
visitado[V]: Booleano que indica se um vértice já foi analisado. 
anterior[V]: Armazena os predecessores para reconstrução do caminho mais curto. 

• Funções: 
imprimir_menu(): Exibe as opções de locais disponíveis para seleção. 
menorDistancia(): Encontra o vértice não visitado com a menor distância calculada. 
imprimirCaminho(): Exibe o caminho entre a origem e o destino. 
dijkstra(): Implementação principal do algoritmo para calcular a melhor rota.
