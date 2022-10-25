# Tipos no Java

No Java, temos algumas palavras que são reservadas e elas não podem ser utilizadas. Elas são chamadas de tipos primitivos.

> Os oito tipos primitivos em Java são: 
> 
> int, byte, short, long, float, double, boolean e char - esses tipos não são considerados objetos, e representam valores brutos.
> 
> Eles são armazenados diretamente na pilha de memória(Memory Stack)


### Tabela de Tipos Primitivos e seus valores:

![Tabela de Tipos Primitivos](http://www.universidadejava.com.br/images/2011-06-15-java-tipos-primitivos-01.png)

Por mais que tenhamos quatro números inteiros, as vezes utilizamos o int dado que a 
JVM por compatibilidade converte tipos literais para int.
> Por exemplo: 
> 
>100 mesmo sendo byte, ele converte para int. 
> 30.000 mesmo sendo um short -> vira int. 
> Logicamente para números maiores ele converte para long.

**Pontos flutuantes**
Float ocupa metada da memória consumida que um tipo double, porém ele é menos utilizado. Ele sofre limitacão
que pode comprometer o seu uso: **somente mantém uma precisão decimal entre 6 e 7 dígito**

Portanto, é mais comum utilizar double nos projetos por uma questão de garantia dados os algoritimos utilizados. 

É importante ver qual tipo de variável que vai servir para o meu problema. Por exemplo: **Qual tipo de dados eu utilizaria para determinar a idade de uma pessoasou o salário de um funcionário?**

# Variaveis no Java

Variavel é uma identificacao de um espaco em memória. Temos uma convencão de como são declaradas uma variável:
```
<Tipo> <nomeVariavel> <atribuicaoDeValorOpcional>
```

Exemplo:

```
int idade;
int anoFabricacao = 2021
double salarioMinimo = 2500
```
Obs1: Se usar o . ele é um número flutuante: 2500.44
Obs2: O tipo long precisa terminar com o L ao final do numero em questão. E o float precisa terminar com o Float.

Exemplo:

```
float pi = 3.14F;
long cpf = 987654332109L;
```

**Java é uma linguagem fortemente tipada!**

[⬆ Voltar ao topo](Resumo)<br>
