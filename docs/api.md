# API

## Rotas principais do Gateway

| Rota | Serviço |
|---|---|
| `/auth/**` | Auth Service |
| `/account/**` | Account Service |
| `/product/**` | Product Service |
| `/order/**` | Order Service |
| `/exchange/**` | Exchange |

## Auth Service

| Método | Endpoint | Uso |
|---|---|---|
| `POST` | `/auth/login` | autenticar e gerar JWT |
| `POST` | `/auth/validate` | validar token internamente |

## Account Service

| Método | Endpoint | Uso |
|---|---|---|
| `POST` | `/account` | criar conta |
| `GET` | `/account/{id}` | buscar conta por ID |
| `GET` | `/account/username/{username}` | buscar por username |
| `PUT` | `/account/{id}` | atualizar conta |

## Product Service

| Método | Endpoint | Uso |
|---|---|---|
| `GET` | `/products` | listar produtos |
| `GET` | `/products/{id}` | buscar produto por ID |
| `POST` | `/products` | criar produto |
| `PUT` | `/products/{id}` | atualizar produto |
| `DELETE` | `/products/{id}` | remover produto |

## Order Service

| Método | Endpoint | Uso |
|---|---|---|
| `POST` | `/orders` | criar pedido |
| `GET` | `/orders` | listar pedidos do usuário |
| `GET` | `/orders/{id}` | detalhar pedido |

## Exchange

| Método | Endpoint | Uso |
|---|---|---|
| `GET` | `/exchange/{from}/{to}` | taxa de câmbio entre moedas |
| `GET` | `/exchange/currencies` | listar moedas suportadas |

## Observação

A documentação acima resume os endpoints que aparecem nos READMEs dos repositórios do projeto. 
