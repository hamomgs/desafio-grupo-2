# Desafio Quebra Tudo

Desafio da escola [Vai na Web](https://www.linkedin.com/company/vainaweb/): Os alunos foram divididos em grupos para criar programas em Portugol. Os códigos foram posteriormente "quebrados", e o desafio consistiu em praticar a revisão de código, aplicando os conhecimentos adquiridos em sala de aula.

## 📚 Sobre o Gerenciador de Estoque

O gereciador de estoque pode conter até 100 produtos e cada produto deve ter nome, quantidade e preço unitário (preço por unidade do produto). Esses produtos serão armazenados em uma matriz chamada "produtos".

- Matriz: `cadeia produtos[100][3]` 
- Descrição: Cada linha é um produto, podendo ter até 100, e cada coluna representa uma informação
  - coluna 0: Nome do Produto
  - coluna 1: Quantidade de Produtos
  - coluna 2: Preço Unitário

### 🖼️ Representação Visual da Matriz:

| Nome do Produto | Quantidade | Preço Unitário |
|-----------------|------------|----------------|
| Produto 1       | 43         | 5.99           |
| Produto 2       | 20         | 15.49          |
| Produto 3       | 15         | 78.29          |
| ...             | ...        | ...            |
| Produto 100     | 8          | 189.9          |

##

### ⚙️ Funções

- `adicionarProduto()`: Adiciona um produto, mas antes de adicionar verifica se o produto já existe ou se o estoque está cheio. Se passar nas validações, é adicionado o novo produto.

- `atualizarProduto()`: Altualiza um produto, após verificar se o produto existe, o usuário pode atualizar o preço unitário e quantidade do produto.

- `removerProduto()`: Remove um produto, após verificar se ele existe, o item é removido do estoque.

- `pesquisarProduto()`: Exibe as informações de um produto no console. O usuário deve pesquisar pelo nome exato do produto.

- `exibirProdutosEstoque()`: Exibe uma lista com todos os produtos do estoque e suas informações.

- `calcularValorTotalEstoque()`: Calcula o valor de cada produto com base na quantidade (produto x quantidade) e soma, no final exibindo o valor total do estoque.

- `inicio()`: É onde fica o "Menu".

### 💻 Demonstração do Sistema funcionando

<details>
  <summary>Vídeo</summary>

  ```
  Vídeo foi gravado mas não editado kkkk, já já colocamos aqui.
  ```
</details>

##

## 👨‍💻 Integrantes do Grupo 2

<table>
  <tr>
    <td align="center"><a href="https://www.linkedin.com/in/alinemelofrontend/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/109696840?v=4" width="100px;" alt=""/><br /><sub><b>Aline Melo</b></sub></a><br /><a href="https://github.com/alinemello29" title="Aline Melo">👨‍💻</a></td> 
    <td align="center"><a href="https://www.linkedin.com/in/hamomgs/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/88857655?v=4" width="100px;" alt=""/><br /><sub><b>Hamom Silva</b></sub></a><br /><a href="https://github.com/hamomgs" title="Hamom Silva">👨‍💻</a></td>
    <td align="center"><a href="https://github.com/JoaodevGabriel"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/116814125?v=4" width="100px;" alt=""/><br /><sub><b>João Gabriel</b></sub></a><br /><a href="https://github.com/JoaodevGabriel" title="João Gabriel">👨‍💻</a></td>
    <td align="center"><a href="https://www.linkedin.com/in/luccassilvaa/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/104798291?v=4" width="100px;" alt=""/><br /><sub><b>Luccas Silva</b></sub></a><br /><a href="https://github.com/LuccasSilvaa" title="Luccas Silva">👨‍💻</a></td>
    <td align="center"><a href="https://github.com/msssampaio2"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/144922878?v=4" width="100px;" alt=""/><br /><sub><b>Mariana Santana</b></sub></a><br /><a href="https://github.com/msssampaio2" title="Mariana Santana">👨‍💻</a></td>
</tr>
</table>

## 🧑‍🏫 Instrutores

<table>
  <tr>
    <td align="center"><a href="https://www.linkedin.com/in/samuel-silveriom/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/103957897?v=4" width="100px;" alt=""/><br /><sub><b>Samuel Silvério</b></sub></a><br /><a href="https://github.com/Samuel-prata" title="Samuel Silvério">🧑‍🏫</a></td> 
    <td align="center"><a href="https://www.linkedin.com/in/leno-rafael-85a2ab1ba/"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/73203800?v=4" width="100px;" alt=""/><br /><sub><b>Leno Rafael</b></sub></a><br /><a href="https://github.com/lenors" title="Leno Rafael">🧑‍🏫</a></td>
</tr>
</table>
