## Estimativas de Tempo de Software
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Estimar as durações das atividades é o processo de estimativa do número de períodos
de trabalho que serão necessários para terminar as atividades específicas com os recursos estimados. A estimativa das durações das atividades utiliza informações sobre as atividades do escopo do projeto, tipos de recursos necessários, quantidades estimadas de recursos e calendários de recursos.

Esse processo requer que a quantidade do esforço de trabalho necessário e que a quantidade de recursos a ser aplicada para completar a atividade sejam estimados; esses são usados para aproximar o número de períodos de trabalho (duração da atividade) necessários para o término da atividade. Todos os dados e premissas que suportam a estimativa são documentados para cada estimativa de duração de atividade.

Os períodos de duração de atividades são estimados em horas ou dias para cada
atividade do pacote de trabalho.

## Cronograma de Atividades

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Desenvolver o cronograma é o processo de determinação das datas de início e fim planejadas para cada atividade, análise de sequências das atividades, suas durações, recursos necessários e restrições visando a criar o cronograma do projeto.

O desenvolvimento do cronograma pode requerer a análise e revisão das estimativas de duração e de estimativas de recursos para criar o modelo de cronograma aprovado do projeto que pode servir como linha de base para acompanhar o seu progresso.

O projeto está adotando uma metodologia ágil, e portanto usando sprints semanais para entrega do trabalho, com sprints de uma e duas semanas, dependendo do trabalho necessário naquela semana. Sendo que a data de entrega final do projeto já está descrito na ementa da matéria de Desenho e Arquitetura de Software.

## Controle do Cronograma

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O controle do cronograma está relacionado a:

> * Determinação da situação atual do cronograma do projeto.
> * Influência nos fatores que criam mudanças no cronograma.
> * Gerenciamento das mudanças reais conforme ocorrem.

## Estimativas de Custos de Software

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A estimativa de custos do projeto de desenvolvimento de software visa associar estimativas de esforço e tempo às atividades de um determinado projeto. Pode-se levantar os seguintes questionamentos acerca do projeto:


> * Quanto esforço é necessário para concluir cada atividade?
> * O tempo de calendário é necessário para concluir cada atividade?
> * Qual é o custo total de cada atividade?

## Estimativas de Produtividade de Software
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As estimativas de produtividade ajudam a definir o custo e o cronograma do projeto. As métricas de produtividade podem se basear nos atributos do software e na divisão pelo esforço total necessário para desenvolvimento. As métricas adotadas pelo projeto serão as **Métricas de software relacionadas à função** que estão relacionados à funcionalidade geral do software, onde serão atribuidos pontos de função. Devido a complexidade de algumas tarefas, durante o levantamento da pontuação será realizado um fator de ponderação(peso). Podemons considerr uma seguinte visualização:

> score = feature_score x peso_feature

* feature_score = São os recursos default a serem utilizados para criação de funcionalidades em geral.

* peso_feature = fator de ponderação que irá analisar as dependencias e necessidades específcas de codificação.

## Modelagem de Custo Algorítmica

A modelagem de custos algorítmica usa uma expressão matemática para prever os custos do projeto com base em estimativas do tamanho do projeto, no número de engenheiros de software e em outros fatores do processo e do produto. Em geral, um cálculo de custo algorítmico para custo de software pode ser expresso como:

```C++
EFFORT = A * pow(SIZE,B) * M
```

A: É um fator constante que depende das práticas organizacionais locais e do tipo de software desenvolvido. [0:50]<br>
SIZE: Pontuação do Projeto<br>
B:  Não Linearidade dos Custos(SIZE/Pontuação) [1:1.5] <br>
M: Experiência dos membros com as ferramentas e recursos [0-5]<br>


Tempo Estimado: 24 semanas(Considerando o período letivo somado ao período relacionado a quarentena)<br>

SIZE: 280 pontos em features e requisitos, resultando uma média de aproximadamente 12 pontos por Sprint<br>

A: 30 pontos, pois o projeto visa as boas práticas utilizando as técnicas mais acessíveis para desenvolvimento, pela complexidade do tema e proposta do projeto. A metodologia SCRUM estará presente durante o desenvolvimento <br>

B: equivale a 1,2. Considerando as adversidade de experiência e recursos<br>

M: equivale ao valor numérico 2 em uma escala de 5 devido a experiência e conhecimento teórico dos membros nas possíveis ferramentas e temas a serem abordados.

> EFFORT = 51,849.10


### Conclusão
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O valor estipulado do projeto ficou sendo R$ 51,849.10, é difícil estimar o custo do estágio inicial de desenvolvimento. As estimativas de função ou ponto de objeto podem ser produzidas mais facilmente do que as estimativas do tamanho (linhas)do código, mas geralmente são imprecisas. As estimativas dos fatores que contribuem para B e M são subjetivas.

## Estimativa por Projetos Anteriores
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O custo de um novo projeto é estimado por um projeto concluído no mesmo domínio do aplicativo. Tendo em mente que o aplicativo é voltado para gestão financeira, possuímos grandes referências neste âmbito tais como o aplicativo Mobills e o Guia Bolso.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O aplicativo Mobills é o aplicativo de finanças pessoais mais bem avaliado do Brasil, e para atingir esse patamar foram acelerados pelo programa ***Google Launchpad Accelerator***, em San Francisco, recebendo um investimento de US$ 50 mil.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Os demais aplicativos não fornecem informações de valores iniciais para seus respectivos projetos.

## Aplicação da Lei de Parkinson



> ***O trabalho se expande para preencher o tempo disponível para sua realização.***

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A lei de Parkinson afirma que o trabalho se expande para preencher o tempo disponível e o custo é determinado pelos recursos utilizados. O custos do projeto seriam o salários dos desenvolvedores, hardware e ferramentas a serem utilizadas, o destaque em si se dá em relação ao tempo.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O trecho: "[...]Se você der a uma pessoa qualquer uma atribuição X, com um prazo de 30 dias, ela tenderá a completá-la de uma forma que ocupe todo o prazo, mas se o prazo for de apenas 3 dias, é provável que ele a complete também, e se tiver que fazer em um dia só, também fará." compreende uma melhor noção de como os prazos a serem estipulados. <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tendo em mente os conceitos e exemplos da Lei, serão adotadas manobras que nos permitam não cair na Lei de Parkinson:<br/>
* Prazo estritamente necessário;
* Determinar Prioridades;
* Pareamentos;
* Controle Rígido de Débitos das Entregas;

## Conclusão
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Portanto o tempo estipulado será definido como 24 semanas, considerando o tempo do semestre letivo e o tempo da quarentena especulada até Junho. O valor do projeto a partir da Modelagem Algorítma é de aproximadamente de R$ 52,000.00 também considerando a estimativa do aplicativo Mobills.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;No decorrer do desenvolvimento e das técnicas a serem utilizadas no projeto, sempre que necessário será realizado um aprimoramento do Custo e do Tempo do projeto, tendo em mente que este documento é apenas uma visão superficial das técnicas de estimativas.


## Referências
>  Agile software development, Wikipedia: http://en.wikipedia.org/wiki/Agile_software_development



> A LEI de Parkinson. [S. l.], 2017. Disponível em: https://efetividade.net/2008/09/a-lei-de-parkinson.html. Acesso em: 10 abr. 2020.

> Ian Sommerville. Software Engineering, Eight Edition. Addison-Wesley, 2007.



### Histórico de revisões
|Data|Versão|Alteração|Autor|
|----|------|---------|-----|
|10/04/2020|0.1|Adicionando Custo e Tempo|Bruno Duarte e Ernando Braga|
