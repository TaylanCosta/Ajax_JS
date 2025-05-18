# Ajax_JS
Trabalho sobre o Ajax. Professor: Araya
SENAC DF

# Comparação de Métodos AJAX em JavaScript

Este repositório contém uma pesquisa comparativa e implementações do uso de diferentes métodos para realizar requisições AJAX em JavaScript: XMLHttpRequest, fetch, Promises e async/await.

## Pesquisa Comparativa

### XMLHttpRequest

**é uma API antiga usada para fazer requisições HTTP em JavaScript. Introduzida antes da padronização do Promise, é baseada em callbacks e tem uma sintaxe mais verbosa.**
- Vantagens:
    - Compatibilidade com navegadores muito antigos
- Desvantagens
     - intaxe verbosa e baseada em callbacks
     - Não suporta Promises nativamente

### fetch

**O fetch é uma API moderna que substitui o XMLHttpRequest. Retorna uma Promise e tem uma interface mais limpa e fácil de usar.:**
- Vantagens:
    - intaxe mais limpa e intuitiva
    - Integração nativa com Promises</li>
- Desvantagens:
    - Não envia/recebe cookies por padrão
    - Não rejeita automaticamente em respostas HTTP de erro (404, 500, etc)

### Promises

 **Promise é um objeto que representa a eventual conclusão (ou falha) de uma operação assíncrona. É a base para o fetch e outras APIs modernas.** ...
* **Facilidade de Uso:** 
- Vantagens:
    - Encadeamento mais limpo
    - Melhor tratamento de erros</li>
  - Desvantagens:
      -  Ainda pode ficar verboso com muitas operações encadeadas

### async/await

 **Introduzido no ES2017, async/await é uma sintaxe que simplifica o uso de Promises, permitindo escrever código assíncrono de forma síncrona.** 
- Vantagens:
    - Código mais legível e linear
- Desvantagens:
    - Requer funções marcadas como async
    -  Pode esconder a natureza assíncrona do código para iniciantes


## Códigos Implementados

* [ajax\_fetch.html](ajax\_fetch.html) - Implementação usando.
* [ajax\_promises.html](ajax\_promises.html) - Implementação usando.
* [ajax\_async\_await.html](ajax\_async\_await.html) - Implementação usando.
