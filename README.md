# How Can a Wellness Technology Company Play It Smart?

[Você pode ver a análise completa no Jupyeter Notebook](https://github.com/biancaportela/bellabeat_analise/blob/main/bellabeat_analysis.ipynb)

## Introdução

Projeto de análise de dados final para o Certificado Profissional Google Data Analytics.Esse estudo de caso é uma simulação das tarefas do dia a dia de um analista de dados júnior que trabalha na Bellabeat, uma empresa focada em produzir produtos para saúde feminina. O estudo de caso busca percorrer todo o processo que envolve a análise de dados: as fases da pergunta, o preparo, o processo, a análise, o compartilhamento e o chamado à ação. 

Como resultado entrega-se um relatório com o sumário do problema de negócios, uma descrição de todas as fontes de dados utilizadas na análise, a documentação da análise de dados, um resumo da análise e a recomendação final para a resolução do *case*. 

## Cenário

O cenário apresenta a Bellabeat que, como previamente mencionado, é uma empresa focada em produtos de saúde feminina. É uma empresa pequena, que busca crescimento no mercado principalmente através da venda de wearables fitness. A empresa vende seus produtos globalmente através do e-commerce. 

Nesse sentido, a proposta do case é analisar o dispositivo smart e os dados obtidos dos clientes com o objetivo de derivar insights de como estes clientes estão usando o dispositivo. Com a análise dos hábitos do consumidor seria possível guiar o time de marketing em uma nova estratégia para a companhia. 

**O problema de negócios que busca-se resolver se divide em três perguntas:**

- Quais são as tendências de consumo nos dispositivos inteligentes?
- Como essas tendências estão relacionadas com a base de clientes da Bellabeat?
- Como essas tendências podem ajudar a influenciar a estratégia de marketing da empresa?

## Sumário executivo

- Os participantes do questionário, em média, não cumprem as métricas recomendadas de atividade física diárias: eles não têm 10000 passos diários e não dormem o recomendado por noite.

<p float="center">
  <img src="https://github.com/biancaportela/bellabeat_analise/blob/e261499fa0bba5ab097ab7dd91200236e52296c4/imagens/media_passos.jpg" width="300" height = "150"/>
  <img src="https://github.com/biancaportela/bellabeat_analise/blob/e261499fa0bba5ab097ab7dd91200236e52296c4/imagens/sono.jpg" width="300" height = "150" /> 
</p>

- Os participantes também tem menos de 30min de momento muito ativos:
<p align="center">
<img src="https://github.com/biancaportela/bellabeat_analise/blob/e261499fa0bba5ab097ab7dd91200236e52296c4/imagens/minutos_ativos.jpg"  width="700" height="400">
</p>
<br>


**Solução**: Como uma das missões da empresa é garantir o bem estar, poderia-se mostrar pequenos textos reafirmando o quanto é importante ter  uma meta *x* de passos e uma boa noite de sono. Esses textos poderiam ser mostrados com maior ênfase para aqueles que não cumprem as metas básicas de saúde.
    
    
- A maioria das pessoas tem poucos minutos de atividade total, sendo o primeiro quartil da amostra sedentário.


|       | TotalSteps   | TotalDistance | VeryActiveMinutes | FairlyActiveMinutes | LightlyActiveMinutes | SedentaryMinutes | Calories    |
|-------|--------------|---------------|-------------------|---------------------|----------------------|------------------|-------------|
| count | 940.000000   | 940.000000    | 940.000000        | 940.000000          | 940.000000           | 940.000000       | 940.000000  |
| mean  | 7637.910638  | 5.489702      | 21.164894         | 13.564894           | 192.812766           | 991.210638       | 2303.609574 |
| std   | 5087.150742  | 3.924606      | 32.844803         | 19.987404           | 109.174700           | 301.267437       | 718.166862  |
| min   | 0.000000     | 0.000000      | 0.000000          | 0.000000            | 0.000000             | 0.000000         | 0.000000    |
| 25%   | 3789.750000  | 2.620000      | 0.000000          | 0.000000            | 127.000000           | 729.750000       | 1828.500000 |
| 50%   | 7405.500000  | 5.245000      | 4.000000          | 6.000000            | 199.000000           | 1057.500000      | 2134.000000 |
| 75%   | 10727.000000 | 7.712500      | 32.000000         | 19.000000           | 264.000000           | 1229.500000      | 2793.250000 |
| max   | 36019.000000 | 28.030001     | 210.000000        | 143.000000          | 518.000000           | 1440.000000      | 4900.000000 |


  - **Solução**: a análise das pessoas que se caracterizam como sedentárias poderia abrir espaço para a criação de uma  funcionalidade premium, em que essas pessoas poderiam optar por pagar uma espécie de assinatura para ter informações ainda mais detalhadas e personalizadas sobre como ter uma vida mais ativa.
    
    
- O dispositivo da Bellabeat rastreia qualidade de sono, peso e atividades diárias. Nenhuma dessas funcionalidades é nova no mercado de dispositivos inteligentes. Assim, a melhor estratégia para garantir novos clientes é apostar na diferenciação de seu produto.
	
  - **Solução**: Focar mais no mercado femino, seu público alvo, oferecendo funcionalidade de rastreio do ciclo menstrual e variações de humor.
    
    
- Há poucos dados únicos, apenas 33 participantes durante um período de um mês. Não há informações sobre dados cruciais como gênero, localização e idade dos clientes. A falta de dados interfere na inferência e na detecção de padrões de consumo.

  - **Solução**: Aumentar o número de observações e o período de análise na coleta de dados.



