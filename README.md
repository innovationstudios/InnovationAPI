# 🚀 InnovationAPI - Whatsapp Business Oficial

Este é um projeto API utilizando a lib oficial do WhatsApp Business V18.0, para envio de midia, template e mensagem definidas manualmente!

## Instalação

1. **Clone este repositório:**

    ```bash
    git clone https://github.com/innovationstudios/InnovationAPI.git/
    ```

2. **Instale as dependências do Node.js:**

    ```bash
    npm install
    ```

3. **Configure as variáveis de ambiente:**

    Renomeie o arquivo `.env.example` para `.env` e preencha as variáveis de ambiente necessárias.

## Uso

1. **Inicie o servidor:**

    ```bash
    npm start

    npx nodemon send.js
    ```

2. **Envie uma solicitação POST para o endpoint `/send-media` com a mídia a ser enviada.**

## Endpoints

### POST /send-media

Envia uma mídia para o WhatsApp e salva no servidor local.

#### Parâmetros

- `from`: (String) Número do remetente.
- `caption`: (String) Legenda da mídia.
- `image`: (File) Arquivo de imagem a ser enviado.

#### Exemplo de Requisição

```bash
curl -X POST -F "from=SEU_NUMERO" -F "caption=LEGENDA_DA_IMAGEM" -F "image=@caminho/para/imagem.jpg" http://localhost:3000/send-media

### Contribuição

**Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue para relatar problemas ou propor melhorias.
**Segue meu pix: victorgd199@hotmail.com Qualquer valor é bem vindo!

### Licença

**Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para detalhes.
