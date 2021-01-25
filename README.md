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
  <tr><td colspan='2'>Boilerplate: Syntax</td></tr>
 </thead>
 <tbody>
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

## Purpose
HyperText Markup Language, is the process of adding meaning (_semantics_) to your content.  
Obviously, anything you are willing to put time into means something to you.  
When communicating with others, and more so when communication involves an automated process,  
giving the automator a few hints as to what goes where, what means what, how things are supposed to  
go together, help a lot more than people realize.  
The craft, nay the art, of getting all this stuff to work to it's utmost potential...  
Is for people smarter than me. But the basics, that's for everyone these days.


<table>
 <thead>
  <tr><th>Tag</th><th>description <em>-o-</em> summary</th><th>example</th></tr>
   <tr><td colspan='3'>Up and Running Quick!</td></tr>
 </thead>
 <tbody>
  <tr><td>&lt;h1&gt; ... &lt;/h1&gt; <br>
  &lt;h2&gt; ... &lt;/h2&gt; <br>
  &lt;h3&gt; ... &lt;/h3&gt; <br>
  &lt;h4&gt; ... &lt;/h4&gt; <br>
  &lt;h5&gt; ... &lt;/h5&gt; <br>
  &lt;h6&gt; ... &lt;/h6&gt; <br></td><td>
  Headings <br>
  Most ideas can be grouped into logical layers. <br>
  Chapters: Sections: Examples <br>

  </td><td></td></tr>
  <tr><td>&lt;p&gt; ... &lt;/p&gt;</td><td>
  Paragraphs are a highly common element. <br>
  Used to hold your text.</td><td></td></tr>
  <tr><td>&lt;a&gt; ... &lt;/a&gt;</td><td>
  Anchors put the Hyper in HyperText. <br>
  This is how you <em>link</em> your content, to other content,  <br>
  And is the perfect time to introduce <em>attributes</em>
  </td><td></td></tr>
  <tr><td>&lt;br&gt;</td><td>A line break. Notice that this has no closing tag? <br> These can be inserted, usually within your paragraphs, to create a definate line break</td><td></td></tr>
  <tr><td>&lt;hr&gt;</td><td>The Horizontal Rule.</td><td></td></tr>
    
   </tbody>
</table>

Attributes give your elements even more data to work with. In the case of the anchor, the <br>
<em>href</em> attribute tells the browser where to go when you activate (click on) the link.
``` html
<a href='URL-to-your-linked-content'>Link Display</a>
```
One that I particularly like, is <em>target</em>
``` html
<a href='URL-to-your-linked-content' target="_blank">Link Display</a>
```
This opens the linked content in a different browser tab. Other options are available, and we will be looking deeper <br> as we go.

## Organization
How you organize your content, is ultimately up too you. However, there are a selection of tags that help the browser to understand how it all fits together. Be wary, and decide what these mean for you, before getting too lost in the details. Some of these tags are somewhat interchangeable based on your needs, others can be used in many places, and are thus bound to the container in question. One, in particular, should only be used once.

<table>
 <thead>
  <tr><th>Tag</th><th>description <em>-o-</em> summary</th><th>example</th></tr>
   <tr><td colspan='3'>Gather your thoughts</td></tr>
 </thead>
 <tbody>
    <tr><td>&lt;div&gt; ... &lt;/div&gt;</td><td>The division, is a generic container for content. It doesn't exactly have a <em>meaning</em>, <br>
    but is very handy.</td><td></td></tr>
    <tr><td>&lt;header&gt; ... &lt;/header&gt;</td><td>Many collections of data can be given a header, this tends to help <br>
    the browser, and the user, to visually identify what this group of data is about exactly.</td><td></td></tr>
    <tr><td>&lt;footer&gt; ... &lt;/footer&gt;</td><td>
    A section to display related data to the primary content of this collection.</td><td></td></tr>
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

<hr>
<p id='def1'>SEO Crawler: Search Engine Optimization. Basically, <em>Google</em></p>