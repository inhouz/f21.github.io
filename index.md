## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/inhouz/f21.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/inhouz/f21.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

<!doctype html>
<html>
<head>
<meta charset="utf-8">
 
</head>
 
<body>
 
<DIV id="CountMsg" class="HotDate">
<span id="td">00天</span>
<span id="th">00时</span>
<span id="tm">00分</span>
<span id="ts">00秒</span>
</DIV>
<script type="text/javascript">
function getRTime(){
var EndTime= new Date('2017/10/23 10:00:00'); //截止时间
var NowTime = new Date();
var t =EndTime.getTime() - NowTime.getTime();
 
var d=Math.floor(t/1000/60/60/24);
var h=Math.floor(t/1000/60/60%24);
var m=Math.floor(t/1000/60%60);
var s=Math.floor(t/1000%60);
 
document.getElementById("td").innerHTML = d + "天";
document.getElementById("th").innerHTML = h + "时";
document.getElementById("tm").innerHTML = m + "分";
document.getElementById("ts").innerHTML = s + "秒";
}
setInterval(getRTime,1000);
</script>
</body>

————————————————
版权声明：本文为CSDN博主「Double=Eggs」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/liweizhong193516/article/details/74685902
