
## Dont use this in Your main account, risk of account suspension

## Prerequisite
Fork this Repo,
Setup secrets in settings --> Secrets


| Secret Name       | Description                                                               |
| ----------------- | ------------------------------------------------------------------------- |
| `GH_TOKEN`        | Your GitHub personal access token with `repo` permissions                 |
| `MIRROR_REPOSLUG` | The repository slug (e.g. `SilentDemonSD/WZML-X`) of your mirror bot      |
| `BOT_TOKEN`       | The Telegram bot token from [@BotFather](https://t.me/BotFather)          |
| `OWNER_ID`        | Your Telegram user ID (usually from @userinfobot)                         |
| `TELEGRAM_API`    | Telegram API ID from [https://my.telegram.org](https://my.telegram.org)   |
| `TELEGRAM_HASH`   | Telegram API hash from [https://my.telegram.org](https://my.telegram.org) |
| `DATABASE_URL`    | MongoDB connection string (⚠️ username and password must be URL-encoded)  |


  
After that done, it should look like this
![image](https://user-images.githubusercontent.com/77688759/120898707-a2224800-c649-11eb-8b5c-4f184736e717.png)


Then edit .github/workflows/mirror-bot.yml


Change `GitHubMail`, `GitHubName` and `Branch` environment variable as your own

![image](https://user-images.githubusercontent.com/77688759/120898733-c54cf780-c649-11eb-9b80-058d4500df29.png)

And That's it.
