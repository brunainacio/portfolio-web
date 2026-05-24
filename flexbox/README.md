# portfolio-web 
# Flexbox

## Conceito

O Flexbox possibilita organizar, alinhar e distribuir espaço entre itens em um contêiner. Um contêiner flexível estende os itens para preencher o espaço livre disponível, sendo possível que uma página se adapte a diferentes dispositivos. 

---

## Funcionamento

Algumas proriedades devem ser definidas no contêiner (elemento pai) enquanto outras devem ser definidas nos filhos (itens flexíveis). 

Principais propriedades: 
* flex-direction --> define direção (linha ou coluna)
* justify-content --> alinhamento horizontal
* align-itens --> alinhamento vertifcal
* flex-wrap --> permite quebrar linha
* gap --> espaço entre itens

---

## Onde é utilizado

O flexbox é muito utilizado para: 
* Menus de navegação
* Centralização de elementos
* Layouts responsivos
* Organização de formulários
* Barras laterais e cabeçalhos


---

## Exemplo prático

@
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
.container {
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 200px;
  background: lightgray;
}

.box {
  width: 80px;
  height: 80px;
  background: pink;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 20px;
}
</style>

<title>Exemplo Flexbox</title>
</head>

<body>

<div class="container">
  <div class="box">1</div>
  <div class="box">2</div>
  <div class="box">3</div>
</div>

</body>
</html>






