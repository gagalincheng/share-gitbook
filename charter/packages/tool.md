## 功能插件
###Search Pro
支持中文，全文搜索

```json
"plugins": [
    "-search",
    "search-pro"
]
```
###Atoc
添加悬浮目录

```json
"plugins": [
    "atoc"
],
"pluginsConfig": {
   	"atoc": {
        "addClass": true,
        "className": "atoc"
    }
}
```

###Splitter
使侧边栏的宽度可以自由调节 

```json
"plugins": [
    "splitter"
]
```

###Prism
语法高亮 [插件地址](https://plugins.gitbook.com/plugin/prism)

```json
"plugins": [
	"-highlight",
    "prism"
],
"pluginsConfig": {
  "prism": {
    "css": [
      "prismjs/themes/prism-solarizedlight.css"
    ]
  }
}
```

###page-footer-ex
自定义页面footer

```json
"plugins": [
    "page-footer-ex"
],
"pluginsConfig": {       
    "page-footer-ex":{
        "copyright":"",
        "update_label":"update",
        "update_format":"YYYY-MM-DD HH:mm:ss",
    }       
}    
```


###github
添加github图标

```json
"plugins": [
    "github"
],
"pluginsConfig": {
    "github": {
        "url": "https://gitlab.gz.cvte.cn/zhengjialin/seewo-school-gitbook"
    }
},
```



















