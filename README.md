# Projeto: Tabela de Produtos Colaborativa 📈

Este é um projeto desenvolvido para os alunos do curso **lets code CETech 2025**. O objetivo é construir coletivamente uma base de dados de produtos em formato JSON.

Posteriormente, este arquivo `data.json` funcionará como uma "API" fixa que será consumida por uma aplicação front-end, onde usaremos `fetch()` em JavaScript para buscar os dados e exibi-los em uma tabela HTML dinâmica.

## 🎯 Objetivo

1.  **Praticar o fluxo de trabalho do Git/GitHub:** Aprender a colaborar em um projeto real usando Fork, Branch, Commit e Pull Request.
2.  **Criar uma base de dados (API):** Contribuir com dados estruturados em JSON.
3.  **Consumir dados com JavaScript:** Preparar o terreno para a próxima etapa do projeto, que é buscar (`fetch`) esses dados e renderizá-los em uma página web.

## 🚀 Como Contribuir

Para adicionar um produto à nossa base de dados, siga os passos abaixo. Sua tarefa é adicionar **um novo objeto de produto** ao arquivo `data.json`.

### Passo a Passo

1.  **Faça o Fork do Projeto:** Clique no botão "Fork" no canto superior direito para criar uma cópia deste repositório na sua conta do GitHub.

2.  **Clone o seu Fork:** Em seu computador, execute o comando abaixo para clonar o repositório (lembre-se de trocar `SEU-USUARIO` pelo seu nome de usuário do GitHub).
    ```bash
    git clone [https://github.com/SEU-USUARIO/tabela-produto-JP.git](https://github.com/SEU-USUARIO/tabela-produto-JP.git)
    ```

3.  **Crie uma Nova Branch:** É uma boa prática criar uma branch separada para cada nova contribuição.
    ```bash
    cd tabela-produto-JP
    git checkout -b adiciona-meu-produto
    ```

4.  **Adicione seu Produto:**
    * Abra o arquivo `data.json` no seu editor de código preferido.
    * Adicione um novo produto ao final da lista, mantendo o formato JSON. **Atenção:** Lembre-se de adicionar uma vírgula `,` depois do último item da lista antes de inserir o seu.
    * Utilize o seguinte modelo para o seu produto:
        ```json
        {
          "id": 99,
          "name": "Nome do seu Produto",
          "category": "Categoria do Produto",
          "price": 123.45,
          "image": "[https://placehold.co/100x100/34495E/FFFFFF?text=Produto](https://placehold.co/100x100/34495E/FFFFFF?text=Produto)",
          "description": "Uma breve descrição sobre o produto.",
          "contribuidor": "Seu Nome"
        }
        ```

5.  **Faça o Commit e Push das suas alterações:**
    ```bash
    git add data.json
    git commit -m "feat: Adiciona o produto [Nome do Produto]"
    git push origin adiciona-meu-produto
    ```

6.  **Abra um Pull Request (PR):**
    * Volte à página do seu fork no GitHub.
    * Clique no botão "Contribute" e depois em "Open pull request".
    * Revise suas alterações e crie o pull request para que sua contribuição seja avaliada e adicionada ao projeto principal.

Pronto! Agora é só aguardar sua contribuição ser integrada ao projeto. 🤝
