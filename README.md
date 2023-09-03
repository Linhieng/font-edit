# 字体

仅仅只是增删字体。

## 提取 ASCII 步骤

1. 使用 FontCreator 打开 `Hack-Regular.ttf` 文件
2. 点击左侧导航栏的 `Unicode`，会看到很多分类，我们只保留 `Basic Latin`，其他的全部删除
3. 打开上方的 `font` --> `properties`，然后编辑 `Family Name` 为 "Hack-ASCII" 来修改字体名称
4. 打开上方的 `file` --> `export font as...` 导出字体文件为 `ttf` 格式

> 说明
>
> `Basic Latin` 一共 95 个字符
>
> ```text
>  1 个空格
> 52 个大小写字母 A-Za-z
> 26 个数字行按键
>     `  1  2  3  4  5  6  7  8  9  0  -  =
>     ~  !  @  #  $  %  ^  &  *  (  )  _  +
> 16 个基本标点符号
>     [   ]   \
>         ;   '
>     ,   .   /
>
>     {   }   |
>         :   "
>     <   >   ?
> ```

## 相关网站

字体编辑器：

- [开源 FontForge](https://fontforge.org/en-US/downloads/windows-dl/)
- [付费 FontCreator 中文代理](https://fontcreator.com.cn/)
- [~~汉化 FontCreator~~](https://www.52pojie.cn/thread-1290173-1-1.html)

字体：

- [Hack](https://github.com/source-foundry/Hack)
