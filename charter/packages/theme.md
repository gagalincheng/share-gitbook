## 主题插件
### ComScore
ComScore 是一个彩色主题，默认的 gitbook 主题是黑白的，也就是标题和正文都是黑色的，而 ComScore 可以为各级标题添加不同的颜色，更容易区分各级标题，效果如本book所示。

在book.json里添加

```json
{
	"plugins": [
        "theme-comscore"
    ]
}
```
安装插件

```sh
$ gitbook install
```