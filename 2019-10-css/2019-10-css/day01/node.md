## 安装的两个插件
1、chinese  汉化vscode
2、open in browser   在浏览器打开

## 基本设置
1、自动保存：文件---首先项--设置   Auto Save afterDelay  Auto Save Delay ：1000 （在1000ms后自动保存，不用手动的ctrl+s）
2、设置文字的大小：文件--首先项--设置  Font Size
3、自动换行：文件---首选项---设置  Word Wrap：on

4、设置皮肤：文件---首选项---颜色主题（l开头的代表浅颜色的，d开头代表深色的）

## 如何快速新建一个html文件
1、新建一个以“.html”为后缀名的文件。
2、在英文输入法下，按！ +enter

## 如何预览
shift+alt+b ：在其它浏览器打开
alt+b: 在默认浏览器打开
鼠标右键选择 

##马克飞象的用法
标题分为六级  快捷键ctrl+（1-5）

加粗：ctrl+b
斜体：ctrl+i

分割线：*** 或者 ---

列表：符合可以是+ 或者 -  如果想要生成子列表，直接按tab键，如果想让子列表回退到上一级 shift+ tab  连续按两次enter键即可退出列表的编辑

引用 ：>   (会产生灰色的背景)

代码块：ctrl+k(连续按三次)

特殊标记：ctrl+k

文字链接：ctrl+l 记着修改[描述的文字] 里面的文字

插入图片：ctrl+g  
   1、可以是在线图片 
   2、也可以是本地 
   3、可以用ctrl+alt+a  截图  ctrl+v  直接粘贴到马克飞象

帮助文档：ctrl+\
最大化编辑区：ctrl+enter  
最大化预览区：ctrl+alt+enter  

## 常见浏览器的内核
1、谷歌浏览器：webkit  现在改成了blink
2、火狐浏览器：gecko
3、ie浏览器：trident
4、欧朋浏览器：presto
## 工作流程
需求-----产品出一个原型图  需求文档 ----需求会--ui根据原型图做成设计稿---web前端还原设计稿（包含数据的获取，以及业务逻辑的实现）------测试（专门的测试人员）----上线---测试

## html标签的特点
绝对多数：
1、关键词 由尖括号括起来
2、成对出现：开始标签 和结束标签
3、结束标签比开始标签多了一个反斜杠
特别的：
比如 <meta> <br> <img> 等，这一类叫做"单标签"或者"自闭和标签"或者"空标签".

## html的基本结构
```
<!DOCTYPE html>  // 声明是html文档
<html lang="en"> // lang=en 代表的是英文，如果是lang="zh-cn"中文，或者省去不写，就是中文。
    <head>
       <meta charset="utf-8"> //utf-8 国际通用编码，不写的时候会乱码
       <meta name="description" content="描述">
       <meta name="keywords" content="关键词">
       <title>网页标题</title>
    </head>
    <body>
        可视区域
        欢迎大家加入第十期css群
    </body>
</html>

```

## 标题标签
分为六级：h1-h6
快捷键：h${$级标题}*6+tab