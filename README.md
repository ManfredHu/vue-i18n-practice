# i18n test
base Vue 3 + Typescript + Vite
i18n test

## 启用volar而不是vetur
2.0 vetur
3.x volar

本项目3.x，请关闭vetur，否则一堆报错。可以看下`.vscode/settings.json`

## i18n

国际化地区编码对照表：https://xiaogliu.github.io/2019/10/11/i18n-locale-code/

需要VSCode插件[Lokalise.i18n-ally](https://marketplace.visualstudio.com/items?itemName=Lokalise.i18n-ally)

最后应该是这样的

![](https://manfredhu-1252588796.cos.ap-guangzhou.myqcloud.com/uPic/AHiX6u.jpg)

可以通过修改`.vscode/settings.json`的`i18n-ally.sourceLanguage`切换编辑器的语言，比如设置

```json
{
  ……
  "i18n-ally.sourceLanguage": "zh",
  ……
}
```

![](https://manfredhu-1252588796.cos.ap-guangzhou.myqcloud.com/uPic/tyEZVL.jpg)

## 机翻
使用插件直接翻译到对应语言的文本出来

![](https://manfredhu-1252588796.cos.ap-guangzhou.myqcloud.com/uPic/K6AYqV.jpg)

会自动增加文本
![](https://manfredhu-1252588796.cos.ap-guangzhou.myqcloud.com/uPic/mwiLoV.jpg)
