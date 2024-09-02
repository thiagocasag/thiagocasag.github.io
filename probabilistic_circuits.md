## Um Estudo sobre Algoritmos para Aprendizado Estrutural de Circuitos Probabilísticos

**Descrição do Projeto:** 
Um comentário recorrente acerca de redes neurais é que, apesar de sua alta acurácia e taxa de acertos, sua estrutura (e até sua prévia seleção de variáveis) traz consigo o que é conhecido como um problema "caixa-preta". Isto significa, resumidamente, que após o treinamento de um modelo como esse, sua tomada de decisão é de difícil compreensão, e correções de possíveis erros de treinamento tornam-se difíceis de rastrear. Para tal, uma alternativa seria a utilização de um modelo gerativo, que, após treinado, guarda consigo uma distribuição de probabilidade explícita das variáveis fornecidas. Um modelo que se encaixa nestas condições é conhecido por **circuito probabilístico** (do inglês, _Probabilistic Circuit_, ou, apenas, **PC**).

Na primeira etapa deste projeto, que foi grande parte da minha iniciação científica e TCC enquanto aluno de graduação, estudei a estrutura deste modelo, e implementei uma das técnicas conhecidas na literatura para gerar o "esqueleto" de um circuito probabilístico com base em um conjunto de dados. 

Na segunda etapa, estudei um algoritmo para encontrar modas de um PC: como dito anteriormente, por ser um modelo gerativo, ele representa uma distribuição de probabilidade. Para determinadas tarefas, é interessante encontrar os pontos máximos destas distribuições, conhecidos por modas, que representam, via de regra, estados mais prováveis. Implementei este algoritmo e verifiquei algumas características da técnica implementada em conjuntos de dados gerados artificialmente, tais como área de convergência do domínio e velocidade de convergência do algoritmo.

Todo o trabalho produzido foi implementado na linguagem _Julia_ e pode ser acessado [aqui](https://github.com/thiagocasag/ic-tcc).
