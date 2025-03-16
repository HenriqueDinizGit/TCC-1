# The Art and Practice of Data Science Pipelines: A Comprehensive Study of Data Science Pipelines In Theory, In-The-Small, and In-The-Large

Biswas, Sumon; Wardat, Mohammad; Rajan, Hridesh. "The Art and Practice of Data Science Pipelines: A Comprehensive Study of Data Science Pipelines In Theory, In-The-Small, and In-The-Large." In 44th International Conference on Software Engineering (ICSE ’22), May 21–29, 2022, Pittsburgh, PA, USA, pp. 2091-2103, 2022. doi: 10.1145/3510003.3510057

## 1. Fichamento de Conteúdo

O artigo apresenta um estudo abrangente sobre os pipelines de data science, dividindo-os em três categorias: pipelines teóricos, pipelines "in-the-small" (como os extraídos de notebooks de competições no Kaggle) e pipelines "in-the-large" (de projetos maduros no GitHub). Os autores descrevem as etapas comuns de um DS pipeline – desde a aquisição e preparação dos dados até a modelagem, treinamento, avaliação e predição – e discutem como essas etapas se organizam e se conectam de maneira diferente em cada cenário. Utilizando métodos de coleta e rotulagem (open-coding) com alta concordância entre os avaliadores, o estudo extrai e unifica os conceitos de DS pipeline a partir de 71 propostas teóricas, 105 implementações do Kaggle e 21 projetos do GitHub. Os resultados indicam que, enquanto os pipelines teóricos apresentam um conjunto mais completo e modular de estágios, os pipelines práticos tendem a ser mais lineares e até “jungles” devido à mistura de tarefas de pré-processamento e modelagem. Dessa forma, o artigo oferece uma representação padronizada que pode auxiliar tanto pesquisadores quanto desenvolvedores na concepção e manutenção de pipelines de data science.

## 2. Fichamento Bibliográfico

* **Definição de DS Pipeline:** O pipeline de data science é definido como uma sequência de estágios – como aquisição, preparação, modelagem, treinamento, avaliação, e predição – que interagem de forma interdependente para transformar dados brutos em insights úteis (aprox. p. 2091-2093).  
* **Representações dos Pipelines:** O estudo propõe três representações dos pipelines para os cenários teórico, in-the-small e in-the-large, destacando as diferenças na modularização e na presença de feedback loops (aprox. p. 2092-2100).  
* **Método de Rotulagem:** Foi utilizada uma abordagem de open-coding, com treinamento e reavaliação entre os raters, resultando em alta concordância (Cohen’s Kappa ≈ 0.83) para a identificação e classificação dos estágios dos pipelines (aprox. p. 2092-2094).  
* **Diferenças de Organização:** Enquanto pipelines teóricos abrangem todas as etapas com clareza, pipelines in-the-small frequentemente omitem estágios como armazenamento e avaliação, e os pipelines in-the-large demonstram estruturas complexas com múltiplos módulos e fases de desenvolvimento versus pós-desenvolvimento (aprox. p. 2094-2100).

## 3. Fichamento de Citações

* "We contributed three representations of DS pipelines that capture the essence of our subjects in theory, in-the-small, and in-the-large."  
* "Among 46 DS pipelines (which are not team processes), Modeling is present in 93% of the pipelines, while evaluation and prediction are often not depicted as separate stages."  
* "The DS pipelines in-the-large have a more complex structure and feedback loops compared to the theoretical representations."

