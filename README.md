Python e PBI - Análise Gráfica e Fundamentalista de Ativos

<img width="5938" height="1080" alt="image" src="https://github.com/user-attachments/assets/563c5011-3a5f-415f-8c73-bf576287234e" />


A consultoria financeira Bulltrend busca visualizar as carteiras de investimento de seus(suas) clientes pensando na melhor forma de indicar bons ativos e acompanhar a evolução destes.

Como analista de dados dessa consultoria, decidi combinar duas potentes ferramentas de Data Science, Python e Power BI, para auxiliar o time de consultores a acompanhar de perto a carteira de ativos dos(das) clientes.

Importantes correntes para análise de ativos: a análise fundamentalista e a análise gráfica.

Por meio da coleta dos dados com as bibliotecas Python e carga no Power BI, será possível avaliar a carteira da pessoa cliente e acompanhar os indicadores fundamentalistas que avaliam a situação financeira da empresas listadas na bolsa e as flutuações das cotações no período estipulado

Problema de negócio:

O objetivo da Bulltrend é identificar quais são os melhores indicadores para gerar o dashboard e compilar em um só painel esses dados juntos às cotações de cada ativo.

Base de dados

Deve importar duas bases de dados em que:

A base de dados com as cotações será gerada dentro do periodo de 01/08/2022 à 01/08/2023, por meio da biblioteca yfinance que lê os dados das cotações de todos os ativos listadas na bolsa do Brasil e do Mundo por meio do site da Yahoo Finance
A base de dados com os indicadores será gerado, por meio da biblioteca fundamentus que lê os dados dos indicadores fundamentalistas de todos os ativos listadas na bolsa do Brasil por meio do site da FUNDAMENTUS.

O desafio será eu como analista de dados do time de dados da Bulltrend tenho o desafio de extrair os dados fundamentalistas e de cotações dos ativos de uma carteira hipotética por meio das bbliotecas Python e carregá-los dentro do Power BI a fim de construir um dashboard com os dados compilados e disponíveis para a análise da pessoa consultora.
