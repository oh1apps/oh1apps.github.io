---
layout: default
---
![Telegram Pusher](assets/images/ico/tp.png)
## Telegram Pusher
***



As an alternative to Pushbullet, Telegram Pusher offers similar functionalities for free.

It consists of two pieces: an extension and a bot that you add to your chat. From there, you can quickly send yourself things such as the URL of the current tab, a photo, selected text, a link, or a note.

You can add as many accounts as you like and send things just by right-clicking!

Telegram Pusher is available for Firefox and Chromium based browsers. You can get it below:

<a href="https://chrome.google.com/webstore/detail/telegram-pusher/ebhigbmhamklhjnaleccblonlaimplin">![Chrome extension](assets/images/badges/cr.png)</a>
<a href="https://microsoftedge.microsoft.com/addons/detail/telegram-pusher/ajchnkkjjdjbdbadphbenmgiabnbjofb">![Edge extension](assets/images/badges/edge.png)</a>
<a href="https://addons.mozilla.org/pl/firefox/addon/telegram-pusher/">![Firefox extension](assets/images/badges/fox.png)</a>

### Setup
***

#### The setup of Telegram Pusher will take a few minutes, but it's necessary to create a 100% private environment where no third party can access things you send. Let's start!

### 1. Add Telegram Pusher bot

Add <a href="https://t.me/PushingRobot">@PushingRobot</a> to your Telegram Chats and activate it by sending */start* command

### 2. Get your chat ID

Send another command to @PushingRobot - */getid* to obtain your credentials. Copy or write them down, and you can safely remove @PushingRobot if you will as it won't be longer needed.

### 3. Talk to BotFather

BotFather is special bot for... creating other bots. In next steps you'll create your private bot which will act as receiver for all messages sent by Telegram Pusher extension.

#### Please note that BotFather offers extensive help and is really foolproof in guiding you by hand. More help you can also find on offical Telegram page <a href="https://core.telegram.org/bots#6-botfather">here</a>

### 4. Create your bot

**4.1** Add <a href="https://t.me/botfather">@BotFather</a> to chats and activate the same way as in step 1.

**4.2** Send @BotFather */newbot* command and after prompt give it a name.

**4.3** Now it's time to assign username to your newly created bot. Username must end in ""bot, like TelegramBot

**4.4** After succesful creation of your new bot, BotFather will prompt you with message containing tokento access HTTP API. Write that token down and don't share it with anyone!

#### Please refer to BotFather help to further customize your bot and manage its settings.

### 5. Configure Telegram Pusher extension
Open extension settings page, and fill all required fields: Username, ID and token and you're good to go!

Use right-click menu to access extension fuctionality.

### 6. Tips

If you want to connect another Telegram account to Telegram Pusher just log-in to it and repeat steps 1 and 2, then provide credentials in extension settings. There's no need to make another bot, juts add your originally created bot to chats of new account.

Username, ID and token are constant (until explicitly changed by user). After reinstall you can quickly get extension to working - just by providing written down values.

BotFather remembers all your bots, even if you delete chat with him. Just add BotFather again to get access to your bot.