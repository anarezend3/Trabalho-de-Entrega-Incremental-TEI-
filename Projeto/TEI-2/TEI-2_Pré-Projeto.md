# Modelo de Pesquisa: Impacto da Adoção de DevOps na Qualidade do Software

## Equipe

* Ana Luiza Rezende
* Gustavo Costa Gabrich
* Luidi Cadete Silva

* Lesandro Ponciano (orientador de acadêmico)

## Introdução

1. A área da Engenharia de Software tratada neste trabalho é _DevOps e sua influência na qualidade do software._

2. O problema que este trabalho busca resolver nessa área é conforme às questões de pesquisa a seguir: _A adoção de DevOps resulta em uma melhoria significativa na qualidade do software, medida por métricas como redução de bugs, aumento da satisfação do usuário e conformidade com os requisitos? Em que medida a integração entre as equipes de desenvolvimento e operações, promovida pelo DevOps, reduz os gargalos de comunicação e os atrasos na entrega de software? A automação de processos no DevOps contribui para uma entrega contínua mais eficiente e confiável de software de alta qualidade?_

3. Resolver este problema é relevante porque _a avaliação do impacto da adoção de DevOps permite entender se essa abordagem realmente contribui para a melhoria da qualidade do software. Isso pode auxiliar organizações a decidirem sobre a implementação de práticas DevOps, considerando sua potencial contribuição para a redução de bugs, aumento da satisfação do usuário e melhoria na conformidade com os requisitos._

4. O objetivo geral deste trabalho é _avaliar formas de adoção de DevOps por equipes de desenvolvimento de software e seu impacto na qualidade do software._

5. Os *três* objetivos específicos deste trabalho são: _(1) Investigar se a adoção de práticas DevOps influencia significativamente a qualidade do software, avaliando métricas como a redução de bugs, avaliar a percepção dos usuários em relação à qualidade do software após a adoção de práticas DevOps, verificar a conformidade do software com os requisitos estabelecidos antes e após a implementação do DevOps; (2) Examinar como a integração entre as equipes de desenvolvimento e operações, promovida pelo DevOps, afeta os gargalos de comunicação, quais são os principais gargalos de comunicação entre equipes de desenvolvimento e operações antes da implementação do DevOps e os atrasos na entrega de software e avaliar a percepção das equipes de desenvolvimento e operações sobre a comunicação e colaboração após a implementação do DevOps; (3) Identificar os processos que foram automatizados como parte da implementação do DevOps, analisar o impacto da automação de processos no DevOps na eficiência e confiabilidade da entrega contínua de software de alta qualidade, após a implementação de práticas de automação._


## Fundamentação Teórica

1. O conceito/teoria principal associado a este trabalho é DevOps. A sua definição neste trabalho é "uma combinação de práticas e ferramentas de engenharia de software que visa aumentar a capacidade de uma organização de entregar aplicações e serviços em alta velocidade, melhorando e evoluindo produtos em um ritmo mais rápido do que as organizações que utilizam processos tradicionais de desenvolvimento de software e gestão de infraestrutura, conforme definido na obra literária científica "The DevOps Handbook: How to Create World-Class Agility, Reliability, & Security in Technology Organizations" pelos autores Gene Kim, Jez Humble e Forrest North (2016).

2. O conceito/teoria secundário associado a este trabalho é a qualidade do software. A sua definição neste trabalho é "a medida em que um software atende aos requisitos funcionais e não funcionais, incluindo a redução de bugs, a satisfação do usuário e a conformidade com os requisitos" conforme definido em outra obra científica literária "Software Quality: Concepts and Practice" pelo autor Daniel Galin (2018).


## Trabalhos Relacionados

1. O trabalho mais relacionado é "DevOps-RAF: An assessment framework to measure DevOps readiness in software organizations" (https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9650363), publicado no ano 2021, pelos autores Lilianny Marrero;Hernán Astudillo porque ele estuda uma estrutura de avaliação para medir a prontidão do DevOps em organizações de software.

2. O segundo trabalho mais relacionado é "Expanding DevOps Principles and Best Practices Based on Practical View" (https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9994216), publicado no ano 2022, pelos autores Muntaha Alawneh;Imad M. Abbadi, porque ele trata de padrões da expansão dos princípios e melhorias das práticas do DevOps com base na visão prática.

