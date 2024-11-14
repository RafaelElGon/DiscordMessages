# Discord Channel Message Scraping
>Esta é uma ferramenta para recuperar o histórico de mensagens de um canal específico no Discord, utilizando a API do mesmo. O objetivo é a preservação do conteúdo de mensagens dos canais de um servidor. 

## Atualmente, o projeto permite:

- Conectar-se ao canal de um servidor do Discord, utilizando o token de um bot para autenticação e o ID de um canal do servidor;
- Coletar mensagens em lotes e salvá-las em um arquivo .json;

## Objetivos futuros:

- ~~Permitir que o conteúdo das mensagens seja recuperado. Por enquanto, somente metadados sobre as mensagens estão disponíveis.~~
- ~~Filtrar as mensagens por ID do usuário.~~

- Implementar uma interface via DM de Discord, para que mais pessoas possam usar de forma mais fácil.
  - Junto dessa possível implementação, entra também adicionar suporte pra enviar o arquivo .json via DM de Discord pra quem requisitou as mensagens.
- Implementar a possibilidade de recuperar todas mensagens de um canal, sem um filtro de usuário.
  - Talvez adicionar métodos de filtragem diferentes. 
 
## Créditos:

- Boa parte da estrutura e das escolhas de como fazer esse projeto foram tiradas [deste post no stackoverflow](https://stackoverflow.com/questions/67793922/data-scraping-on-discord-using-python) 


# Discord Channel Message Scraping
>This is a tool to retrieve the message history from a specific discord server channel, using Discord's API. The goal of this project is preservation of message contents.

## Currently, the tool allows for:

- Connecting to a Discord text channel, using a bot token for auth, and an ID of a server channel;
- Collect messages in batches and saving them in a .json file;

## Futre goals:

- ~~Retrieve the content of messages. As of now, only metadata about the messages are retrieved.~~
- ~~Filter message collection by user ID.~~

- Implementing an interface to use the bot via text messages, so that more people can use it more easily.
  - With this, also comes creating DM support so that the .json file can get sent via Discord DM to the user that requested it.
- Implement an option to collect all messages from a channel, with no user filtering.
  - Maybe add different filtering methods.
 
## Credits:

- Most of the structure and choices of how to make this project came from [this post from stackoverflow](https://stackoverflow.com/questions/67793922/data-scraping-on-discord-using-python)
