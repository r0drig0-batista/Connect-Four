# 1º Trabalho IA - ConnectFour

## Descrição do Projeto
Este projeto implementa e analisa algoritmos de busca aplicados ao jogo **ConnectFour**. O objetivo é criar agentes inteligentes capazes de tomar decisões estratégicas com base em heurísticas e simulações, permitindo uma melhor escolha de jogadas.

## Estrutura do Notebook
### 1. Introdução
Apresentação geral do problema e da abordagem adotada para desenvolver os agentes inteligentes.

### 2. Objetivo
Descrever a aplicação de algoritmos de busca no ConnectFour, visando criar um agente capaz de tomar decisões otimizadas.

### 3. Implementação
#### Class ConnectFour
- Representa o tabuleiro e a mecânica do jogo.
- Implementação das regras e função de verificação de vitória.

#### Class Node
- Estrutura de dados utilizada nos algoritmos de busca.
- Representa estados do jogo, armazenando informações sobre jogadas e avaliação heurística.

#### Menu no Terminal
- Interface simples para interagir com o jogo via terminal.
- Permite escolher o tipo de agente e observar suas decisões.

### 4. Algoritmos Implementados
Foram testados diferentes algoritmos para tomada de decisão no jogo:
- **Minimax:** Avalia todas as possíveis jogadas e escolhe a melhor, assumindo que o adversário também joga de forma ótima.
- **Alpha-Beta Pruning:** Otimiza o Minimax, cortando ramos da árvore de decisão que não impactam no resultado final.
- **Monte Carlo Tree Search (MCTS):** Executa simulações aleatórias do jogo para avaliar jogadas prováveis.

### 5. Resultados Obtidos e Discussão
- Comparou-se o desempenho dos algoritmos, analisando o tempo de execução e a qualidade das jogadas.
- O Alpha-Beta Pruning demonstrou uma redução significativa no tempo de cálculo comparado ao Minimax puro.
- O MCTS mostrou-se eficiente em cenários onde há muitas opções viáveis e uma profundidade alta de busca.

### 6. Conclusão
O estudo mostrou que o uso de algoritmos de busca pode proporcionar um desempenho avançado em jogos como ConnectFour. A escolha do algoritmo ideal depende do contexto, da profundidade de busca desejada e da disponibilidade de recursos computacionais.

---
Autores: 
- Francisco Tavares
- Rodrigo Batista
- Rodrigo Taveira

