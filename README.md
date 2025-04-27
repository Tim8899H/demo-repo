# demo-repo
a demo for github repo

This is the first commit, good luck. Add on github.

Add a local change with commit.

# 以下是MD语法的小结

1. MD中单个换行相当于空格，只有连续换两行会作为换行进行段落划分；
2. 标题使用#在行首，#最大，##次之，最多6级标题；
3. 前后加\`标识代码，如`This is the code`；
4. 前后加\*标识斜体，如*我是斜体, this is the sample*；
5. 前后加两个\*标识粗体文本，如**我是粗体，this is the sample**；
6. 前后加两个\~标识删除线，如~~我是删除线，this is the sample~~
7. 一行开始连续三个-号形成分割线；
8. 使用```行进行框住的区域为代码区域，显示代码相关高亮效果；
9. 文件链接，网页链接，图片链接显示等使用[]()标识，中括号中为链接内容的标题，圆括号内为链接；
10. 无序列表使用“- ”在行首，则形成无序列表，有序列表使用”数字. “在行首；
11. 直接显示图片，使用“![]()”在行首，圆括号内为图片链接，中括号内可以为空；
12. 表格每一列使用|分隔开，第一行为表格列标题，第二行统一为---，第三行开始为表格内容，第二行可以进行表格对齐的设置；
13. markdown插件中markdown all in one是比较好的插件

## 段落示例
para1-line1.
para1-line2.
para1-line3.

para2-line1.
para2-line2.
para2-line3.

## 斜体字示例
*这是斜体，斜体内容前后不要有空格*

## 粗体字示例
**这是粗体，粗体内容前后不要有空格**

## 删除线示例
~~这是希望标识删除的文字，内容前后不要有空格~~

## 分割线示例

---
分割线以下内容

---
分割线以下内容

## 单行代码示例
代码print：`print("Hello World!)`

## 代码段示例
一个Python代码段：
``` python
import os
print("This is my first python program.")
JAVA_HOME = os.getenv("JAVA_HOME")
print("JAVA_HOME is " + JAVA_HOME)
```
一个c++代码段：
``` cpp
#include <iostream>
int main()
{
    std::out << "Hello World.";
    return 0;
}
```

## 文件链接示例
上述代码请见[test.py](./demo_dir/test1.py)

## 网页链接示例
我查询问题答案一般用[DeepSeek](https://chat.deepseek.com/)

## 无序列表
- line1
- line2
- line3

## 有序列表
1. line1
2. line2
3. line3

## 显示图片
头像：

![](./头像2.jpeg)

## 表格示例
| 小程序     |  性能评分 | 用户数     | 打开次数     |    卡顿率     |   JS错误率    |
|---------|------:|:--------|:---------|:----------:|:----------:|
| 始祖鸟     |   100 | 886829  | 2247610  |   0.031%   |   0.072%   |
| Salomon |    94 | 136268  | 302799   |   0.086%   |   0.194%   |
| 壁克峰-微商城 |   100 | 160888  | 135062   |   0.925%   |   0.004%   |

# END

