<h1 align="center">
  <img src="https://ik.imagekit.io/h3pbjahr5l/github_explorer/bootcamp_gostack_w-mlUIi3D.png" />
</h1>

<h1 align="center">
  🚀️ Desafio 02 - Conceitos do Node.js
</h1>

## 📖️ Sobre o desafio
Desenvolvido durante o curso **Bootcamp Gostack** da [Rocketseat](https://rocketseat.com.br/).

Será uma aplicação para armazenar repositórios do meu portfólio, que irá permitir a **criação**, **listagem**, **atualização** e **remoção dos repositórios**, e além disso permir que os repositórios possam receber "likes".

---

## 💻️ Testes realizados
- **should be able to create a new repository:** Para que esse teste passe, sua aplicação deve permitir que um repositório seja criado, e retorne um json com o projeto criado.

- **should be able to list the repositories:** Para que esse teste passe, sua aplicação deve permitir que seja retornado um array com todos os repositórios que foram criados até o momento.

- **should be able to update repository:** Para que esse teste passe, sua aplicação deve permitir que sejam alterados apenas os campos url, title e techs.

- **should not be able to update a repository that does not exist:** Para que esse teste passe, você deve validar na sua rota de update se o id do repositório enviado pela url existe ou não. Caso não exista, retornar um erro com status 400.

- **should not be able to update repository likes manually:** Para que esse teste passe, você não deve permitir que sua rota de update altere diretamente os likes desse repositório, mantendo o mesmo número de likes que o repositório já possuia antes da atualização. Isso porque o único lugar que deve atualizar essa informação é a rota responsável por aumentar o número de likes.

- **should be able to delete the repository:** Para que esse teste passe, você deve permitir que a sua rota de delete exclua um projeto, e ao fazer a exclusão, ele retorne uma resposta vazia, com status 204.

- **should not be able to delete a repository that does not exist:** Para que esse teste passe, você deve validar na sua rota de delete se o id do repositório enviado pela url existe ou não. Caso não exista, retornar um erro com status 400.

- **should be able to give a like to the repository:** Para que esse teste passe, sua aplicação deve permitir que um repositório com o id informado possa receber likes. O valor de likes deve ser incrementado em 1 a cada requisição, e como resultado, retornar um json contendo o repositório com o número de likes atualizado.

- **should not be able to like a repository that does not exist:** Para que esse teste passe, você deve validar na sua rota de like se o id do repositório enviado pela url existe ou não. Caso não exista, retornar um erro com status 400.