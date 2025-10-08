#  Tech Challenge -- Fase 2 \| Otimização de Rotas Médicas com IA

##  Pós-Graduação: Inteligência Artificial para Desenvolvedores -- FIAP


------------------------------------------------------------------------

##  Objetivo do Projeto

Este projeto faz parte do **Tech Challenge -- Fase 2** e tem como
objetivo desenvolver um **sistema de otimização de rotas para
distribuição de medicamentos e insumos médicos**, utilizando
**Algoritmos Genéticos (AG)** e integração com **Modelos de Linguagem
Natural (LLMs)**.

A solução busca apoiar hospitais e centros de saúde na **entrega
eficiente de medicamentos, vacinas e equipamentos médicos**, reduzindo
custos e tempo de deslocamento.

------------------------------------------------------------------------

##  Descrição Geral

O projeto implementa um **Algoritmo Genético** capaz de resolver o
problema clássico de **roteamento de veículos (VRP)**, uma evolução do
**Problema do Caixeiro Viajante (TSP)**, considerando restrições
realistas como:

-   Prioridade de entregas (urgente x regular)\
-   Capacidade máxima de carga\
-   Autonomia limitada dos veículos\
-   Múltiplos veículos disponíveis\
-   Penalidades por rotas ineficientes

Além disso, o projeto inclui um módulo de **integração com IA generativa
(LLM)** para gerar **relatórios automáticos e instruções de rota** em
linguagem natural, permitindo que motoristas e equipes médicas
compreendam facilmente os trajetos otimizados.

------------------------------------------------------------------------

##  Principais Funcionalidades

-   Implementação de **Algoritmo Genético customizado** para otimização
    de rotas\
-   **Função fitness** baseada em distância, prioridade e autonomia\
-   **Visualização interativa** das rotas no mapa (usando *Folium*)\
-   **Comparação de desempenho** entre diferentes configurações do AG\
-   **Exportação** de resultados em CSV e PNG\
-   **Placeholder** para integração com modelos LLM (GPT, LLaMA, Falcon
    etc.)

------------------------------------------------------------------------

##  Etapas do Projeto

1.  **Definição do problema e dados simulados**\
2.  **Implementação do Algoritmo Genético (AG)**\
3.  **Simulação do VRP (Vehicle Routing Problem)**\
4.  **Visualização e análise dos resultados**\
5.  **Integração com LLM (IA de linguagem)**

------------------------------------------------------------------------

##  Tecnologias Utilizadas

  -----------------------------------------------------------------------
  Categoria                           Ferramenta
  ----------------------------------- -----------------------------------
  Linguagem principal                 Python 3.x

  Ambiente                            Google Colab / Jupyter Notebook

  Bibliotecas principais              pandas, numpy, folium, matplotlib,
                                      scikit-learn

  IA Generativa                       OpenAI GPT / Placeholder LLM

  Controle de versão                  Git / GitHub

  Visualização                        Folium (mapas interativos)

  Exportação                          CSV e PNG
  -----------------------------------------------------------------------

------------------------------------------------------------------------

##  Como Executar o Projeto

1.  **Clone o repositório**

    ``` bash
    git clone https://github.com/TechChallenge-FIAP-Grupo6/tech-challenge-fase2.git
    cd tech-challenge-fase2
    ```

2.  **Instale as dependências**

    ``` bash
    pip install -r requirements.txt
    ```

3.  **Execute o notebook**

    -   Abra o arquivo `tech_challenge_fase2.ipynb` no **Google Colab**
        ou **Jupyter Notebook**.\
    -   Execute as células em ordem.

4.  **Geração de relatórios com LLM**

    -   Insira sua **chave da API** (por exemplo, `OPENAI_API_KEY`) no
        campo indicado.\
    -   Execute a célula para gerar relatórios automáticos das rotas.

------------------------------------------------------------------------

##  Resultados Obtidos

-   Redução significativa no custo total de rotas em relação ao
    baseline.\
-   Visualização das melhores rotas otimizadas no mapa.\
-   Geração de relatórios textuais automáticos com resumo de eficiência.

*(adicione prints e imagens aqui)*

------------------------------------------------------------------------

##  Entregáveis

-   **Notebook completo (.ipynb)** com código e resultados\
-   **PDF** com relatório técnico e prints dos mapas\
-   **Link do repositório GitHub**\
-   **Vídeo de demonstração (até 15 minutos)** apresentando:
    -   Execução do notebook\
    -   Resultados das rotas\
    -   Explicação da lógica do AG\
    -   Integração com LLM

------------------------------------------------------------------------

##  Integrantes do Grupo
-   Nathan
-   Denys
-   Fernanda

  ##  Referências

-   FIAP -- Pós IA para Desenvolvedores
-   Kaggle -- exemplos de datasets de logística e saúde
-   Goldberg, D.E. -- *Genetic Algorithms in Search, Optimization &
    Machine Learning*\
-   OpenAI Documentation




