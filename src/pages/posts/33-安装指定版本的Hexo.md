---
date: 2023-07-19
---
最近闲来无事又折腾了几天博客主题，原因是搭建在cloudstudio的服务器突然打不开了，折腾好久联系上技术以后说是”历史镜像的预热问题“咱外行人也不懂，处理完以后说我这个空间是2021年创建的，毕竟老，新版本的Bug会少点，我就尝试从新创建一个。遇到了一下几个问题：

1. 之前按照的HEXO是4.21版本，现在最新版已经到6.2+，安装完以后发现主题不兼容，一堆报错。
2. **Node.js**现在最低版本也是建议18.x，而我之前安的是10.0的，想直接用[vercel](https://vercel.com/)部署的想法也pass掉了。

没办法，只能尝试按照旧版本的hexo了，在折腾好几天以后，总算安装成功。

### 操作方法如下

1. 安装Git Linux (Ubuntu, Debian)：
`sudo apt-get install git-core`
2. 安装旧版本Node.js
`curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs`
3. 安装指定版本hexo：
`npm i hexo@4.2.1`

不出意外的话就成功了，虽然会有一些报错，但不影响。

### 展示

![image-20230719104942156](https://img.010316.xyz//usr/hugo/2022/image-20230719104942156.png)

