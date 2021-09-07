<h1 align="center"><a href="https://github.com/lete114/AWStats-Theme-WebStack" target="_blank">AWStats-Theme-WebStack</a></h1>
<p align="center">一个静态网址导航网站，基于 <code>AWStats</code> 静态生成器生成的静态导航网站主题</p>

<p align="center">
    <a href="https://github.com/lete114/AWStats-Theme-WebStack/releases/"><img src="https://img.shields.io/github/package-json/v/lete114/AWStats-Theme-WebStack/master?color=%23e58a8a&label=master" alt="master"></a>
    <a href="https://github.com/lete114/AWStats-Theme-WebStack/blob/master/LICENSE"><img src="https://img.shields.io/github/license/lete114/AWStats-Theme-WebStack?color=FF5531" alt="MIT License"></a>
</p>

## Quick Start

```bash
npm install awstats-cli -g ## 安装cli

mkdir AWStats-WebStack ## 新建文件夹

cd AWStats-WebStack ## 进入新建的文件及

awstats init ## 初始化awstats，默认含AWStats-Theme-HomePage

git clone git@github.com:lete114/AWStats-Theme-WebStack.git themes/WebStack

```

修改根目录的`config.yml`的`theme`属于为主题名:`theme: WebStack`

> `config.WebStack.yml`优先级高于`themes/WebStack/config.yml`

你可以使用`themes/WebStack/config.yml`进行配置也可以将它拷贝到根目录`AWStats-WebStack/config.yml`将其重命名为`config.WebStack.yml`，其中`WebStack`要保持和`themes/`下的文件名相同(包括大小写)

> 更多关于 AWStats 的内容请前往 [https://github.com/lete114/AWStats](https://github.com/lete114/AWStats)

## License

[MIT](LICENSE)
