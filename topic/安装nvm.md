# 安装 nvm

## 开始

nvm 全称是 node version manager，中文意思是 node 版本管理。

在使用 node 时，不推荐直接安装 node，先安装 nvm，由 nvm 来安装 node。有了 nvm，我们可以安装多个 node 版本，然后自由地在

如果下面的 nvm 步骤实在装不了。那你就去[nodejs 官网](https://nodejs.org/zh-cn/)直接安装 node 吧。选择最新版本 v8.3.0。

## 安装 NVM

#### Win 安装 NVM

[Windows 下安装 nvm、npm 及 node.js](https://segmentfault.com/a/1190000010596717)，这篇文档是何伟同学总结整理，如遇到问题可以再微信群里问他。

[网上另一篇总结文档](https://segmentfault.com/a/1190000007612011)

注意：如果 nvm 实在装不了。那你就去[nodejs 官网](https://nodejs.org/zh-cn/)直接安装 node 吧。选择最新版本(好像是 8.4 了吧)。

#### MAC 安装 NVM

注意：如果 nvm 实在装不了。那你就去[nodejs 官网](https://nodejs.org/zh-cn/)直接安装 node 吧。选择最新版本(好像是 8.4 了吧)。

打开终端，输入

```bash
> curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
```

![https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/nvm4.png](https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/nvm4.png)

和下图一样结果，说明你已经安装成功。

![https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/nvm4.png](https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/nvm5.png)

#### 验证安装

关掉终端，重新再打开终端。输入

```bash
> nvm --version
```

![https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/nvm1.png](https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/nvm1.png)

【注意】

如果你验证安装还是提示`nvm: command not found`，请按照下面的步骤来操作。

```bash
> touch ~/.bash_profile
> touch ~/.bashrc
> curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash
```

执行成功后，关掉终端开启终端，然后继续往下走。

#### 安装 node

通过 nvm 安装 node 的 v8.0.0 版本

```bash
> nvm install v8.0.0
```

![https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/nvm2.png](https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/nvm2.png)

#### 执行 node

在终端，输入 node

```bash
> node
```

此时会直接进入到 node 的终端编辑模式。
在 node 的终端编辑模式下，输入一行代码

```javascript
> console.log('hello, js')
```

![https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/nvm3.png](https://raw.githubusercontent.com/wiki/xugy0926/getting-started-with-javascript/nvm3.png)

你在 node 环境下运行的第一行代码就大功告成了。

#### 退出 node 编辑模式

快捷键：`ctl + c` 按两次
