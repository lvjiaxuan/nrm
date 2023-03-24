截至 2023年3月24日，从 npm 安装的 nrm 存在一些 issues，其实 GitHub [源码](https://github.com/Pana/nrm)上有的已经解决，但是没有发布。一年多没更新了，不知道是不是弃坑了。

所以我 fork 下来，帮它发布一下😀，没有改动任何业务代码，只是改了 package.json 相关 publish 信息。

安装使用：由于使用的命令还是 nrm，所以要先卸载已有的 nrm
```sh
npm un nrm -g
npm i nrm-lvj -g
nrm -h
```
