# portfolio-web 
# Manipulação do DOM e Eventos

## Conceito

DOM significa Document Object Model. É uma interface de programação que permite interagir com documentos HTML. É possível adicionar, modificar ou excluir elementos em uma página da web. Também é possível tornar o site interativo, fazendo com que elementos respondam a eventos.

---

## Funcionamento

No DOM um documento HTML é representado como uma árvore de nós. 
O documento HTML é o nó raiz na hierarquia e tem um nó filho. Cada elemento do HTML se torna um nó da árvore e alguns desses elementos podem ter outros elementos, sendo possível ter relações de pai, filho e irmão.
Sem o DOM o JavaScript não conseguiria distinguir os elementos da página. 

Com o DOM é possível localizar elementos específicos pelo seu ID, classe, tag ou por seletores mais complexos do CSS. Depois de encontrar o elemento, o JavaScript passa a ter uma referência e pode manipula-la.
Diagrama que representa a estrutura básica do DOM: 

```
Document
========

HTML
-----

- Head
  - Title
- Body
  - H1
  - H2   
```

---

## Onde é utilizado

O DOM é utilizado sempre que o JavaScript precisa interagir com uma página da web. Exemplos de uso: 

* Alterar conteúdo da página
* Modificar estilos
* Responder a eventos
* Criar ou remover elementos
* Validação de formulários
* Aplicações modernas como React, Angular, Vue.js

---

# Eventos

Eventos são ações que acontecem na página e podem ser detectadas pelo JavaScript. Quando um evento ocorre uma função pode ser executada para responder essa ação. Exemplos: 

* Clicks
* Input
* Submit
* Mouseover
* Load






