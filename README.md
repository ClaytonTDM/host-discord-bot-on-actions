# How to host a Node.JS Discord bot on GitHub Actions
1. Fork this repository
2. Add your bots code
3. Add your bot token to an enviroment variable (you have to do this in order to avoid sharing your bot token, you can set enviroment variables in `Repository Settings > Environments > Environment Variables`)
4. If done correctly, the action should get indefinitely stuck on `Run npm start`
5. Done! Your Discord bot should be online.
