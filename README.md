# Api REST e RESTFul

As APIs REST (Representational State Transfer) são conjuntos de diretrizes arquiteturais que visam melhorar a eficiência na comunicação entre sistemas distribuídos. Estas APIs seguem princípios como arquitetura cliente-servidor, estado representacional e uma interface uniforme.

O termo "RESTful" refere-se à implementação prática desses princípios em um serviço web. Serviços RESTful seguem as diretrizes da arquitetura REST, utilizando métodos HTTP para operações em recursos, identificados por URIs únicas. Além disso, eles manipulam recursos por meio de representações, como JSON ou XML, e seguem o conceito de HATEOAS para permitir navegação dinâmica.

Em conjunto, APIs REST e serviços RESTful oferecem uma abordagem padronizada para a construção de serviços web eficientes, escaláveis e interoperáveis, promovendo a simplicidade e flexibilidade na comunicação entre sistemas.

## Diferenças entre REST e RESTFul

REST (Representational State Transfer) é uma arquitetura que define princípios para redes escaláveis, incluindo statelessness, recursos identificáveis e operações padronizadas.

RESTful refere-se à implementação desses princípios em uma API web específica, adotando características como recursos identificáveis, representações padronizadas, statelessness e operações HTTP.

Principais diferenças são: Abordagem vs. Implementação: REST é uma arquitetura, enquanto RESTful é a aplicação desses princípios em uma API web., HATEOAS: Específico do RESTful, destaca a interação dinâmica baseada em hypermedia, Padrões e Convenções: RESTful segue padrões específicos, enquanto REST pode ser mais flexível na implementação, Ambos desempenham um papel crucial no desenvolvimento de sistemas distribuídos, proporcionando eficaz comunicação entre componentes de software.

## HTTP verbs

Os HTTP verbs são métodos fundamentais no protocolo HTTP, desempenhando papéis específicos na comunicação entre clientes e servidores. Aqui está um resumo conciso:

GET: Recupera dados de um recurso. Exemplo: GET /api/users/123

POST: Envia dados para criar um novo recurso. Exemplo: POST /api/users

PUT: Atualiza um recurso existente ou cria um novo. Exemplo: PUT /api/users/123

DELETE: Remove um recurso identificado pela URI. Exemplo: DELETE /api/users/123

PATCH: Aplica modificações parciais a um recurso. Exemplo: PATCH /api/users/123

OPTIONS: Obtém informações sobre opções de comunicação. Exemplo: OPTIONS /api/users

HEAD: Similar ao GET, retorna apenas cabeçalhos. Exemplo: HEAD /api/users/123

Esses verbos desempenham funções específicas e são escolhidos de acordo com a operação desejada em uma aplicação web, seguindo princípios fundamentais do protocolo HTTP.

## HTTP Status Code

Os códigos de status HTTP são indicadores essenciais que fornecem informações sobre o resultado de uma solicitação entre clientes e servidores. Aqui estão alguns códigos comuns:

1xx - Informativos: Indicações preliminares, como 100 Continue.

2xx - Sucesso: Confirma o sucesso da solicitação, como 200 OK ou 201 Created.

3xx - Redirecionamento: Informa sobre redirecionamentos, como 301 Moved Permanently.

4xx - Erro do Cliente: Indica problemas na solicitação do cliente, como 400 Bad Request ou 404 Not Found.

5xx - Erro do Servidor: Sinaliza problemas no servidor, como 500 Internal Server Error.

Esses códigos ajudam a compreender e reagir adequadamente durante a interação com serviços web, fornecendo informações sobre o estado da solicitação.