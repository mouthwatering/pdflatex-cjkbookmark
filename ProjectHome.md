因为之前一直没找到解决办法，所以只能用英文的书签，偶尔看到gbk2uni的办法，然后自己用python脚本写了一个简单的转换程序。

日志在这里
http://www.thinkemb.com/wordpress/?p=260

用法
```
pdflatex book.tex
utf8bookmark.py book.out
pdflatex book.tex
```

最终的效果如下

![http://pdflatex-cjkbookmark.googlecode.com/files/esnap_57.png](http://pdflatex-cjkbookmark.googlecode.com/files/esnap_57.png)