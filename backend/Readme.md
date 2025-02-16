# 🚀 Backend do Site de Reciclagem de Eletrônicos

Este repositório contém o backend para um site de reciclagem de eletrônicos, desenvolvido com Node.js, Express e MongoDB. O sistema oferece APIs para gerenciar postos de coleta, postagens de blog, solicitações de suporte, informações do site, FAQ, além de funcionalidades de login e cadastro de usuários.

## 🔍 Objetivo do Projeto

O site de reciclagem de eletrônicos visa facilitar a conexão entre usuários que desejam descartar seus aparelhos eletrônicos de forma correta e empresas ou cooperativas responsáveis pela coleta e reciclagem. O sistema oferece funcionalidades como agendamento de coleta, mapa de postos de coleta, informações sobre os tipos de eletrônicos aceitos, notícias sobre reciclagem e um canal de suporte para dúvidas e sugestões.

## Tecnologias Utilizadas

*   **Node.js**
*   **Express** 
*   **MongoDB** 
*   **Mongoose** 

## Descrição das Pastas

*   **controllers**: Contém os arquivos responsáveis por receber as requisições, interagir com os models e services, e enviar as respostas para o cliente.
*   **models**: Define a estrutura dos dados (schemas) que serão armazenados no banco de dados MongoDB.
*   **routes**: Define as rotas da API, ou seja, os endpoints que o cliente pode acessar.
*   **services**: Contém a lógica de negócios da aplicação, separando-a dos controllers.
*   **middlewares**: Contém funções que são executadas antes das requisições chegarem aos controllers, como autenticação e validação.

## 💻 Variáveis de Ambiente

Crie um arquivo `.env` na raiz do projeto e defina as seguintes variáveis:

*   `MONGO_URI`: URL de conexão com o banco de dados MongoDB.
*   `PORT`: Porta em que o servidor irá rodar.
*   `(Outras variáveis necessárias)`

## ⚙️ Instalação

1.  Clone este repositório:

    ```bash
    git clone [https://github.com/usuario/repo.git](https://github.com/usuario/repo.git)
    ```

2.  Navegue até o diretório do projeto:

    ```bash
    cd backend
    ```

3.  Instale as dependências:

    ```bash
    npm install
    ```

## Executando o Servidor

1.  Inicie o servidor MongoDB.
2.  Execute o comando:

    ```bash
    node server.js
    ```

    O servidor estará rodando na porta especificada na variável de ambiente `PORT` (ou na porta 5000 por padrão).


## 👥 Contribuindo

Sinta-se à vontade para abrir issues ou pull requests para contribuir com melhorias ou correções.

## 📝 Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](./LICENSE) para mais informações..

## 📬 Contato

Caso tenha alguma dúvida ou sugestão, sinta-se à vontade para abrir uma issue ou me contatar diretamente:

- 📧 **E-mail (Senac):** ana.ppviana@senacsp.edu.br 
- 📧 **E-mail (Hotmail):** ana.pereira.viana@hotmail.com  
- 📧 **E-mail (Gmail):** paulinhapv22@gmail.com


**🌟 Se você gostou, não se esqueça de dar uma estrela no repositório! Isso nos ajuda a alcançar mais entusiastas e colaboradores.**

---
