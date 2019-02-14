```js
/*marked(markdownString [,options] [,callback])

Member	        Type	    Default
baseUrl	        string	    null        任何相对链接的前缀url
breaks	        boolean	    false       如果为true，添加<br>一个换行符（copies GitHub）。需要gfm是true。
gfm	            boolean	    true        如果为true，使用被认可的GitHub Flavored Markdown（GFM）规范
headerIds	    boolean	    true        如果为true，在生成标题时包含id属性。（h1，h2，h3等）
headerPrefix	string	    ''          在生成标题时为id属性添加前缀的字符串。（h1 id="asd-id"，h2，h3等）
highlight	    function	null        一个函数用于突出显示代码块的功能，请参阅Asynchronous highlighting.。
langPrefix	    string	    'language-' 用于在<code>块中为className添加前缀的字符串。用于语法突出显示。
mangle	        boolean	    true        如果为true，自动链接的电子邮件地址将使用HTML字符引用转义
pedantic	    boolean	    false       如果为true，尽可能遵照原始markdown.pl。不修复原有的错误或表现。关闭并覆盖gfm。
renderer	    object	    new Renderer() 将标记渲染为HTML的函数的对象。有关详细信息，请参阅扩展性
sanitize	    boolean	    false       如果为true，使用sanitizer函数对传递到markdownstring的HTML进行清理。
sanitizer	    function	null	    一种函数对传入到markdownString的HTML进行清理。
silent	        boolean	    false	    如果为true，解析器不会抛出任何异常。
smartLists	    boolean	    false	    如果为true，使用比markdown.pl拥有的更智能的列表行为。
smartypants	    boolean	    false	    如果为true，使用“智能”排版标点符号来表示引号和短划线。
tables	        boolean	    true	 	如果为true且gfm为true，使用GFM Tables扩展。
XHTML	        boolean	    false	 	如果为true，在生成自闭合的HTML空元素标签时（<br/>，<img />等）加上XHTML所需的“/”。
*/
```
![options](../images/marked.js options.PNG)