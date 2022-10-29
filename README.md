# blog
## 运行条件：
- 需要 hexo

- 安装好必要的库：`npm install`

- 为了hexo-renderer-markdown-it能像hexo-renderer-marked一样对图片路径自动添加，需要使用最新版本：（这里也奇怪，我`npm i`得到的node_modules里不是最新版本，虽然版本号一致
    ```
    git clone git@github.com:hexojs/hexo-renderer-markdown-it.git node_modules/hexo-renderer-markdown-it
    ```
- 安装好主题 Next：`git clone https://github.com/theme-next/hexo-theme-next themes/next`

## 运行：
```
hexo g
hexo s
```
