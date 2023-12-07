# 博客园皮肤geek

## 配置教程

```
https://www.cnblogs.com/jonil/p/17607499.html
```

## 页面定制css更改为如下，并禁用模板默认css

```
#loading{bottom:0;left:0;position:fixed;right:0;top:0;z-index:9999;background-color:#f4f5f5;pointer-events:none;}.loader-inner{will-change:transform;width:40px;height:40px;position:absolute;top:50%;left:50%;margin:-20px 0 0 -20px;background-color:#3742fa;border-radius:50%;animation:scaleout 0.6s infinite ease-in-out forwards;text-indent:-99999px;z-index:999991;}@keyframes scaleout{0%{transform:scale(0);opacity:0;}40%{opacity:1;}100%{transform:scale(1);opacity:0;}}
```

## 页首HTML代码更改为如下，主要是加载时的动画

```
<div id="loading">
    <div class="spinner-box">
        <div class="blue-orbit leo"></div>
        <div class="green-orbit leo"></div>
        <div class="red-orbit leo"></div>
        <div class="white-orbit w1 leo"></div>
        <div class="white-orbit w2 leo"></div>
        <div class="white-orbit w3 leo"></div>
    </div>
</div>
```

## 页脚HTML代码更改为如下，可根据需要开启和关闭

```
<script src="https://guangzan.gitee.io/awescnb/index.js"></script>
<script>
  const opts = {
    theme: {
      name: 'geek',
      avatar: 'https://pic.cnblogs.com/avatar/2722327/20220216172220.png',
      headerBackground: 'https://img2023.cnblogs.com/blog/2722327/202308/2722327-20230803215755489-1940866103.png'
    },
    signature: {
    enable: false,
    contents: [
    "冰冻三尺，非一日之寒。",
    ],
    imagebox: {
    enable: true,
    },
    darkMode: {
    enable: true,
    autoDark: false,
    autoLight: false
    },
    github: {
      enable: true,
      url: 'https://github.com/jonilchan',
    },
    gitee: {
      enable: true,
      url: 'https://gitee.com/jonil',
    },
    catalog: {
      enable: true,
      position: 'left',
    },
    tools: {
      enable: true,
      initialOpen: true,
    },
    topProgress: {
      enable: true,
    },
},
  }
  $.awesCnb(opts)
</script>
```

## 附上主题作者仓库，感谢[guangzan](https://www.cnblogs.com/guangzan/)带来的主题

```
https://github.com/cnbloglabs/theme-geek/

```

