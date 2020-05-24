修改自开源项目：https://github.com/stridercheng/chatui



**完成Androidx迁移**

用Android Studio打开项目时如果报"Unsupported Modules Detected ..."错误，直接将根目录下.idea目录删除，重新打开项目即可。

迁移过程中参考了文档：

[Androidx迁移——弃用support库指南](https://www.jianshu.com/p/1113c81ad57f)
[android.support升级到androidx踩坑记录](https://www.jianshu.com/p/b0800f590e6e)

## 原有功能

原始项目文档可参见：

https://github.com/stridercheng/chatui/blob/master/README.md

https://www.jianshu.com/p/4fc79094cc85

+ 替换部分图片资源
+ 用源生RecyclerView替换了EasyRecyclerView,比较相信官方。
+ 修复拍照在7.0系统中无法获取权限问题。
+ 增加文件分享，点击文件打开。
+ 增加联系人信息分享。
+ 长按消息弹出上下文菜单
+ 注册app到系统分享面板，能够处理分享自外部的URL、图片、文档。

## 截图
![image](https://github.com/stridercheng/chatui/raw/master/images/preview.png)

## 问题
代码结构待优化
