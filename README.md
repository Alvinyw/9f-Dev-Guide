# Introduce

### 1. 安装 [Node.js](https://nodejs.org/en/) 和 npm (Node.js 的安装包一般会包含 npm 的安装)；
### 2. 拉取代码：

   ```javascript
   $ git clone
   ```

### 3. 安装 gitbook ：
   
   ```javascript
   $ npm install gitbook-cli -g
   ```

### 4. 创建你的书：
   
   ```javascript
   $ gitbook init
   ```
   
   init 成功之后会看到文件： `README.md` 和 `SUMMARY.md`。
### 5. 打开并编辑书目录文件 SUMMARY.md ：
    
   ```javascript
    * [Introduction](README.md)
	* [一：设计规范](designGuide/index.md)
    * [1. 主题色](designGuide/themeColor.md)
    * [2. 文字](designGuide/fontText.md)
    * [3. 按钮](designGuide/buttons.md)
    * [4. 小结](designGuide/summary.md)
   ```
   保存之后再执行下面的命令：
   
   ```javascript
   $ gitbook init
   ```
   你会发现 gitbook 为你建好了 SUMMARY 中定义的文件夹，且把在 SUMMARY.md 列出来的 md 文件都建好放在了相应文件夹里。
   
   接下来我们只要对应的打开 md 文件填写我们的内容就好。
### 6. 预览一下书的样子：
   
   ```javascript
   $ gitbook serve
   ```
   执行成功之后会看到一个网址：
   
   ```javascript
   http://localhost:4000
   ```
   拷贝该网址在浏览器打开就可以预览书的样式了。

### 7. 将 md 文件 build 成 html 文件：
   
   ```javascript
   $ gitbook build
   ```
   执行成功之后你会看到多了一个 **_book** 文件夹，里面就是转换好的 html 文件。

## 创建的 book
[GitBook](https://alvinyw.github.io/Blog/9fGuide/index.html)
   
   