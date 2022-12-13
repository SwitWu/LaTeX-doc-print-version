## `ctex.dtx`

+ 将 `\section{\LuaLaTeX 下的中文支持方式}` 改为 `\section{\protect\LuaLaTeX 下的中文支持方式}`

## `ctxdoc.cls`

+ 由于原本的中文字体偏细，故设置中文字体为 `fontset = fandol`
+ 注释掉了西文字体设置，改用默认字体
+ `\hypersetup` 中添加了 `colorlinks=false`