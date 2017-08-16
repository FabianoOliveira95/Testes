# Testes
----
## O que são testes em software ?
Um software em desenvolvimento está passível de bugs ou falhas, e o teste é o processo responsável pela detecção dessas falhas durante o desenvolvimento do produto, para que elas sejam corrigidas antes da conclusão do programa. Aqui será tratado os principais tipos de testes usados atualmente.
## Teste Unitário
Para um correto funcionamento de um software, é preciso que tudo aquilo que compõe ele esteja em correto funcionamento, pois se uma parte está defeituosa, ela irá prejudicar todo o resto do programa. Para evitar esse problema, o teste unitário é implementado nessas "partes" do sistema, onde o objetivo é identificar possíveis falhas que poderão comprometer o correto funcionamento do resto do software, por isso o nome **unitário**, por focar nas pequenas partes do código, na unidade. Assim, esse teste foca na identificação de bugs que estejam ocorrendo em linhas de código, métodos e outras partes menores do programa em si, analisando o problema de forma isolada(1). <br />
**Exemplo:** Um método que testa a senha de uma conta, ele deve testar se ao digitar os caracteres, os mesmos são substituídos por um caractere especial que oculta a senha, também deve testar se a senha atende os padrões para a criação daquela determinada conta e deve impedir que a senha seja copiada ou colada.

## Teste de Integração
Basicamente, esse tipo de teste é responsável por avaliar se as partes de um programa estão funcionando corretamente em conjunto, assim durante o desenvolvimento, a equipe consegue identificar e corrigir possíveis problemas de compatibilidade, desempenho e dependência entre os componentes do programa, por exemplo, testar se a interação entre dois objetos de um sistema onde existem diferentes telas estão interagindo corretamente, pois ambos são dependentes, o programa deve ser capaz de mudar de tela corretamente sem a existência de travamentos ou lentidão(2). Também existem duas formas de implementar esse tipo de teste:

* **Teste de integração incremental** - O funcionamento do software é avaliado parte a parte, ou seja, é analisada cada etapa do processo, e essa análise pode ser executada tanto do nível de integração maior para a menor parte das interações, como do nível menor para o maior.

* **Teste de integração não incremental** - Aqui a análise das interações e relacionamentos do programa são executadas de um modo global, sem a necessidade de uma avaliação passo a passo.
## Teste do Sistema
Durante o desenvolvimento do software, ele deve passar pelas fases de **testes unitários** e **testes de integração** para identificar e resolver falhas antes da conclusão do sistema, porém, mesmo após o mesmo estar concluído, ainda não é garantido que o programa estará livre de erros ou atenderá as espectativas do cliente, por isso serão apresentadas algumas técnicas de testes que são executadas para encontrar problemas após a conclusão do projeto:
* **Teste Funcional** - Como o nome diz, o objetivo desse teste é verificar se as funcionalidades do sistema atendem ao que foi especificado, por exemplo, o sistema deve avisar se o usuário deu alguma entrada indevida em um campo específico como senha, aonde existe um padrão a ser seguido e foi digitado uma senha fora do padrão, se o programa aceitar, já é um erro que foi identificado. Também pode ser avaliado o desempenho como lentidão e se o sistema retorna o valor esperado(3).
* **Teste de Usabilidade** - Busca garantir se a interface do sistema é acessível e de bom entendimento ao usuário, por exemplo, se as funcionalidades de acesso a diferentes operações numa interface de home baking estão bem localizadas e de fácil acesso(4).
* **Teste de Desempenho** - Esse teste consiste em avaliar dois aspectos fundamentais para um bom desempenho de software, o **tempo de de execução** e a **vazão**. É esperado que o software atenda os critérios de desempenho, tempo de resposta, se todos os componentes do sistema estão funcionando corretamente e tendo as respostas esperadas. Por exemplo, testes que monitoram se um determinado sistema de banco de dados não está sofrendo com um gargalo de informações(5).
* **Teste de Carga** - Aqui o objetivo é avaliar se o sistema suporta uma grande quantidade de usuários simultâneos, por exemplo, o quanto o sistema de um banco irá aguentar se 5.000 usuários estiverem acessando ao mesmo tempo(6).
* **Teste de Segurança** - Teste que busca garantir que o sistema não esteja passível de acessos ilegais, ele busca avaliar a vulnerabilidade do software(7)
# TDD
O **Test-Driven Development** é basicamente a prática de escrever os testes antes de escrever o código do programa em desenvolvimento, mas de forma cíclica, criando etapas desse processo e as repetindo. Antes de ser implementada uma nova funcionalidade no sistema, primeiro se escreve o teste que irá testar essa funcionalidade.
## Ciclo de desenvolvimento TDD
* Escrever o teste (este não estará funcionando, pois não existe funcionalidade para ser testada)
* Implementar a funcionalidade
* Testar a funcionalidade, até que ela passe
* Refatorar o código dessa funcionalidade
* Escrever o próximo teste
**Vantagens do TDD** - A prática do TDD permite que toda a equipe que está no desenvolvimento do sistema, tenha um feedback rápido e maior conhecimento a cerca das funcionalidades do sistema, das que já foram implementadas e das que ainda serão; códigos menores e mais limpos; correção de bugs mais ágil tanto para detecção quanto para a correção dos mesmos; aumento da produtividade da equipe.
Muitos desenvolvedores ainda acham que é perca de tempo ou mais trabalho programar testes, porém isso é uma ideia muito equivocada, pois é muito visível que softwares que são entregues com bugs e com problemas de especificação acarretam em mais demanda de tempo e retrabalho, um software que passou por uma bateria de testes e avaliações antes da entrega ao cliente, tem grandes chances de atender os resultados esperados. Concluindo, o desenvolvimento que usa a prática TDD tende a ser mais curto e eficiente do que programas que não usaram esses processos, pois as chances de existirem bugs são grandes e dará mais trabalho ainda a manutenção do código dele(8).




## Referências
(1) http://testesdesoftware.com/teste-de-unidade/ <br />
(2) http://testesdesoftware.com/teste-de-integracao/ <br />
(3) http://testesdesoftware.com/testes-funcionais/ <br />
(4) http://www.idera.com.br/Servi%C3%A7os/TestedeSoftware.aspx <br />
(5) https://www.tiespecialistas.com.br/2015/11/teste-de-desempenho-de-software/ <br />
(6) http://www.devmedia.com.br/testes-de-desempenho-carga-e-stress/26546
(7) http://www.devmedia.com.br/teste-de-seguranca-agregando-confianca-ao-software/27792 <br />
(8) http://www.devmedia.com.br/test-driven-development-tdd-simples-e-pratico/18533
