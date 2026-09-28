# puc-ead-data-science_ENG
Repositório para o projeto de Engenharia de Dados - MVP: Construção de um Pipeline de Dados na Nuvem

Este projeto teve como objetivo construir um pipeline completo de engenharia e análise de dados sobre rotatividade de funcionários, utilizando o Databricks como ambiente de processamento em nuvem. A partir de um dataset com licença free, foram desenvolvidas as camadas Bronze, Silver e Gold, garantindo organização, padronização e qualidade dos dados ao longo de todo o fluxo. Na camada Silver, foram aplicadas transformações essenciais, como padronização de tipos, limpeza de categorias e seleção de atributos relevantes. Em seguida, a camada Gold consolidou as informações em um modelo estrela composto por uma tabela fato e duas dimensões, permitindo análises rápidas e estruturadas.

Com o modelo analítico pronto, foram realizadas consultas no Databricks SQL para responder às principais perguntas do projeto, incluindo taxa geral de rotatividade, identificação de áreas e cargos com maior índice de desligamentos e análise de fatores como horas extras, satisfação no trabalho, equilíbrio vida‑profissional, idade, renda e tempo de empresa. Algumas perguntas iniciais não puderam ser respondidas devido à ausência de atributos específicos na camada Gold, como distância da residência, escolaridade, gênero e viagens corporativas, que poderão ser incorporados em versões futuras do projeto.

O trabalho também envolveu uma etapa de qualidade de dados, garantindo integridade referencial, ausência de duplicidades nas dimensões e consistência dos atributos utilizados nas métricas. No geral, o projeto consolidou um pipeline funcional, escalável e pronto para evoluir para dashboards, análises avançadas e até modelos preditivos.

O detalhamento está na documentação do projeto.
