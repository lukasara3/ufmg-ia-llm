# 🗺️ Análise de Grafos Geoespaciais e Preparação de Rotas

**Projeto de Inteligência Artificial | UFMG**

Este projeto explora a interseção entre Inteligência Artificial e Sistemas de Informação Geográfica (GIS). Ele utiliza dados do **OpenStreetMap (OSM)** para construir, manipular e analisar redes urbanas sob a ótica de grafos matemáticos. 

O objetivo principal é processar dados geoespaciais do mundo real e prepará-los para algoritmos avançados de busca de caminhos (pathfinding) e análise espacial, que são componentes essenciais em logística, planejamento urbano e softwares de roteamento.

---

### 🛠️ Tecnologias e Bibliotecas

<div align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn" />
</div>

*   **OSMnx:** Biblioteca principal para download de geometrias espaciais e modelagem em formato de grafos de rede.
*   **Geopandas & Shapely:** Utilizadas para operações espaciais e manipulação de dados geométricos.
*   **Overpass API:** Integração para consultas específicas de dados de mapas e pontos de interesse (POIs).
*   **Matplotlib:** Utilizada para a visualização de grafos e nós.

---

### ⚙️ Funcionalidades e Implementação

*   **Aplicação da Teoria dos Grafos:** Transformação de dados brutos de ruas em uma estrutura de grafo (nós representando cruzamentos, arestas representando segmentos de rua).
*   **Filtragem Geoespacial:** Extração de pontos de dados específicos usando tags do OSM (ex: isolamento de nós `highway=bus_stop`).
*   **Mapeamento de Vizinhos Mais Próximos (Nearest Neighbor):** Utilização de algoritmos espaciais para encontrar e projetar os pontos geométricos mais próximos dentro de uma rede de grafos não projetada.
*   **Integração com APIs:** Gerenciamento de requisições para serviços externos (Overpass API), lidando com *timeouts* e restrições de extração de dados.
*   **Visualização de Dados:** Criação de representações visuais das redes de grafos e dos pontos de interesse enriquecidos para validação analítica.

---

### 💡 Aprendizados Técnicos

O desenvolvimento deste projeto consolidou meu entendimento sobre o funcionamento interno de aplicações de mapeamento. Estruturar e manipular dados geoespaciais brutos em grafos matemáticos é uma etapa fundamental para a construção de qualquer serviço baseado em localização, mecanismos de otimização logística ou modelos de IA espacial.
