1-Por que devemos fazer testes automatizados nas aplicações que desenvolvemos?

uma das principais razões é Aumenta a eficiência do processo de testagem, esses testes estão menos suscetíveis a falhas humanas, pois sempre são repetidos da mesma exata maneira.

2-O que são testes unitários?

São testes que verificam se uma parte específica do código, costumeiramente a nível de função, está funcionando corretamente.

3-O que são testes automatizados?

ão programas que executam testes em softwares que estão em construção de uma forma padronizada, sem ser necessário a intervenção humana. Pois, tais testes possuem funcionalidades capazes de testar de forma automática todos os aspectos de uma plataforma, com o intuito de assegurar um desempenho adequado.

4 -Escolha uma pirâmide de testes e descreva com suas palavras cada secção da pirâmide.

I - camada da base: testes unitarios; testa pequenas partes do codigo de maneira isolada e independente, como componentes, funções e afins, sendo possivel achar o local exato de uma falha caso o teste falhe.

II-camada do meio:testes de integração; esse tipo de teste tem como objetivo tester Unidades interando entre si, alguns exemplos de testes de integração são testes que se comunicam com API's, micro-serviços, banco de dados e etc..

III-camada do topo: Testes de Ponta a Ponta (E2E); a função desse teste é simular a aplicação em seu estado final, um teste que simula o ambiente real, em outras palavras, testam a aplicação de ponta a ponta, validam se está tudo como o esperado para tais funcionabilidades, garantir o funcionamento do fluxo da aplicação e etc, esse teste tem nível de complexidade e tempo para execução ainda mais elevado, fazendo-se necessária uma escolha bastante criteriosa de quais cenários terão cobertura de testes nesse nível.
