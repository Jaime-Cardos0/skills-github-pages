---
layout: post
title: "Declaração de variáveis em JavaScript"
author: Jaime Cardoso
date: 2025-04-11 08:00:00
categories: [programação, aprendizado]
tags: [variáveis, JavaScript]
---

### Variáveis

#### O que são variáveis

**Variáveis:** são espaços na memória de um computador onde podemos guardar alguma informação mutável.

-[ ] -[ ] -[ ]
-[ ] -[X] -[ ]
-[ ] -[ ] -[ ]

<sub>Um espaço preenchi na memória.</sub>

####Declaração de variáveis em Javascritp (JS)

Para declarar uma variável em JS usamos as palavras reservadas `var`, `let` ou `const`
**var:** declara uma variável sem escopo, ou seja, uma variável que pode ser acessada em qualquer parte do código. O uso do var não é recomendado por conta dos possíveis
erros e falta de segurança.

**let:** é uma alternativa ao uso do var, fazendo sentir a localidade de escopo, ou seja, a variável só é lida no escopo em que fora declarada, sendo mais seguro e menos sujeitos a erros de escopo.

**const:** não declara uma variável, mas sim uma constante, ou seja, o valor declarado com const não é alterado no decorrer da execução do programa

####Exemplos de utilização

```javascript
var x = 12 
let w = true
const s = "String"


