# portfolio-web 
# Funções

## Conceito

Funções são blocos de códigos que executam uma determinada tarefa. Isso permite organizar o código, evitar repetições e deixar a manutenção e compreensão do programa mais fácil. 

---

## Funcionamento

Uma função é definida com um conjunto de instruções e pode ser executada sempre que for chamada. É possível receber informações por parâmetros, processar os dados e retornar um resultado. Dessa forma, pode ser reutilizada diversas vezes em diferentes partes da aplicação.

```
function somar() {
    let numero1 = Number(document.getElementById("num1").value);
    let numero2 = Number(document.getElementById("num2").value);

    let resultado = numero1 + numero2;

    document.getElementById("resultado").innerHTML =
        "Resultado: " + resultado;
}
```

No exemplo acima a função recebe dois números como parâmetros, faz a soma e retorna o resultado. 

---

## Onde é utilizado

As funções são utilizadas em praticamente todas as aplicações desenvolvidas. São usadas para validar formulários, realizar cálculos, manipular dados...

---






