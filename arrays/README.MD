# portfolio-web 
# Arrays

## Conceito

Arrays são estruturas utilizadas para armazenar vários valores em uma única variável.

## Funcionamento

Os elementos são armazenados em posições numeradas, iniciando pelo índice 0. É possível adicionar, remover, alterar e consultar valores armazenados no array.

## Onde é utilizado

Arrays são utilizados para armazenar listas de informações, como produtos, clientes, pedidos, nomes, preços e qualquer conjunto de dados relacionados.

## Exemplo Prático

Neste exemplo, foi criado um array contendo uma lista de personagens de um jogo. Ao clicar no botão, todos os personagens armazenados no array são exibidos na tela.

```javascript
const personagens = ["Sage", "Skadi", "Hotdoly", "TWS"];

function listarPersonagens() {
    document.getElementById("resultado").innerHTML =
        personagens.join(", ");
}
