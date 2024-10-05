# Regressão Linear para predição de séries temporais

Esse projeto foi feito para a disciplina de mestrado da Unicamp IA048 - Aprendizado de Máquina.

A base de dados trabalhada foi a U.S Airline Traffic Data, a qual contém informações referentes ao tráfego aéreo mensal norte-americano no período de 2003-2023, em particular, foi explorada a série temporal do número total de voos.
A análise desse tipo de série temporal pode ser útil para o planejamento das companhias aéreas e setores administrativos de aeroportos, para a elaboração de estratégias de preços e outras decisões de negócios.

As perguntas respondidas com esse código foram:

a) Exiba o gráfico da série temporal completa. Numa inspeção visual simples,  ́e possível reconhecer ao menos
três faixas distintas de comportamento aproximadamente “regular” na série: (i) Jan/2003 a Ago/2008; (ii)
Set/2008 a Dez/2019; (ii) Jan/2020 a Set/2023. Discuta possíveis razões históricas / econômicas para essas
transições de comportamento.

b) Divida a série em dois conjuntos: (i) treinamento e validação, com amostras de 2003 a 2019; (ii) teste, com
amostras de 2020 a 2023. Faça a análise de desempenho do preditor linear  ́otimo, no sentido de quadrados
mínimos irrestrito, considerando:

b1) A progressão do valor da raiz quadrada do erro quadrático m ́edio (RMSE, do inglês root mean squared
error ), junto aos dados de validação, em função do número de entradas (K) do preditor (desde K = 1
a K = 24). Apresente o gráfico obtido e busque tecer conjecturas sobre os motivos subjacentes a seu
comportamento.


b2) O gráfico com as amostras de teste da série temporal e as respectivas estimativas geradas pela melhor
versão do preditor (i.e., usando o valor de K que levou ao mínimo erro de validação). Obtenha, também,
o RMSE e o erro percentual absoluto médio (MAPE, do inglês mean absolute percentage error ) para o
conjunto de teste.

b3) O gráfico com as amostras apenas dos dois  ́ultimos anos (2022 e 2023) e as estimativas geradas pelo
melhor preditor, além dos respectivos valores de RMSE e MAPE.

c) Repita o procedimento detalhado nos itens b1) e b2), mas adotando a seguinte divisão dos dados: (i)
treinamento – amostras de 2003 a 2019; (ii) validação – amostras de 2020 e 2021; (iii) teste, com amostras
de 2022 e 2023. Discuta os resultados obtidos e façaa uma comparação com o cenário anterior (especialmente
com o que foi obtido no item b3).
