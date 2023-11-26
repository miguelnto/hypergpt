# hyperGPT

Documentação de referência para o bot hyperGPT, desenvolvido com a tecnologia do ChatGPT.

## Configuração inicial e como usar

Requisitos:

- Uma *key* para ativar o bot.
- O link de convite para o bot.

Se você tem todos esses requisitos, por favor siga os seguintes passos **na ordem:**

- Convide o BOT para seu servidor.
- Use o comando `/activate` com a key. Se você digitou corretamente, o bot alertará que a key foi ativada com sucesso.
- POR FAVOR LEIA MAIS INFORMAÇÕES SOBRE AS KEYS [ABAIXO](#keys)
- Use o comando `/expires` para checar quando sua key vai expirar. Esse comando pode ser usado no futuro quantas vezes você quiser.
- O BOT já está configurado e pode ser usado. Use o comando `/help` para conferir todos os comandos disponíveis ou leia os comandos [abaixo](#comandos).

## Keys

Keys são usadas para a ativação da aplicação. Confira a seguir informaçãoes essenciais sobre as keys:

- Você deve usar apenas uma key e **uma vez** por mês. Se você tem 2 ou mais keys, aguarde até 1 ou 2 dias antes da data de expiração da key para usar uma nova. Se você usar uma key e em seguida usar outra, isso não extenderá o prazo de expiração.
- Uma key funciona só uma vez. Se você tentar usar uma key usada, você vai receber uma mensagem de erro.
- O horário da expiração da key é de acordo com o horário de brasília. Se sua key expira em `22/12/2031`, e são `00:01` do dia `22/12/2031` no horário de brasília, sua key já expirou.
- Nenhum comando ou interação com o bot será possível se o seu servidor não estiver ativado com a key.

## Comandos

Esse BOT foi criado com foco em uso da inteligência artificial, e comandos para gerar imagens e respostas estão disponíveis. Além disso, existe um "modo restrito" no BOT, que permite que você restrinja os canais em que o bot pode ser usado. Por exemplo, você pode criar um canal chamado `#gpt-comandos`, e então adicionar esse canal para a lista restrita com o comando `/addchannel`, e depois acionar o modo restrito com o comando `/restrict`.

#### `/chat` - Converse com a IA.

- **prompt** - Pode ser qualquer mensagem de texto, incluindo perguntas ou afirmações.

#### `/imagine` - Gera uma imagem baseada no prompt.

- **model** - Modelo para usar. Pode ser `prodia` ou `pollinations`.
- **prompt** - Prompt que será usado para gerar a imagem.

#### `/addchannel` - Adiciona um canal pelo ID para o bot responder no modo restrito.

- **canal** - ID do canal. Caso não seja passado, o canal onde este comando foi usado será aplicado.

#### `/deletechannel` - Delete um canal pelo ID da lista para o bot responder no modo restrito.

- **canal** - ID do canal. Caso não seja passado, o canal onde este comando foi usado será aplicado.

#### `/listchannels` - Lista todos os canais adicionados ao modo restrito.

#### `/restrict` - Ativa ou desativa o modo restrito do bot.

## Contato

- Email: miguelup01@outlook.com
- Servidor: [HyperStore](https://discord.gg/M7FURN5R88)
