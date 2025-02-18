# Markdown

Markdown é uma linguagem de marcação de texto

# Cabeçalhos

# Nível 1 
## nível 2
### Nível 3
#### Nível 4
##### Nível 5
###### Nível 6

# Listas

Existem dois tipos de Listas: ordenadas e não-ordenadas.

- item não ordenado 
- outro item
- mais um item

1. Item ordenado
1. outro item
1. mais um
1. e outro...

## Marcações em linha 

linha com **negrito**

linha com *italico*

Um _texto italicizado_

## Imagens

![](logo_senac.png)
![](logo_senac.png)

## links

Links são fáceis

Clique [Aqui](https://senacrs.com.br) para ir ao SENAC.

para a imagem virar um link é só colocar o código da imagem

[![](logo_senac.png)](https://senacrs.com.br)

E links tbm funcionam para URLS locais, que levam a outras páginas Markdown no nosso projeto

volte para o [README](README.md)

## código

podemos escrever trechos de códigos usando fontes menos espaçadas para preservar as tabulações e intentações do códigos

```
aqui podemos escrever o texto puro.
os espaços e as quebras de linhas são preservadas.
```
``` java
class 01{
public static void main(String args[]){
    system.out.println("ola mundo");
};
    
}
```


aqui no vs code e tbm no github
(e outros hosts como codeberg) podemos tbm usar *colorização de sintaxe*
 
 isso tbm funciona para centenas de linguagens 

 ## caixas de destaque /citação
 
 é necessário textos para chamar a atencção para certos parágrafos. Um caso comum é para citações longas. Outro caso é o de destaques de textos.

 > este parágrafo que será renderizado em destaque nos vizualidores Markdown.

 essas caixas podem conter vários parágrafos também.

 > Um primeiro parágrafo em destaque.
 >
 > Um segundo parágrafo em destaque.