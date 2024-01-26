使用本项目存在封号风险，已停止维护，推荐使用 [在线工具](https://weread.deno.dev/) 进行转换。

# xrw 夏如雯

与[魏如雪](https://github.com/ckisok/wrx)是好朋友

## 安装

与她的好朋友的安装方式相同，参考[安装说明](https://github.com/ckisok/wrx#%E5%AE%89%E8%A3%85)

## 使用

> ## 警告
> 在生成 epub 格式时需要下载图片，图片请求会自动携带 cookie 与浏览器指纹信息，因此为了更好的隐藏自己，请使用一个完全不一样的浏览器(与使用 web 版微信读书不一样)运行该插件。
>
> 特别注意：经测试，同一浏览器的无痕模式仍然会携带 cookie 与相关信息。

打开插件弹框，如下图：

![image](https://github.com/ckisok/xrw/assets/143160104/fbe052d5-3653-4164-939b-d3a49c9a8fed)

将 **魏如雪** 导出的数据文件拖到指定位置，然后选择要生成的格式，点击 **生成** 按钮。

> 对于图片比较多的书籍，如果进度长时间不更新，请耐心等待，并不是真的卡住了。

### 关于图片打包时的数字的说明

在打包图片的时候会出现2个数字，如下图：

![image](https://github.com/ckisok/xrw/assets/143160104/5334b448-bbe9-4b2b-8d29-476534716d86)

第一个数字表示成功打包的图片数量，第二个数字表示图片下载失败的数量，正常情况下第二个数字一直为0，如果第二个数字不为0，则表示某一张图片下载失败了，最终生成的 epub 文件中会使用下面这样的占位图片替代：

![image](https://github.com/ckisok/xrw/assets/143160104/b9a0dc15-e241-4f99-b537-4595fc78273a)
