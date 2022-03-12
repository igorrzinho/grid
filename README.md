# grid
 para usar o grid usamos para definir as colunas `grid-template-column: ;` e para as linhas usamos `grid-template-rows: ;` podemos definir quantas colunas quisermos até 12 as linhas não tem limite
 * para definir-mos os tamanhos das colunas 
```` css
grid-template-columns: 100px 300px auto ;
```` 
  a primeira coluna terá 100 píxeis de largura a segunda 300 e as demais largura automáticas
 * para definir-mos a altura das linhas
```` css
grid-template-rows: 100px 300px auto ;
````
  a primeira coluna terá 100 píxeis de altura a segunda 300 e as demais altura automáticas

## grid-gap

 grid-gap é nada mais que o espaçamento entre os elementos    
 podemos usar o `grid-column-gap: ;` que define o espaçamento entre as colunas, `grid-row-gap: ;` define o espaçamento entre as linhas, `grid-gap: ;` que define o espaçamento entre ambas
* grid-column-gap
esse define o espaçamento entre as colunas
```` css
grid-column-gap: 10px;
`````
teremos o espaço entre as colunas 10 px
* grid-row-gap
esse define o espaçamento entre as linhas
```` css
grid-row-gap: 10px;
`````
teremos o espaço entre as linhas 10 px
* grid-gap
podemos usar apenas um valor 
```` css
grid-gap:10px;
````
que será aplicativo para a colunas e as linhas, ou
```` css
grid-gap:10px 20px;
````
que o primeiro valor será o espaço entre as linhas do segundo o espaço das colunas
