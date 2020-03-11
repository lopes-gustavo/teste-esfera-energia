# Projeto ESFERA ENERGIA

Queremos criar um website, usando Angular 9, para mostrar uma lista de usuários, separados por empresas.

A lista de usuários pode ser buscada em:
`GET https://jsonplaceholder.typicode.com/users`

Um usuário está estruturado na forma:
```
{
    "id": <number>,
    "name": <string>,
    "username": <string>,
    "email": <string>,
    "address": {
        "street": <string>,
        "suite": <string>,
        "city": <string>,
        "zipcode": <string>,
        "geo": {
            "lat": <string>,
            "lng": <string>
        }
    },
    "phone": <string>,
    "website": <string>,
    "company": {
        "name": <string>,
        "catchPhrase": <string>,
        "bs": <string>
    }
}
```


## Telas

Queremos 2 telas.

### Principal

#### Descrição
Essa tela vai conter uma tabela, listando os usuários, por empresa, conforme a imagem abaixo.

![](https://i.stack.imgur.com/EJVPR.png)

#### URL
Essa tela deve ser entregue a partir da raiz: `http://localhost:4200/`

#### Detalhes

Essa tabela será clicável por linha.

Caso a linha seja clicada, o app deverá ir para outra tela, que deve listar as informações do usuário em questão.


### Secundária

#### Descrição
Essa tela deve listar as informações do usuário em questão.

#### URL
Essa tela deve ter um link único, por exemplo: `http://localhost:4200/<id>`, que possa ser acessada diretamente, caso desejado

#### Detalhes
O `id` não deve ser mostrado.

**O layout dessa tela ficará por sua conta.**

Fique a vontade para adicionar outras informações (como por exemplo mapa mostrando a localização do usuário ou link para o website dele, etc)


## Observações

* Utilize [Angular 9](https://angular.io)

* Utilize [Bootstrap](https://getbootstrap.com) ou [MDBootstrap](https://mdbootstrap.com/docs/angular/getting-started/download)

* Utilize as boas práticas citadas no [site oficial](https://angular.io/guide/styleguide)

* Crie [testes unitários](https://angular.io/guide/testing)

* Crie uma página 404 caso a URL digitada não seja válida

* Uma vez carregado os usuários, em caso de mudança de tela, os dados não devem ser carregados novamente ([RouteReuseStrategy](https://angular.io/api/router/RouteReuseStrategy))

* Adicione no README um passo a passo de como testar a aplicação localmente e como buildá-la para produção

* Adicione no README um passo a passo de como rodar os testes unitários

* Não é necessário criar testes de integração

* Caso tenha alguma dúvida da estória, fique a vontade para criar premissas. Só deixe-as explícitas no README do projeto.

* Não esperamos que faça tudo do projeto. Priorize aquilo que acha mais importante e entregue no prazo estipulado.

* Avaliaremos o seu modo de pensar, as boas práticas, o que você achou prioritário e o código em si

__________

#### Estamos abertos para tirar quaisquer dúvidas ou sugestões que venha a ter do projeto. Mande uma mensagem pra gente!
