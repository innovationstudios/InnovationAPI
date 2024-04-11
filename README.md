WhatsApp Media Sender
Este é um projeto simples para enviar mídias para o WhatsApp usando o Whaticket e armazenar as mídias no servidor local.

Instalação
Clone este repositório:

bash
Copy code
git clone https://github.com/seu-usuario/nome-do-repositorio.git
Instale as dependências do Node.js:

bash
Copy code
npm install
Configure as variáveis de ambiente:

Renomeie o arquivo .env.example para .env e preencha as variáveis de ambiente necessárias.

Uso
Inicie o servidor:

bash
Copy code
npm start
Envie uma solicitação POST para o endpoint /send-media com a mídia a ser enviada.

Endpoints
POST /send-media
Envia uma mídia para o WhatsApp e salva no servidor local.

Parâmetros
from: (String) Número do remetente.
caption: (String) Legenda da mídia.
image: (File) Arquivo de imagem a ser enviado.
Exemplo de Requisição
bash
Copy code
curl -X POST -F "from=SEU_NUMERO" -F "caption=LEGENDA_DA_IMAGEM" -F "image=@caminho/para/imagem.jpg" http://localhost:3000/send-media
Contribuindo
Sinta-se à vontade para contribuir com melhorias para este projeto. Abra uma issue para discutir as mudanças que deseja fazer ou envie um pull request diretamente.

Licença
Este projeto é licenciado sob a MIT License.
