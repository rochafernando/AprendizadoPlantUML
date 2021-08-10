# Diagram de Classes
Ele permite a visualização das classes que vão compor o sistema com seus respectivos atributos, métodos e relação entre as demais classes.

## 4.1 - Persistência.
Ver Livro

## 4.2 - Classes, Atributos e Métodos
Classes são a representação de algo, elas possuem atributos que armazenam valores (estados) e os metódos que são suas funções (ações que executam).

Na UML o diagrama de classes não se preocupa em defininir que etapas esses métodos deverão percorrer quando forem chamados, sendo essa uma função atribuida a outros diagramas.

Na UML uma classe é representada através de um retângulo **com até 3 divisões** (não obrigatoriamente haverá as 3).

1. Contém o nome da Classe.
2. Atributos e seus tipos de dados
3. Métodos.

Conforme o exemplo abaixo:

![Classe](../images/DiagramaDeClasses/Fig41.png "Classe")

## 4.3 - Relacionamentos
As classes costumam se relacionar como uma forma de compartilharem informações e processos entre si, de forma a a colaborarem umas com as outras

### 4.3.1 - Associações
Associações descrevem o tipo de vínculo que ocorre entre as classes.
Elas podem ser:

**unárias** -> auto relacionamento

**binárias** -> Duas classes

**ternária ou N-ária** -> Três ou mais classes envolvidas

As associações representam um equivalente mais próximo do MER (Modelo Entidade Relacionamento), ou seja, seu objetivo é definir a maneira como as classes estão unidas e interagem entre si, compartilhando informações.
Elas são representadas por retas como no diagrama de caso de uso e também pode conter setas indicando sua navegabilidade (sentido da informação entre classes envolvidas) *não obrigatório.

Essas retas também podem conter títulos para determinar o tipo de vínculo entre as classes.


#### Associação Unária ou Reflexiva

Relação de uma classe com ela própria

![AssociacaoUnaria](../images/DiagramaDeClasses/Fig41.png "AssociacaoUnaria")

