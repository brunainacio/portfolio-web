# portfolio-web 
# Objetos em JavaScript

## Conceito

Objetos são estruturas utilizadas para armazenar informações relacionadas por meio de propriedades e valores.

## Funcionamento

Os dados são organizados em pares de chave e valor, permitindo representar entidades do mundo real, como pessoas, produtos e clientes.

## Onde é utilizado

Objetos são amplamente utilizados para representar e organizar dados em aplicações, facilitando o acesso e a manipulação de informações relacionadas.

## Exemplo Prático

Neste exemplo, foi criado um objeto representando um personagem de jogo. Ao clicar no botão, as informações armazenadas no objeto são exibidas na tela.

```javascript
const personagem = {
    nome: "Sage",
    classe: "Mago",
    nivel: 50,
    vida: 3200
};

function mostrarPersonagem() {
    document.getElementById("resultado").innerHTML =
        `Nome: ${personagem.nome}<br>
         Classe: ${personagem.classe}<br>
         Nível: ${personagem.nivel}<br>
         Vida: ${personagem.vida}`;
}
