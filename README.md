<div align="center">
<img src="./src/assets/vite.svg" style="width:60px;height:60px" alt="icon"/>
<img src="./src/assets/openai.svg" style="width:64px;height:64px;margin:0 32px" alt="icon"/>
<img src="./src/assets/react.svg" style="width:60px;height:60px" alt="icon"/>

<h1 align="center">ChatGPT Web</h1>


可部署商业化的 ChatGpt 网页应用。

[Proxy Demo]() / [Business Demo](https://chatgpt79.vercel.app/) / [Issues](https://github.com/79E/ChatGPT-Web/issues) / [Buy Me a Coffee](https://www.buymeacoffee.com/beggar)

[代理（proxy）演示](https://chatgpt79.vercel.app/) / [商业（business）演示](https://aizj.top/) / [反馈](https://github.com/79E/ChatGPT-Web/issues) 

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/79E/ChatGpt-Web)

![cover](https://cdn.jsdelivr.net/gh/duogongneng/testuitc/1682393823691cover.png)


</div>


## 🤖 主要功能

- 用户系统可对使用进行相关限制
- 精心设计的 UI，响应式设计。
- 极快的首屏加载速度（~100kb）
- 海量的内置 prompt 列表，来自[中文](https://github.com/PlexPt/awesome-chatgpt-prompts-zh)和[英文](https://github.com/f/awesome-chatgpt-prompts)
- 一键导出聊天记录，完整的 Markdown 支持
## 🎮 开始使用
**Node 环境**

`node` 需要 `^16 || ^18 || ^19` 版本（node >= 16），可以使用 nvm 管理本地多个 node 版本。

```
# 查看 node 版本
node -v

# 查看 npm 版本
npm -v

# 查看 yarn 版本
yarn -v

```

**1.先 `Fork` 本项目，然后克隆到本地。**
```
git clone https://github.com/79E/ChatGpt-Web.git
```

**2.安装依赖**
```
yarn install
```

**3.运行**
```
yarn dev
```

**4.打包**
```
yarn build
```


## ⛺️ 环境变量

> 本项目大多数配置项都通过环境变量来设置。

#### `VITE_APP_REQUEST_HOST` 

请求服务端的`Host`地址。

#### `VITE_APP_TITLE` 

Chat Web 标题名称。

#### `VITE_APP_LOGO` 

Chat Web Logo。

#### `VITE_APP_MODE` 

应用模式可选：商业模式（business）代理模式（proxy）混合模式（mix）

## 🚧 开发

> 强烈不建议在本地进行开发或者部署，由于一些技术原因，很难在本地配置好 OpenAI API 代理，除非你能保证可以直连 OpenAI 服务器。

#### 本地开发

1. 安装 nodejs 和 yarn，具体细节请询问 ChatGPT；
2. 执行 `yarn install && yarn dev` 即可。

## 🎯 部署
> 直接将打包好的 `dist` 目录上传到服务器即可。WEB项目暂时不直接访问 OpenAI API 所有不要求服务器地址。

### Vercel
如果你将其托管在自己的 Vercel 服务器上，可点击 deploy 按钮来开始你的部署！

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/79E/ChatGpt-Web)

<details>
 <summary>设置 Vercel 的指导</summary>

1. 前往 [vercel.com](https://vercel.com/)
1. 点击 `Log in`
   ![](https://files.catbox.moe/tct1wg.png)
1. 点击 `Continue with GitHub` 通过 GitHub 进行登录
   ![](https://files.catbox.moe/btd78j.jpeg)
1. 登录 GitHub 并允许访问所有存储库（如果系统这样提示）
1. Fork 这个仓库
1. 返回到你的 [Vercel dashboard](https://vercel.com/dashboard)
1. 选择 `Import Project`
   ![](https://files.catbox.moe/qckos0.png)
1. 选择 `Import Git Repository`
   ![](https://files.catbox.moe/pqub9q.png)
1. 选择 root 并将所有内容保持不变，并且只需添加名为 PAT_1 的环境变量（如图所示），其中将包含一个个人访问令牌（PAT），你可以在[这里](https://github.com/settings/tokens/new)轻松创建（保留默认，并且只需要命名下，名字随便）
   ![](https://files.catbox.moe/0ez4g7.png)
1. 点击 deploy，这就完成了，查看你的域名就可使用 API 了！

</details>



## 🧘 贡献者

[见项目贡献者列表](https://github.com/79E/ChatGPT-Web/graphs/contributors)

## 📋 开源协议

[![License MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://github.com/79E/ChatGpt-Web/blob/master/license)
