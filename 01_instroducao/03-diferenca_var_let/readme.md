### Qual a diferença entre VAR e LET?

> para conseguirmos entender a diferença entre esses dois jeitos de declarar variáveis é preciso
> entender sobre escopo

### Escopo

>  Podemos entender escopo como paredes {CHAVES} que separam coisas {VALORES} que existem dentro
> desses chaves.
> Dentro de um arquivo js podemos ter variaveis, constantes, funções e objetos
#### var
> veja no arquivo variavelvar.js que está dentro desse diretório, não faz diferença uma variável
> estar declarada dentro ou fora dos pares de chaves, o resultado será o mesmo... mas isso apenas
> se estiver utilizando a palavra reservada var.
> 
#### let
> com o let a história é outra, ele consegue diferenciar e atribuir valores diferentes para dentro e
> fora das chaves {} veja no arquivo variaveislet.js

#### Recomendação
> nunca utilizar var de forma global, imagine, se ela está de forma "SOLTA" pode acontecer algo estranho com o contexto global que se está trabalhando
> alterada pelo objeto window de seu navegador, geralmente sempre utilizamos nomes parecidos para
> declarar variáveis então com certeza em um mesmo projeto você poderá ter var nome para isso ou
>aquilo.