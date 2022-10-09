
## Dont use this in Your main account, risk of account suspension

## Prerequisite
Fork this Repo,
Setup secrets in settings --> Secrets


`GH_TOKEN` :- Your github personal access token, from https://github.com/settings/tokens

`MIRROR_REPOSLUG` :- Your Secret Repository, as in `<username>/<reponame>` for eg `ghost/mirror-bot`

  
After that done, it should look like this
![image](https://user-images.githubusercontent.com/77688759/120898707-a2224800-c649-11eb-8b5c-4f184736e717.png)


Then edit .github/workflows/mirror-bot.yml


Change `GitHubMail`, `GitHubName` and `Branch` environment variable as your own

![image](https://user-images.githubusercontent.com/77688759/120898733-c54cf780-c649-11eb-9b80-058d4500df29.png)

And That's it.
