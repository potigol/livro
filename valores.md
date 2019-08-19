# Valores e Variáveis


## Valores

Podemos guardar valores na memória dando-lhes um nome. Esse processo é chamado de _declaração de valor_. O nome serve para que possamos recuperar o valor mais adiante. No exemplo a seguir damos o nome `idade` ao número `18`, `país` ao texto `"Brasil"` e `preço` ao número `12.50`.

```python
idade = 18
país = "Brasil"
preço = 12.50
```

Quando precisamos de um valor é só usar seu nome.

```python
nova_idade = idade + 1     # nova_idade = 19
```

## Tipos

Cada valor que usamos tem um tipo. O tipo serve para dizer quais operações podemos realizar com os valores. No caso de `idade`, o tipo é `Inteiro`; no caso de `país`, o tipo é `Texto`; e no caso de `preço`, o tipo é `Real`.

Com valores dos tipos numéricos podemos fazer operações aritméticas como soma e subtração. Já com um texto podemos concatenar (juntar dois textos) com outro texto ou extrair parte dele para formar um novo texto.

Os principais tipos que temos são os seguintes:

| Tipo | Valores |
| --- | --- |
| Inteiro | `-4`, `0`, `5`, ... |
| Real | `-7.23`, `0.0`, `5.25`, ... |
| Texto | `"texto"`, `"ola"`, `"mundo"`, ... |
| Lógico | `verdadeiro` e `falso` |
| Caractere | `'a'`, `'4'`, `'&'`, ... |

Na definição de valores podemos especificar o tipo do valor. Por exemplo, podemos escrever:

```python
idade: Inteiro = 18
país: Texto = "Brasil"
preço: Real = 12.50
```

> A regra geral é
> ```python
> nome_do_valor : Tipo = Valor
>
> # ou
>
> nome_do_valor = Valor     # tipo omitido
> ```

Os tipos são essenciais em linguagens com tipagem estática como Potigol para verificar quais as operações são permitidas. Operações ilegais são facilmente descobertas pela violação dos tipos. Por exemplo a operação `18 + "Brasil"` daria um erro porque não podemos somar um inteiro com um texto.

O tipo geralmente pode ser omitido. Nesse caso, o próprio Potigol consegue _inferir_ (descobrir) o tipo no momento da declaração à partir tipo do valor.

### Declaração simultânea

No exemplo anterior declaramos três valores distintos, cada um em uma linha. Mas podemos declarar vários valores simultaneamente em uma mesma linha.

```python
idade, país, preço = 18, "Brasil", 12.50
```

Do lado esquerdo do sinal `=` temos a lista de nome e do lado direito temos os valores. O primeiro valor (`18`) será atribuído ao primeiro nome (`idade`), o segundo valor ao segundo nome e assim por diante.

Também podemos dar vários nomes ao mesmo valor. Neste caso temos uma lista de nomes e apenas um valor. No exemplo, `a`, `b` e `c` serão iguais a 40.

```python
a, b, c = 40
```

Um último detalhe sobre atribuições de valores é que uma vez atribuído um valor a um nome, nós não podemos mais alterar o valor. Por exemplo, se dizemos que `idade = 18`, não podemos dizer mais adiante que `idade = 19`. Isto daria um erro na execução do programa.

## Variáveis

### Declaração de Variáveis

### Atribuição
