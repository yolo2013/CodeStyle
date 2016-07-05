# 前端编码规范

> 无论有多少人在维护，所有在代码仓库中的代码理应看起来像同一个人写的。

## 总规范

1. 忽略（Omit）协议：如 background: url(http://www.google.com/images/example); 应该写background: url(//www.google.com/images/example); 以方便http与https协议切换，除非必须使用某个协议
2. 缩进使用两个空格，在IDE的**Settings-Editor-Code Style-Manage-Import**[这个文件](https://github.com/yolo2013/CodeStyle/blob/master/CodeStyle.xml)即可
3. 标签属性使用小写
4. 文件命名使用分隔符`-`
4. 代码提交前，统一在IDE中使用`Ctrl+Alt+L`进行代码格式化

## HTML与CSS

1. ID和Class命名以`-`分隔，如`global-header`
2. 标签属性使用双引号
3. 无需添加浏览器厂商前缀，如'-ms-xxx'，发布时使用 **Autoprefixer** 自动生成

## JavaScript

1. 非HTML模板中，使用单引号`'`
2. 非必要情况下（一行开头是括号或者方括号的时候）不使用分号
3. 命名：functionNamesLikeThis, variableNamesLikeThis, ClassNamesLikeThis, EnumNamesLikeThis, methodNamesLikeThis, SYMBOLIC_CONSTANTS_LIKE_THIS
