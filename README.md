# learn-html
 Content is key. HTML is content.

 Github runs it's documentation, primarily, on markdown. This can include most _if not all_ standard html tags.

 <code>Like So</code>

 But markdown offers a few shortcuts, that really assist in the process

 ``` javascript
   function testMarkdownDisplay(){
       // And do some stuff
   }
 ```

We will get more in depth into that at a later time. For now, we will focus on the basics of HTML for Web Design, PDF design, and all the things.


## Boilerplate: 
### The bare minimum

Do not be concerned if you do not recognize or understand this. These following lines are the first leap of faith. They work. They are _mostly_ needed. Just use it and trust.
``` html
  <!DOCTYPE html>
   <html>
    <head>
     <title></title>
    </head>

    <body>
     <!-- Commentary  -->
    </body>
   </html>
```

<table>
 <thead>
  <tr><th>Tag</th><th>description <em>-o-</em> summary</th></tr>
 </thead>
 <tbody>
  <tr><td colspan='2'>Boilerplate: Syntax</td></tr>
  <tr><td>&lt;&gt;</td><td>An HTML element, is decalared with the brackets. <br>Most will be paired with a closing bracket <em>&lt;/&gt;</em></td></tr>

  <tr><td>&lt;!DOCTYPE html&gt;</td><td>In the olden days, before standards were standard, <br>
    You needed to know precisely how your page was to be formed, <br>
    and which elements you planned to use. <br>
    This line tells the browser to use the standard.
  </td></tr>
  <tr><td>&lt;html&gt; ... &lt;/html&gt;</td><td>
  All the pages contents will go inside this pair. <br>
  Notice, from now on, all tags that come in pairs<br>
  should be opened, and closed AS pairs, with any content <br>
  wrapped properly. 
  </td></tr>
  <tr><td>&lt;head&gt; ... &lt;/head&gt;</td><td>
  This element holds information about the document. <br>
  In many cases, supporting information is also listed here, <br>
  to add functionality, style information, and more. <br>
  Specifics addressed as needed.
  </td></tr>
  <tr><td>&lt;title&gt; ... &lt;/title&gt;</td><td>
   The name of the document, for display in the browser tab, <br>
   And for <a href='#def1' title='Search Engines'>SEO Crawlers</a> for indexing.
  </td></tr>
  <tr><td>&lt;body&gt; ... &lt;/body&gt;</td><td>
  The bulk of the project will be inside this element.
  </td></tr>
  <tr><td>&lt;!-- ... --&gt;</td><td>
   Commentary isn't seen on the final product. <br>
   It can be viewed in the code. <br>
   There will be many times you wish you had comments. <br>
   And likely moments when they are too much. <br>
   Practice using them everywhere, until you get the hang of <br>
   where the line of <span title='Too Much Information'><em>TMI</em></span> is located.
  </td></tr>
  </tbody>
</table>

<!--
<table>
 <thead>
  <tr><th>Tag</th><th>description <em>-o-</em> summary</th><th>example</th></tr>
 </thead>
 <tbody>
  
  <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
  <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
  <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
  <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
  <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
  <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
  <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
  <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
  <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
  <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
    <tr><td>&lt;&gt; ... &lt;/&gt;</td><td></td><td></td></tr>
  <tr><td></td><td></td><td></td></tr>
 </tbody>
</table>
 -->

<hr>
<p id='def1'>SEO Crawler: Search Engine Optimization. Basically, <em>Google</em></p>