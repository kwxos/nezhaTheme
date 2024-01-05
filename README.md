### 用于F大的nezha-agent，docker镜像美化

打包amzayo大佬和kshipeng大佬美化的哪吒主题文件

kshipengTheme.tar.gz：https://github.com/kshipeng/nezhaThemeCustom

amzayoTheme.tar.gz：https://blog.amzayo.com/index.php/archives/28

### ssh到容器，然后运行下面脚本
#### docker主题替换脚本

kshipeng大佬-->[demo](https://tz.euser.cf/)

```
wget -N https://github.com/kwxos/nezhaTheme/releases/download/nezhaTheme-page/kshipengTheme.tar.gz && tar -xzvf kshipengTheme.tar.gz && rm -rf kshipengTheme.tar.gz && ./backup.sh
```

amzayo大佬-->[demo](https://tz.amzayo.top/)

```
wget -N https://github.com/kwxos/nezhaTheme/releases/download/nezhaTheme-page/amzayoTheme.tar.gz && tar -xzvf amzayoTheme.tar.gz && rm -rf amzayoTheme.tar.gz && ./backup.sh
```
