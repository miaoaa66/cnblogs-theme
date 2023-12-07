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
      avatar: 'https://foruda.gitee.com/avatar/1676425187895746361/10704733_miaoaa66_1676425187.png!avatar200',
      headerBackground: 'https://img2023.cnblogs.com/blog/3178228/202311/3178228-20231105195347911-1287900573.jpg'
    },
    signature: {
        enable: true,
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
            url: 'https://github.com/MiaoAA-Hello',
        },
        gitee: {
            enable: true,
            url: 'https://gitee.com/miaoaa66',
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
    links: [
        {
            name: "&nbsp&nbsp&nbsp&nbsp&nbsp&nbspGIT AND WEB          ",
            link: "",
        },
        {
            name: "🚀 GitHub",
            link: "https://github.com/MiaoAA-Hello",
        },
        {
            name: "✈️ Gitee",
            link: "https://gitee.com/miaoaa66",
        },
        {
            name: "📺 Bilibili",
            link: "https://space.bilibili.com/40717608",
        },
            {
            name: "🎵 WYY",
            link: "https://music.163.com/#/user/home?id=454539644",
        },
        {
            name: "&nbsp&nbsp&nbsp&nbsp&nbsp&nbspFriendly Link          ",
            link: "",
        },
        {
            name: "🏂 十二月",
            link: "http://blog.ti3.cc/",
        },
        {
            name: "🏂 南烟",
            link: "https://isujin.cn/home",
        },
        {
            name: "🏂 护法师兄",
            link: "https://www.cnblogs.com/jonil/",
        },
    ],
  }
  $.awesCnb(opts)
</script>
```

## 附上主题作者仓库，感谢[guangzan](https://www.cnblogs.com/guangzan/)带来的主题

```
https://github.com/cnbloglabs/theme-geek/

```

