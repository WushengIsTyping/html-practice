# README

THis folder is for html practice. 

## Things to Remember
1. necessary tags: html, body
2. important tags: 
   * h1, h2, h3 for titles
   * p for passage
   * a for link
   * br for a new line
   * hr for horrizontal line
   * img for images, remind to write the path correct, "alt" appears when your mouse move to the image
   * center for making all text in tags center-aligned
   * table for table, tr for row, th for table head, td for column
   * \<!--> <--> for comment
   * i for italic, etc. search when you need
   * code for computer code 
   * ul for un-ordered list, ol for ordered list, li for list index
   * span feels like class, use for text in a line, not a div
3. useful properties
   * width, height for img
   * align for h1, h2, h3 titles
   * bgcolor for background color of body (whole page)
   * class for classname, can be used for hint and comment, will show in outline, name is good for structure
   * id for unique id, can be used as link anchor, easy to reference in JavaScript or CSS
   * style for inline style, e.g. font-family, font-size, color
   * title for title of webpage, not in this document
4. put style properties in a .css file can make your code much cleaner
5. tag div with classes, you can deal with same class at the same time, see practice-3
6. \<!DOCTYPE html> for HTML5, HTML4 has multiple different doctype, most browser support HTML5
7. layout: html5(easy) or div(flexible), see practice-4
8. meta tag should be put at the beginning of head
   * charset: document character coding, e.g. "UTF-8"
   * name and content: author/keywords/description, e.g. \<meta name="description" content="tutorial">
   * viewport content 视窗设置: 
     * width: 可视区域的宽度
     * initial-scale: 页面首次显示的缩放级别
     * user-scalable: 用户是否可缩放
   * \<meta http-equiv="X-UA-Compatible" content="IE=edge"> 运行在IE浏览器上时优先用最高模式进行解析渲染
9.  use bootstrap as much as you can!!
10. frameset: resizable frames, you can put 3 html files on one page, use \<frame src="practice-1.html" /> \
    iframe: 把HTML页面作为一个模块插入的感觉，用于在网页内显示网页
11. script: put in head-->execute when page is loaded, put in body-->execute when it is called

    ```
      <script type="text/javascript">
          document.write("\<h1>Hello World!</h1>")
      </script>
      <noscript>
          Your browser does not support JavaScript.
      </noscript>
    ```
    <p> noscript tag will appear when your browser doesn't support this script language
12. head can contain title, meta, link, style, script

## Bootstrap
1. you need to use html5 to ensure bootstrap can work
2. add \<meta name="viewport" content="width=device-width, initial-scale=1.0"> to ensure it works on mobile
3. find components here: https://v3.bootcss.com/components/
4. bootstrap javascript pugins needs jquery, if you want to use them you need to add
    ```
      <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
      <script src="bootstrap-3.3.7-dist/js/jquery-3.1.1.min.js"></script>
      <!-- Include all compiled plugins (below), or include individual files as needed -->
      <script src="bootstrap-3.3.7-dist/js/bootstrap.min.js"></script>
    ```

## Content of Practices
P1: simple page with titles, passage, link, start new line, image, table, horrizontal line, comment, list
P2: common properties, e.g. align, border, name, style, span
P3: CSS for style, style in header for classes
P4: layout, id usage
P5: meta tag, responsive/adaptive (to screen size) design, which is necessary for mobile device
P6: Bootstrap

## Useful Links
tutorial: http://www.w3school.com.cn/html/index.asp \
layout: http://www.w3school.com.cn/html/html_responsive.asp \
bootstrap: https://www.runoob.com/bootstrap/bootstrap-tutorial.html \
bootstrap getting started: https://v3.bootcss.com/getting-started/#grunt \
bootstrap component: https://v3.bootcss.com/components/
