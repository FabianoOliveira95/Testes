# Testes
----
## O que são testes em software ?
Um software em desenvolvimento está passível de bugs ou falhas, e o teste é o processo responsável pela detecção dessas falhas durante o desenvolvimento do produto, para que elas sejam corrigidas antes da conclusão do programa. Aqui será tratado os principais tipos de testes usados atualmente.
## Teste Unitário
Para um correto funcionamento de um software, é preciso que tudo aquilo que compõe ele esteja em correto funcionamento, pois se uma parte está defeituosa, ela irá prejudicar todo o resto do programa. Para evitar esse problema, o teste unitário é implementado nessas "partes" do sistema, onde o objetivo é identificar possíveis falhas que poderão comprometer o correto funcionamento do resto do software, por isso o nome **unitário**, por focar nas pequenas partes do código, na unidade. Assim, esse teste foca na identificação de bugs que estejam ocorrendo em linhas de código, métodos e outras partes menores do programa em si, analisando o problema de forma isolada(1).
## Teste de Integração
Basicamente, esse tipo de teste é responsável por avaliar se as partes de um programa estão funcionando corretamente em conjunto, assim durante o desenvolvimento, a equipe consegue identificar e corrigir possíveis problemas de compatibilidade, desempenho e dependência entre os componentes do programa(2). Existem duas formas de implementar esse tipo de teste:

* **Teste de integração incremental** - O funcionamento do software é avaliado parte a parte, ou seja, é analisada cada etapa do processo, e essa análise pode ser executada tanto do nível de integração maior para a menor parte das interações, como do nível menor para o maior.

* **Teste de integração não incremental** - Aqui a análise das interações e relacionamentos do programa são executadas de um modo global, sem a necessidade de uma avaliação passo a passo.
## Teste do Sistema
Durante o desenvolvimento do software, ele deve passar pelas fases de **testes unitários** e **testes de integração** para identificar e resolver falhas antes da conclusão do sistema, porém, mesmo após o mesmo estar concluído, ainda não é garantido que o programa estará livre de erros ou atenderá as espectativas do cliente, por isso serão apresentadas algumas técnicas de testes que são executadas para encontrar problemas após a conclusão do projeto:



## Referências
(1) http://testesdesoftware.com/teste-de-unidade/ <br />
(2) http://testesdesoftware.com/teste-de-integracao/