3. O terceiro trabalho mais relacionado é "A Study of Adoption and Effects of DevOps Practices" (https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10033313), publicado no ano 2022 pelos autores Tyron Offerman; Robert Blinde; Christoph Johann Stettina; Joost Visser, porque ele fala sobre um estudo sobre a adoção e efeitos das práticas DevOps.

## Materiais e Métodos

1. O tipo de pesquisa adotado neste trabalho é "quantitativa", porque _envolve a coleta e análise de dados numéricos relacionados à qualidade do software e à eficiência das práticas DevOps_, e também é  e "descritiva", pois ela _busca descrever como a adoção de práticas DevOps influencia na qualidade do software e na eficiência das equipes de desenvolvimento e operações, podendo ser tanto de maneira positiva quanto negativa._

2. Os materiais utilizados neste trabalho são _os dados de commits, bugs e releases serão coletados utilizando a API do GitHub (https://docs.github.com/en/rest?apiVersion=2022-11-28), que fornece informações detalhadas sobre o histórico de desenvolvimento e manutenção dos projetos. Além disso, informações sobre a satisfação do usuário serão obtidas através de análises de reviews e ratings disponíveis nas plataformas de distribuição de software, como App Store, Google Play e outras plataformas relevantes._

3. Os métodos empregados nesta análise incluirão várias etapas. _Primeiramente, os dados serão coletados utilizando a API do GitHub para obter informações sobre commits, bugs e releases dos projetos selecionados, além de avaliações e feedbacks de usuários das plataformas de distribuição de software. Em seguida, as métricas serão calculadas. Para a redução de bugs, será contado o número de bugs reportados e corrigidos em períodos de tempo definidos. A satisfação do usuário será analisada e quantificada com base nas avaliações e feedbacks dos usuários. A conformidade com os requisitos será avaliada a partir da documentação e relatórios de conformidade dos projetos. A comunicação entre equipes será analisada por meio de logs de comunicação e reuniões, e os atrasos na entrega serão calculados como o tempo médio entre commits e releases. A eficiência da entrega contínua será medida pela frequência e sucesso das entregas contínuas, e a confiabilidade será avaliada contando o número de falhas ou incidentes pós-deployment. As análises estatísticas incluirão o uso de gráficos para medir a relação entre a adoção de DevOps e as métricas de qualidade do software, além de testes de comparação em relação às médias das métricas de qualidade entre os projetos que adotaram DevOps e os que não adotaram. Análises de regressão serão empregadas para entender o impacto específico de cada prática DevOps (integração de equipes e automação de processos) nas métricas de qualidade do software._

4. As métricas utilizadas para avaliar a qualidade do software e a eficiência das práticas DevOps _são divididas em três categorias principais: qualidade do software, integração entre equipes e automação de processos. Para a qualidade do software, as métricas incluem a redução de bugs (número de bugs reportados e corrigidos ao longo do tempo), a satisfação do usuário (avaliações e feedbacks dos usuários) e a conformidade com os requisitos (avaliação do atendimento aos requisitos funcionais e não funcionais do software). Para a integração entre equipes, as métricas incluem a comunicação (número e frequência de interações entre as equipes de desenvolvimento e operações, medidas por análise de logs de comunicação e reuniões) e os atrasos na entrega (tempo médio entre commits e releases). Para a automação de processos, as métricas incluem a eficiência da entrega contínua (frequência e sucesso das entregas contínuas, incluindo tempo de deployment e rollback) e a confiabilidade (número de falhas ou incidentes pós-deployment)._

5. A forma de amostragem _envolverá a seleção de projetos que adotaram práticas DevOps e projetos que não adotaram, para fins de comparação. A seleção incluirá projetos de diferentes domínios e tamanhos para garantir a representatividade. A análise comparativa entre esses dois grupos permitirá avaliar o impacto específico das práticas DevOps nas métricas de qualidade do software._

6. As etapas de execução do trabalho incluem: _1) coletar os dados dos projetos no GitHub e avaliações dos usuários nas plataformas de distribuição de software; 2) calcular as métricas de qualidade do software, integração entre equipes e automação de processos; 3) analisar a relação entre a adoção de DevOps e as métricas de qualidade do software utilizando gráficos, testes de comparação de amostras independentes e análises de regressão; e 4) interpretar os resultados para responder às questões de pesquisa e atingir os objetivos gerais e específicos do estudo._
