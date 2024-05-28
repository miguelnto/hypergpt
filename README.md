# HyperGPT

**Documentação de referência para o bot hyperGPT, desenvolvido com a tecnologia do ChatGPT.**

Esse BOT foi criado com foco em uso da inteligência artificial para criar interatividade e diversão para seu servidor!

As seguintes funcionialidades estão disponíveis:

- 🤖 - *Gerar respostas em texto com IA.*
- 🖼️ - *Gerar imagens com IA.*
- 🧠 - *Limitar canais onde usar o BOT com o "modo restrito".*

## Configuração inicial e como usar

Requisitos:

- Uma *key* para ativar o bot.
- O *link* de convite para o bot.

Se você tem todos esses requisitos, por favor siga os seguintes passos **na ordem:**

1. Convide o BOT para seu servidor usando o link de convite.
2. Use o comando `/activate` junto com sua key para ativar o BOT. Se você digitou corretamente, o BOT alertará que a key foi ativada com sucesso.
3. Em caso de dúvidas, por favor leia mais informações sobre as keys na seção [abaixo](#keys).
4. Use o comando `/expires` para checar quando sua key vai expirar. Esse comando pode ser usado a qualquer momento para te deixar informado.
5. Pronto! O BOT já está configurado e pode ser usado. Confira todos os comandos disponíveis na seção [comandos](#comandos).

## Keys

Keys são usadas para a ativação da aplicação. Confira a seguir informações essenciais sobre as keys:

- Você deve usar apenas uma key e **uma vez** por mês. Se você tem 2 ou mais keys, aguarde até 1 dia antes da data de expiração da key para usar uma nova. Se você usar uma key e em seguida usar outra, isso não extenderá o prazo de expiração.
- Uma key funciona só uma vez. Se você tentar usar uma key usada, você vai receber uma mensagem alertando que a key não pôde ser usada para ativar o BOT.
- Nenhum comando ou interação com o bot será possível se o BOT não estiver ativado com a key.

### Comandos com as keys

---

#### ⚙️ /activate - `key` 
Ativa o bot com uma key.

- `key` - A key que deve ser usada o bot seja ativado.

> Exemplo:

`/activate "7Z8V-LIFO-2W5T"`

---

#### ⚙️ /expires 
Checa a data de expiração da key.

Esse comando não tem parâmetros.

---

## Observações

🚩 **ATENÇÃO!**

Nesta documentação, os comandos são referenciados da seguinte forma:

#### ⚙️ **/comando** - `parâmetro_1`, `parâmetro_2`, ...
Descrição do comando.

- `parâmetro_1` - Significado do parâmetro...
- `parâmetro_2` - Significado do outro parâmetro...

> Exemplo:

Um exemplo de como usar o comando.

`/comando "parametro_1" "parametro_2"`

🚩 **ATENÇÃO!**

Existe um "modo restrito" no BOT, que permite que você restrinja os canais em que o bot pode ser usado. Por exemplo, você pode criar um canal chamado `#gpt-comandos`, e então adicionar esse canal para a lista restrita com o comando `/addchannel`, e depois acionar ou desacionar o modo restrito com o comando `/restrict`.

## Comandos principais

#### ⚙️ /chat - `prompt` 
Converse com a IA.

- `prompt` - Pode ser qualquer mensagem de texto, incluindo perguntas ou afirmações.

> Exemplo:

Uma pergunta aleatória de matemática.

`/chat "quanto é 720*8?"`

---

#### ⚙️ /imagine - `model`, `prompt`
Gera uma imagem baseada no prompt usando IA.

- `model` - Modelo para usar. Pode ser *prodia* ou *pollinations*.
- `prompt` - Prompt que será usado para gerar a imagem.

> Exemplo:

Gerando uma imagem de uma elfa de cabelo verde na cidade. 

*Detalhe: o prompt não precisa estar em inglês, mas prompts em inglês geram imagens mais detalhadas.*

`/imagine "prodia" "green haired elf in the city"`

![Elfa de cabelo verde na cidade.](elf.png)

---

## Contato

**Esse BOT foi desenvolvido com carinho por Miguel (@miguelnto), programador full stack e designer.**

Todos os links de contato estão abaixo.

- Email: miguelup01@outlook.com
- Servidor: [HyperStore](https://discord.gg/M7FURN5R88)
- Discord: miguelnto
