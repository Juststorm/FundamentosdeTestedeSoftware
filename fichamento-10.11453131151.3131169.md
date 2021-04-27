# Incremental Strategy for Applying Mutation Operators Emphasizing Faults Dificult to be Detected by Automated Static Analyser

SILVA, Vinícius Barcelo; SPOTO, Edmundo Sérgio; ARAÚJO, Cláudio Antônio; VINCENZI, Auri M R. Incremental Strategy for Applying Mutation Operators Emphasizing Faults Difficult to be Detected by Automated Static Analyser. SBES‘17: Proceedings of the 31st Brazilian Symposium on Software Engineering, Ceará, Brasil, p. 24-33, 2017. Disponível em: [10.1145/3131151.3131169](https://doi.org/10.1145/3131151.3131169). Acesso em: 27 abr. 2021.

## 1. Fichamento de Conteúdo

O artigo trata de Testes de Mutação e busca dar continuidade aos estudos desenvolvido por Carlos Araújo e outros autores no estudo "Correlating automatic static analysis and mutation testing: towards incremental strategies" publicado um ano antes. No texto, os autores definem o Teste de Mutação por si só, seus benefícios, malefícios, explicam o custo e comparam os tipos dinâmicos e estático. Ainda, os autores trazem exemplo das ferramentas mais utilizadas no mercado para diferentes linguagens de programação. Neste estudo, a linguagem de programação escolhida é o C puro, a ferramenta para gerar os mutantes é a Proteum/IM e a utilizada para análise (estática) é a Splint. O trabalho é muito bem conduzido e explicado, parecendo com uma boa extensão a estudos já desenvolvidos. Os autores deixam claros seus métodos, resultados, deixam espaço para mais testes e relatam a importância de não se limitar ou confiar 100% no que foi obtido nesses diferentes testes, pois eles foram específicos. Com isso, foi possível concluir que os testes de mutação são sim eficazes e ideais para construção de bons programas (_softwares_), mas que muita das vezes eles podem conter vícios e não serem totalmente eficientes por uma série de fatores, sendo algo que eles querem combater uma causa disso: o erro humano.

## 2. Fichamento Bibliográfico

* O alto custo computacional tratado no artigo, e presentes em muitos outras pesquisas e testes como um ponto negativo, se trata do uso demasiado do hardware de uma máquina para realizar determinadas tarefas exaustivamente para obter resultados. Dependendo do alto custo, ele pode ser inviabilizado por máquinas não tão potentes ou pode acabar precarizando certos equipamentos (página 24)
* A resistência a ferramentas de teste automatizadas se dá pelo não conhecimento da eficiência real delas. Isso é, quando o teste é realizado manualmente, o programador/engenheiro de software tem a convicção que os testes estão sendo realizados e pode acompanhar de perto os resultados. Em contrapartida, as automatizadas são benéficas no sentido de pouparem o programador de criar vícios no próprio teste a fim de manipular resultados (página 25)
* Um conjunto de teste de baixa qualidade é um conjunto de teste que não cobre todas (ou a maioria das possibilidades). Para maximizar a saída e a eficiência de determinado teste, é necessário que busque se cobrir tudo que for possível, para que os resultados daquele conjunto de teste sejam analisados satisfatoriamente (página 26)

## 3. Fichamento de Citações

* "O Teste de Mutação gera, por meio dos operadores de mutação, versões do programa em teste contendo possíveis defeitos. Assumindo que o programa original está correto, é necessário construir testes que mostrem que o mutante e o programa original se comportem de maneira diferente e, nesse caso, descartando a possibilidade do programa possuir o defeito representado pelo mutante"
* "A hipótese do programador competente parte da premissa de que programadores experientes escrevem programas bem próximos de estarem corretos"
* "Para que um op gere mutantes é necessário que o programa original contenha as estruturas sintáticas exigidas pelo operador para criar os mutantes."
* "Nesse estudo foi empregada apenas a linguagem C e, assim, tais resultados não podem ser estendidos automaticamente para outras linguagens de programação."
* "Mesmo com um conjunto reduzido de dados, os testes realizados são condizentes e sustentam os resultados obtidos."
