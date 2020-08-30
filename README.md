# Instalação

```bash
npm install -g json-server

```

# db.json

O arquivo db.json será o arquivo de onde serão geradas as API's, nesse exemplo serão gerada duas nos endpoints /posts e /comments

# Iniciando o servidor

Agora é só rodar o comando abaixo e seu servidor estará iniciado. Lembrando que por padrão a API vai funcionar no enderço: http://localhost:3000

```bash
json-server --watch db.json

```

# Rotas

| Request | URL | Descrição |
| --- | --- | --- |
| `GET` | /posts | 	Busca todos os posts |
| `GET` | /posts/1 |Busca o post de id=1 |
| `POST` | /posts | Salva um post|
| `PUT` | /posts/1 |Atualiza os dados de um post |
| `PATCH` | /posts/1 |Atualiza parte dos dados do post |
| `DELETE` | /posts/1 |Remove um post |
| `GET` | /comments | 	Busca todos os comentários |
| `GET` | /comments/1 |Busca o comentário de id=1 |
| `POST` | /comments | Salva um comentário |
| `PUT` | /comments/1 |Atualiza os dados de um comentário |
| `PATCH` | /comments/1 |Atualiza parte dos dados do comentário |
| `DELETE` | /comments/1 |Remove um comentário |

As rotas vão ser compostas pelo endereço base (localhost:3000) mais o recurso que você quer acessar com por exemplo “posts”.
Para executar os requests de exemplo abaixo você pode usar a ferramenta Postman (https://www.getpostman.com/) ou alguma outra de sua preferencia.
Para ver os resultados na pratica assista o vídeo acima ou execute os exemplos no seu computador.
