# angular2-webpack

### npm 安装问题

npm install，因为要去github.com上下载二进制源码，众所周知的原因，国内的网络上github.com速度太不稳定了，所以安装很慢。

这里推荐一种极速安装的方法，当然还是使用万能的淘宝镜像源。

打开~/.npmrc（windows用户打开 c:\Users\当前用户名\.npmrc）增加一行(如果当前用户下面没有.npmrc文件，可以把项目里面的.npmrc文件拷贝进去)

>     SASS_BINARY_SITE=https://npm.taobao.org/mirrors/node-sass/

npm install 之后就可以了。
