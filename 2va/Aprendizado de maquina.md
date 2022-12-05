**Aprendizado de máquina**

o aprendizado de máquina é como um campo de estudo que dá aos computadores a habilidade de aprender sem terem sido programados para essa finalidade.

Quando estamos criando um modelo de aprendizado de máquina não informamos ao computador os passos a seguir para que ele aprenda o que precisa, isso porque o conhecimento é adquirido, no geral, a partir de modelos estatístico/matemáticos que reconhecem padrões em dados, criando a possibilidade que eles aprendam com seus erros e façam previsões em cima do que foi aprendido. Esses modelos podem ser definidos por diferentes formas de aprendizado.

**Supervisionado**

O aprendizado supervisionado é um paradigma de aprendizado de máquina que visa obter informações sobre o relacionamento entre as entradas e saídas de um sistema com base em um conjunto de amostras de treinamento. Algoritmos de aprendizado supervisionado analisam dados de treinamento e geram funções de inferência que serão usadas para mapear novos exemplos.

Para torná-lo menos abstrato, vamos considerar um exemplo, classificando e-mails como spam. Um modelo de classificação baseado em entradas sinalizadas fornece uma experiência que evita que você tenha que classificar quais e-mails são maliciosos ou não. Entre essas entradas, classificamos os e-mails como confiáveis ​​ou não confiáveis, para que o modelo aprenda a reconhecer a categoria a que os novos dados pertencem com base no que já sabe sobre esses dados rotulados.

![](https://dataat.github.io/introducao-ao-machine-learning/assets/02_classification/email_classifier.png)

**Não supervionado**

O aprendizado não supervisionado envolve o treinamento de máquinas em dados não rotulados e/ou classificados. Por exemplo, algoritmos que fazem isso tentam descobrir padrões ocultos que agrupam informações com base em semelhanças ou diferenças.

Para ilustrar isso com mais clareza, vamos imaginar um algoritmo de aprendizado não supervisionado que receba imagens contendo cães e gatos.

Depois de receber uma imagem, nada se sabe sobre as características de cada animal, ou seja, não podem ser classificados. No entanto, o algoritmo será responsável por encontrar semelhanças, padrões e diferenças que permitam distinguir cães e gatos. No exemplo citado acima, utilizamos uma técnica chamada agrupamento, mas existem outras como regras de associação e redução de dimensionalidade.

A técnica de agrupamento explicada no exemplo anterior envolve o agrupamento de dados não rotulados com base na semelhança ou diferença. Esses algoritmos de agrupamento ainda podem ser subdivididos em **agrupamentos exclusivos, sobrepostos, hierárquicos** e **probabilísticos.**

**Regras de Associação**

Usando regras de associação, procuramos descobrir os relacionamentos que descrevem a maioria dos dados. Essa associação é amplamente utilizada na análise de cestas de compras, onde as empresas buscam entender as relações de preferência de compra entre os produtos. Utilizando técnicas de redução de dimensionalidade, além de manter a integridade dos dados, o número de recursos será reduzido para que possam ser gerenciados pelo modelo.

**Aprendizado por reforço**

O aprendizado por reforço é o treinamento de modelos de aprendizado de máquina para tomar uma série de decisões. Os agentes aprendem a atingir metas em ambientes incertos e potencialmente complexos. No aprendizado por reforço, um sistema de IA é confrontado com uma situação. Os computadores usam tentativa e erro para encontrar soluções para problemas. 

Para que a máquina faça o que o programador deseja, a inteligência artificial é recompensada ou punida pelas ações que realiza. Seu objetivo é maximizar a recompensa total. Enquanto o cientista de dados define a política de recompensa, as regras do jogo, ele não dá ao modelo nenhuma dica ou sugestão sobre como resolver o jogo. 

Cabe ao modelo decidir como executar as tarefas para maximizar as recompensas, começando com testes completamente aleatórios e terminando com políticas complexas.

Temos como exemplo um agente e uma recompensa com muitos obstáculos no meio, conforme a figura abaixo. O agente tem que encontrar o melhor caminho para alcançar a recompensa, e quando encontra um obstáculo, tem que ser penalizado (porque tem que escolher o caminho sem o obstáculo). Com o aprendizado por reforço, podemos treinar um agente para encontrar o melhor caminho.

![](https://lh6.googleusercontent.com/bRBFxfWqvjEk99YKR21p04jJwX8JLgK_FTZarHEc68Menj4lhCx9UFbubo7CzH1_DqkKwmbPqwlTzWe2diiS7veFRk4DYLExudji9NA5HyRl3SLb3qoni9HXBzRaS_ahVvJqjIk)
