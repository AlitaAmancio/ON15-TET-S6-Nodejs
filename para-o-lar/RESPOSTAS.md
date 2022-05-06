# Respostas

1 - O CRUD corresponde ao segundo nível de maturidade de uma API REST.

2 - Os verbos HTTP estão diretamente ligados com o CRUD (Create, Read, Update, Delete) : POST, GET, PUT, PATCH, DELETE, HEAD, OPTIONS sendo os mais conhecidos.

3 - O HATEOAS (Hypermedia as the Engine of Application State), quando aplicado, configura o último nível de maturidade de uma API, trazendo o modelo REST para um novo nível.

4 - Um método HTTP é idempotente se uma requisição idêntica pode ser feita uma ou mais vezes em sequência com o mesmo efeito enquanto deixa o servidor no mesmo estado.

5 - O PUT atualiza um recurso, por inteiro. Se um recurso cliente tem como informações os atributos nome, e-mail, data de nascimento e CPF, ao efetuar uma atualização passando o verbo PUT na requisição a API, todos os atributos do cliente devem ser enviados no corpo da requisição, mesmo aqueles que não serão atualizados, já o PATCH atualiza um recurso, porém parcialmente. Seguindo o mesmo exemplo do PUT, um cliente com seus atributos, nesse tipo de requisição apenas o atributo desejado será enviado no corpo da requisição. Geralmente para atualização é a ação mais utilizada, pois utiliza menos dados para navegação no tráfego de informação;

