# Como escrever um README.md

De acordo com as próprias documentações do github, um Readme é o primeiro arquivo que um visitante olhará em seu repositório, funcionando como uma capa do seu trabalho/repositório.

Esse arquivo inclui informações do **repositório/projeto** como:

1. Título do projeto;
2. O que é o projeto;
3. Como instalar o projeto;
4. Como usar o projeto;
5. Quem contribuiu com o projeto;
6. Contato para usuários que tiverem dúvidas sobre o projeto;

## Em qual linguagem é feito o README.md?

O README é escrito na linguagem Markdown, uma linguagem de marcação que converte o texto
escrito para um HTML. Por isso que a extensão do arquivo readme é .md, que vem de Markdown.

## Como escrever em Markdown?

Por o readme ser feito utilizando Markdown, o caminho para um bom readme é
saber como escrever em Markdown, concorda?

Assim, neste tutorial, o objetivo é te ensinar as principais funcionalidades
da linguagem Markdown!

Não se preocupe, não é difícil. As maiorias dos textos escritos em Markdown
utilizam os seguintes caracteres para estilização: #, \, *, !, [ ], ( ).

Vamos aprender um pouquinho mais sobre o uso deles abaixo!

### Como escrever Títulos

Os títulos são usados para indicar seções principais em um documento. Em Markdown são escritos utilizando as hashtags #, de forma que
a quantidade de hashtags que iremos utilizar é igual ao nível do título.

Exemplo:

````
# Título nível 1
## Título nível 2
### Título nível 3
#### Título nível 4
##### Título nível 5
###### Título nível 6
````

Resultado:

# Título nível 1
## Título nível 2
### Título nível 3
#### Título nível 4
##### Título nível 5
###### Título nível 6

## Formatando textos em Markdown

### Negrito

Para escrever em negrito com Markdown, você pode utilizar tanto 2 asteriscos `**`
como 2 underline `__` antes e depois do texto que pretende destacar.

Exemplo:

`Um exemplo do **texto em negrito**`

`Outro exemplo do __texto em negrito__`

Resultado:

Um exemplo do **texto em negrito**

Outro exemplo do __texto em negrito__

### Itálico

Para escrever em negrito com Markdown, você pode utilizar tanto 1 asteriscos `*`
como 1 underline `_` antes e depois do texto que pretende destacar.

Exemplo:

`Um exemplo do *texto em itálico*`

`Outro exemplo do _texto em itálico_`

Resultado:

Um exemplo do *texto em negrito*

Outro exemplo do _texto em negrito_

### Rasurado

Para escrever com efeito riscado com Markdown, você utiliza 2 til `~~` antes e depois do texto que pretende destacar.

Exemplo:

`Um exemplo do ~~texto riscado~~`

Resultado:

Um exemplo do ~~texto riscado~~

## Listas

### Listas Não Ordenadas

As listas não ordenadas, são listas de itens que não possuem uma numeração. Assim, é para itens que você não se importa com a ordem deles na sua lista.

Para criar uma lista não ordenada você pode usar os seguintes caracteres na frente do seu item: `+`, `-`, `*`

Exemplo:

```
- Item 1
- Item 2
- Item 3
```

Resultado:

- Item 1
- Item 2
- Item 3

### Listas Ordenadas

Se você deseja criar uma lista de itens com numeração, as listas ordenadas são perfeitas para isso!

Para criar uma lista ordenada basta enumerar os itens com `1.`, `2.`, `3.` e assim por diante!

Exemplo:

```
1. Item 1
2. Item 2
3. Item 3
```

Resultado:

1. Item 1
2. Item 2
3. Item 3

## Links

Para criar links no markdown você precisa combinar o uso de colchetes `[ ]` com os parenteses `( )`e formar a seguinte sintaxe:

```
[título do link](URL-Endereço da página)
```

Assim, temos como exemplo:

```
[Visite o meu github](https://github.com/joaosilvacruz)
```

Resultado:

[Visite o meu github](https://github.com/joaosilvacruz).

Assim, você clicar no título do link e ir à página que deseja!

### Links de arquivos do repositório

Além disso, link também pode ser utilizado para redirecionar o usuário a arquivos do seu próprio repositório. Utilizando a mesma estrutura e repassando a URL do arquivo desejado.

```
[Pasta imagens](https://github.com/joaosilvacruz/tutorial-readme/tree/main/imagens)
```

## Imagens

Para inserir imagens com markdown é bem-parecido com a inserção de links visto anteriormente, bastando apenas adicionar uma exclamação `!` na frente dos colchetes.

A sintaxe é:

```
![Descrição da imagem](URL da imagem)
```

**OBS.: Atente-se a digitar uma boa descrição da imagem para garantir a acessibilidade**

Exemplo:

```
![Imagem do meu perfil do meu linkedin](https://github.com/joaosilvacruz/tutorial-readme/blob/main/imagens/linkedin.jpg)
```

OBS2.: Veja que como URL coloquei uma imagem que está no meu próprio repositório. Você pode colocar dessa forma ou de imagens de outras fontes.

Resultado: 

![Imagem do meu perfil do meu linkedin](https://github.com/joaosilvacruz/tutorial-readme/blob/main/imagens/linkedin.jpg)

## Blocos de código

Em alguns momentos pode ser que você deseje colocar blocos de código no seu readme para explicar alguma parte do código específico, assim como eu fiz com os comandos nesse tutorial.

### Códigos em linha

Podemos criar códigos em linha (inline) adicionando um acento crase <code>`</code> antes e depois do comando em destaque, da seguinte forma:

Exemplo:

```
Destacando o comando `System.out.prinln`
```

Resultado:

Destacando o comando `System.out.prinln`

### Códigos em múltiplas linhas

Caso você deseje destacar um grande trecho de código, utiliza-se três crases <code> ```</code> antes e depois do bloco de código desejado.

Exemplo:


\```

if (tutorial == "completo") {

System.out.println("Parabéns! Você aprendeu tudo!);

} else {

System.out.println("Complete o tutorial!")
}
\```

Resultado:

```
if (tutorial == "completo") {
    System.out.println("Parabéns! Você aprendeu tudo!);
    } else {
        System.out.println("Complete o tutorial!")
    }
```

## Linhas Horizontais

Caso você deseje separar seções do seu documento, as linhas horizontais são ótimas!

Para criar uma é bem simples, basta digitar três ou mais hífens em uma linha separada `---`.

Exemplo: 

```
Texto a ser separado

---

Texto a ser separado
```

Resultado:

Texto a ser separado

---

Texto a ser separado

















