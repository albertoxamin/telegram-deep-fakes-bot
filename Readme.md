# telegram-deep-fakes-bot
This bot uses the first-order-model https://github.com/AliaksandrSiarohin/first-order-model to generate video note deep fakes

## How to use it

Open the python notebook with colab by clicking this <a href="https://colab.research.google.com/github/albertoxamin/telegram-deep-fakes-bot/blob/master/deep_fake_telegram.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
And **follow the instructions on the notebook**.
> **NOTE:** due to too many requests there is no support, do **not** dm me if you can't start the bot. If you follow the instructions on Google Colab you will get the bot running. If you do not know how to use Google colab search a tutorial on youtube or online.

## Enabled users

You can change the enabled users by simply adding your Telegram ID(not username or name, but ID) to the `enabled` array.

For example:

`enabled =[12345678,12344321]`

here we have enabled two users, `12345678` and `12344321`.

If this array is empty, everyone can use your bot (for testing purposes, we decided to set it like that).

## Screenshot

![Imgur](https://i.imgur.com/gjzq5Nb.png)
