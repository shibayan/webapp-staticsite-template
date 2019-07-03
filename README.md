# webapp-staticsite-template

Azure Web App Template for Static Site Generator (e.g VuePress, Hugo)

## Getting Started

### 1. Deploy to Azure

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3a%2f%2fraw.githubusercontent.com%2fshibayan%2fwebapp-staticsite-template%2fmaster%2ftemplate%2fazuredeploy.json" target="_blank">
  <img src="https://azuredeploy.net/deploybutton.png" />
</a>

### 2. Choice `site generator`

![image](https://user-images.githubusercontent.com/1356444/60607026-621c1000-9df7-11e9-9875-46c0a29943d8.png)

### 3. Setup `build command` and `publish directory`

#### Hexo

Build Command | Publish Directory
---|---|
hexo generate | public

![image](https://user-images.githubusercontent.com/1356444/60606793-f174f380-9df6-11e9-89f9-267d92d74ec8.png)

#### Hugo

Build Command | Publish Directory
---|---|
hugo | public

![image](https://user-images.githubusercontent.com/1356444/60607237-de165800-9df7-11e9-8c21-c49d4a732ab5.png)

#### Nuxt

Build Command | Publish Directory
---|---|
npm run generate | dist

![image](https://user-images.githubusercontent.com/1356444/60607330-00a87100-9df8-11e9-95c1-9f88c1ac8a9d.png)

#### VuePress

Build Command | Publish Directory
---|---|
npm run build | .vuepress/dist

![image](https://user-images.githubusercontent.com/1356444/60607363-174ec800-9df8-11e9-93aa-4a5cb00015e5.png)

### 4. Deploy using git

- Use continuous deployment (e.g GitHub, Azure Repos)
  - https://docs.microsoft.com/en-us/azure/app-service/deploy-continuous-deployment
- Use local git
  - https://docs.microsoft.com/en-us/azure/app-service/deploy-local-git

### 5. Enjoy :smile:

## License

This project is licensed under the [MIT License](https://github.com/shibayan/webapp-staticsite-template/blob/master/LICENSE)
