# hexo-theme-Anatole-Core


## 关于主题
基于ben02的Anatole主题进行修改，原项目地址：[hexo-theme-Anatole](https://github.com/Ben02/hexo-theme-Anatole)。

简约、美观、实用

暂时只支持简体中文，其他语言需要修改部分代码。

觉得不错的话麻烦`star`一下 -_-


## 外观
Demo : https://www.jixian.io

![jixian.io](https://qn.jixian.io/demo.jpg)


## 使用

### 安装
``` 
git clone https://github.com/mrcore/hexo-theme-Anatole-Core.git themes/anatole-core

或者直接下载主题zip包解压至主题目录下，重命名为anatole-core

# 安装hexo-renderer-pug

npm install hexo-renderer-pug --save

```

### 配置
修改hexo根目录下的 `_config.yml` ： `theme: anatole-core`

其他需要配置的地方请看 `themes/anatole-core/_comfig.yml`

### 更新
``` 
cd themes/anatole-core
git pull
```

## 许可证
MIT License

## 其他
我非前端工作者，也不怎么会nodejs，都是现学现改，实现就行，不追求代码质量 -_-

自己动手 丰衣足食

<br>

## 近期更新（2020.05.28）

### 2020.05.28 第五次更新：
删掉一些没用的文件

<br>

### 2020.05.06 第四次更新：
修复description显示的bug

可以直接在主题设置里设置copyright等信息

<br>

### 2020.04.23 第三次更新：
增加基于Valine的网页计数，放在了文章底部

<br>

### 2020.04.17 第二次更新：
优化了大量CSS样式

更新了图标库到最新版本

增加了标签页和标签云图

留言和关于页面不显示时间

删掉了一些不用的功能代码

本实现了不蒜子网页计数，但不蒜子服务器超时严重，放弃

<br>

### 2018.11.26 第一次更新：
去掉右上角的头像

社交网络改成国内常用的Github、知乎 、QQ和邮件

description进行了修改，原主题的description加`<br>`会强制转义，导致不能换行。

页面调成3：7 方便文章浏览

把友链改成留言
