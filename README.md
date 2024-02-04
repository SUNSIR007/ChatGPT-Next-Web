## 原作者
https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web

## 个性化配置
###  1.更改默认设置
app/store/config.ts中进行修改，可对比这设置进行修改

### 2.更改主题色彩
app/styles/globals.scss中进行更改,--second是 sidebar 的颜色

### 3.发送按钮主题
chat.tsx `<IconButton>`（1300 行）

### 4.输入框提示词
cn.ts `Input: (submitKey: string)`(69行)

### 5.配置环境变量
BASE_URL：你的第三方 api 地址
OPENAI_API_KEY：你的 api key
CODE：密码

## 部署
先将本仓库fork至你的仓库，然后通过vercel进行import，注意添加环境变量，详情查看docs里的文档