# Inquire

[Inquire](https://inquire.run) is a generalized chatbot ready to handle anything you throw at it. Right now you can interface with [Inquire](https://inquire.run) through Telegram

[Inquire](https://inquire.run) takes advantage of prompt engineering large langauge models like `davinci-3` from [OpenAI](https://beta.openai.com/docs/models/gpt-3) to create personas for users to interact with. For example you can chat with a `math-teacher`, `philosopher`, or `dietitian`.

## Using Telegram
[Chat with Inquire](https://t.me/inquireai_bot)

### Commands 
Below are a set of commands and explaination of them

#### Start
`/start  <?persona>` initalizes your session with the bot with a general chat persona. Alternatively you can start the bot with a specific persona using `/start <persona>`. Starting the bot with a specific persona can also be used in deeplinks with the parameter being the persona, for example `t.me/inquireai_bot?start=<persona>`

#### Help
`/help` prints information about the bot and how to use it. An example output could be
```
Inquire is a converstational chatbot that can take the form of just about any persona.

To get started start typing @inquireai_bot followed by the persona you want to chat with (e.g. @inquireai_bot math-teacher). Any message after will be answered!

If you are in a group chat you will need to preface your inquiry with /chat

Learn more about Inquire at https://inquire.run
```

#### Chat
`/chat <query>` a direct way of chatting with the bot. If you are in a private chat (just you and the bot) it will respond to any chat you send. If you are in a group (to not disturb the rest of the chat) you will need to directly command the bot to respond to you with `/chat <your query>`.

#### Random
`/random` will display a clickable inline list of ten random personas that you can interact with. Simply click on one to start chatting.

#### Persona
`/persona` will output the current persona that you are chatting with.

#### Set
`/set <persona>` will switch the current persona that are you are chatting with. Alternatively if you know the exact slug of the persona you want to chat with you can use `/<persona-slug` for example `/math-teacher`.

#### All
`/all` will list out every persona available on the Inquire platform

### Group Chats 
If there are multiple bots in the chat you may have to query it with `@inquireai_bot/<command>` (yes no space between the bot and the command).
