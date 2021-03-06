# hugo-pacman-theme

Demo: http://coderzh.github.io/hugo-pacman-theme/

## config.toml

```toml
BaseURL = "http://coderzh.github.io/hugo-pacman-theme/"
LanguageCode = "zh-CN"
HasCJKLanguage = true
Title = "Hugo PacMan Theme Demo"
Theme = "hugo-pacman-theme"
pygmentsStyle = "default"
pygmentsUseClasses = true


[outputs]
  home = [ "RSS", "HTML" ]
    
[outputFormats] 
  [outputFormats.RSS]
    mediatype = "application/rss"
    baseName = "feed"

[Params]
  AuthorName = "coderzh"
  AuthorHomepage = "https://blog.coderzh.com"
  BottomIntroduce = "Introduce1 <br/> Introduce2"
  Description = ""
  Subtitle = "subtitle"
  Weibo = "coderzh"
  WeiboID = 1816308191
  Twitter = "coderzh"
  GitHub = "coderzh"
  Facebook = "coderzh"
  LinkIn = "coderzh"
  Imglogo = "img/logo.svg"
  AuthorImg = "img/author.jpg"
  DateFormat = "2006年01月02日"
  MonthFormat = "2006年01月"
  FancyBox = true

  [Params.GoogleAnalytics]
    ID = "UA-10147768-2"

  [Params.Disqus]
    ShortName = "coderzh"

  [Params.Strings]
    Search = "搜索"
    PageNotFound = "你访问的页面不存在"
    ShowSideBar = "显示侧边栏"
    HideSideBar = "隐藏侧边栏"
    Categories = "分类"
    Archive = "归档"
    Tags = "标签"
    TagCloud = "标签云"
    Rss = "RSS 订阅"
    TableOfContents = "文章目录"

[Menu]
  [[Menu.Main]]
    Name = "首页"
    URL = "/"
    Weight = 1
  [[Menu.Main]]
    Name = "关于"
    URL = "/about"
    Weight = 2
```

## ScreenShot

![hugo-pacman-theme](https://raw.githubusercontent.com/coderzh/hugo-pacman-theme/eda9c351a538558f42a0b086a9320c99dd98e579/images/screenshot.png)
