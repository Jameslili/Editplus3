Editplus3
==========
Use EditPlus有代码自动完成功能和zen Coding功能

自动完成功能设置是这样的
-----------------------
点菜单‘工具’-‘参数设置’-左边‘设置&语法’-右上边‘HTML’-右下边‘自动完成’前面打上勾，加载‘XHTMLBAR.ACP’，应用确定。<br>
关闭软件再重新打开，在html里输入如‘H1’然后按空格，就会出现<h1></h1>了，按什么出来什么是可以自定义的，刚刚加载那个html自动完成的文件里你可以看见
```
#T=H1
<h1>^!</h1>
```
这是设置的一组代码，#T=后面的就是你要简单输入的代码，下面一排就是自动完成的代码，^!是光标停留的地方，你也可以设置
```
#T=hhh
<h1 class="">^!</h1>
```
这只是举个例子，这时候按hhh和空格就会出来`<h1 class=""><h1>`，你习惯什么就怎么写好了
其他语法也可以自己设置。注意修改了文件后要重新启动软件才能生效。      
zen Coding设置 
-----------
就是点菜单上的‘Zen Coding‘-‘使用zen Coding’
然后比如你输入`‘div#header>p.abc*5’`然后按`ctrl+e`就会出来下面这些代码了
```
<div id="header">
<p class="abc"></p>
<p class="abc"></p>
<p class="abc"></p>
<p class="abc"></p>
<p class="abc"></p>
</div>experience how to use it easy to automating completion the pages
```
快捷键
---------
*自动换到下一行对其位置`ctrl+enter`  
*一键注释`ctrl+/`   
*自动复制这一行`ctrl + '+'`    
