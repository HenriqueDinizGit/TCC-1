# Unmasking Data Secrets: An Empirical Investigation into Data Smells and Their Impact on Data Quality

Recupito, Gilberto; Rapacciuolo, Raimondo; Di Nucci, Dario; Palomba, Fabio. "Unmasking Data Secrets: An Empirical Investigation into Data Smells and Their Impact on Data Quality." In CAIN 2024 – Software Engineering for AI, April 14–15, 2024, Lisbon, Portugal. https://doi.org/10.1145/3644815.3644960

## 1. Fichamento de Conteúdo

O artigo investiga o conceito de “data smells”, definidos como indicações baseadas no valor dos dados que sinalizam problemas latentes de qualidade, de forma análoga aos code smells em software. Os autores propõem uma atualização e expansão do catálogo existente, incorporando 12 novos data smells distribuídos em três categorias adicionais, o que enriquece a compreensão sobre as falhas na qualidade dos dados. Para validar essa nova taxonomia, o estudo emprega uma abordagem empírica baseada na análise de 19 conjuntos de dados reais. Métodos estatísticos – como o coeficiente de Spearman e modelos lineares generalizados – são aplicados para investigar a correlação entre a ocorrência dos data smells e métricas de qualidade (completude, unicidade, consistência e legibilidade). Os resultados demonstram que, embora a ocorrência isolada de um data smell possa parecer discreta, o seu acúmulo pode degradar significativamente a qualidade dos dados. Assim, os autores ressaltam a importância de desenvolver estratégias automatizadas para a detecção e mitigação desses problemas, contribuindo para a melhoria da confiabilidade em sistemas AI.

## 2. Fichamento Bibliográfico

* **Data Smells:** Termo em inglês que se refere a “indicações baseadas no valor dos dados” que sinalizam problemas latentes de qualidade, análogo aos code smells em software.
* **Spearman’s Coefficient:** Método estatístico utilizado para medir a correlação entre a ocorrência dos data smells e as métricas de data quality.
* **Generalized Linear Models (GLM):** Modelos estatísticos empregados para quantificar o impacto cumulativo dos data smells nas métricas de qualidade dos dados.
* **Catalog Update:** Atualização do catálogo de data smells, que inclui novas categorias e definições, aprimorando a compreensão dos problemas de qualidade dos dados.

## 3. Fichamento de Citações

* "Data smells are data value-based indications of latent data quality issues caused by poor practices that may lead to problems in the future."  
* "An updated catalog of data smells, which advances the state of the art by providing the definition of novel data smells, along with the information on how to detect them."  
* "While the effect of a single instance of a data smell may appear negligible, the cumulative impact in high quantities can significantly degrade data quality."
