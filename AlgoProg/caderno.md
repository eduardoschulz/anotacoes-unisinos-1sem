
# Table of Contents

1.  [Arquitetura de Von Neumann](#org4601a38)
2.  [Processos de Tradução](#orgcbc5162)
    1.  [Processo de Interpretação](#orgcb8216b)
    2.  [Processo de Compilação](#org204be70)
3.  [Algoritmo](#org2485968)
    1.  [Formas de Representar um Algoritmo](#orgc580fd2)



<a id="org4601a38"></a>

# Arquitetura de Von Neumann


<a id="orgcbc5162"></a>

# Processos de Tradução


<a id="orgcb8216b"></a>

## Processo de Interpretação

-   um interpretador

-   Um programa pode ser executado em qualquer maquina, desde que jhaja o interpretador disponivel. O codigo ira funcionar no Windows, OSX ou Linux mas eles precisam do interpretador.

-   Execução mais lenta

-   O Erro não eh detectado ate ser instruido no CPU


<a id="org204be70"></a>

## Processo de Compilação

-   Lingua -> Compilador -> Programa Objeto -> Arquitetura -> Execucao
-   Erro eh detectado na compilação
-   O código produzido não é portavel para qualquer arquitetura
-   Diferentes executaveis para diferentes arquiteturas

-   Java é uma Lingua Compilada
-   O compilador Java, entretandom não gera código para o *host* e sim para a máquina virtual java(a JVM).

Programa fonte(teste.java) -> Compilador Javac -> programa objeto(bytecode) exemplo teste.class &#x2013;> jvm
Tipos de Erro:

-   Lógico(compilador não consegue prever)
-   Compilação (compilador encontrou algum erro seja ele na syntax ou estrutura); Se compilar irá gerar um executavel; Se compilar irá gerar um executavel.
-   Execução(segmentation fault, etc&#x2026;)


<a id="org2485968"></a>

# Algoritmo

-   Um algoritmo é uma sequência de passos finita, que devem ser seguidos para alcançar algum objetivo
-   Para ordenar ao computador que realize uma determianda tarefa, um algoritmo é descrito em uma linguagem de programação
-   Este algoritmo é, então, compilado (ou interpretado) e executado.


<a id="orgc580fd2"></a>

## Formas de Representar um Algoritmo

-   Representam o algoritmo no nível lógico
    -   Abstrai detalhes referentes ao código
    -   não é ligada a alguma linguagem
-   Fluxograma
    -   Forma mais visual de ver o algoritmo
    -   ![img](./fluxo.png)
-   Pseudocódigo(português estruturado)
-   Descritiva (narração)

