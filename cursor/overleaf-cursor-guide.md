# Overleaf + Cursor 论文写作指南

## 一、概述
在学术写作中，Overleaf是强大的在线LaTeX编辑平台，Cursor是智能的本地编辑器。将两者结合使用，可以让您的论文写作体验更加流畅和高效。

## 二、为什么选择这个组合？
1. **Overleaf优势**
   - 在线协作编辑
   - 内置LaTeX编译环境
   - 丰富的模板库
   - 实时预览

2. **Cursor优势**
   - 本地编辑更流畅
   - AI辅助写作
   - 强大的代码补全
   - 快捷的编译预览

## 三、设置步骤


### 1. 获取 Overleaf Cookie

我们需要获取Overleaf的访问凭证（Cookie）, 按 `F12` 打开浏览器的开发者工具, 获取Cookie的步骤如下：

1. 打开 Overleaf 网站并登录, 进入编辑器
2. 在开发者工具中切换到"Network"（网络）选项卡
3. 在筛选框中输入"project"
4. 找到对应请求
5. 在请求头中找到Cookie值
6. Cookie值通常以 overleaf_session2=... 或 sharelatex.sid=... 开头


注意：Cookie 是您的临时访问凭证，它包含了您的登录信息，不要泄露给他人。有效期是临时的，关闭浏览器后可能失效。

![获取 Overleaf Cookie](https://raw.githubusercontent.com/iamhyc/Overleaf-Workshop/master/docs/assets/login_with_cookie.png)

### 2. 配置 Cursor
1. 打开 Cursor 的插件市场，搜索 Overleaf Workshop 并安装. 
2. 配置Overleaf连接, 复制Cookie到插件设置.

![Cursor 配置 Overleaf 连接](https://raw.githubusercontent.com/iamhyc/Overleaf-Workshop/master/docs/assets/demo01-login.gif)


## 四、使用方法

### 1. 基本操作快捷键
- `opt+Alt+B`: 编译文档
- `opt+Alt+V`: 预览PDF
- `opt+Alt+J`: 跳转到PDF位置
- 在PDF中双击: 跳转到源代码位置

### 2. 项目管理
- 使用"Open Project Locally"在本地打开项目
- 通过LaTeX-Workshop进行编译和预览
- 更改自动同步到Overleaf

### 3. 协同工作流程
1. Overleaf创建项目
2. 使用Cookie连接本地编辑器
3. 进行本地编辑
4. 更改自动同步
5. 协作者实时查看更改

## 五、总结

Overleaf + Cursor的组合为学术写作提供了强大的工具链。通过合理配置和使用，可以显著提高论文写作的效率和体验。