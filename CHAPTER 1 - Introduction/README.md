# CHAPTER 1
## CSS - Introduction
<p>
<b>What is CSS?</b><br>
CSS stands for 'Cascading Style Sheet'.
It is used to style HTML pages, Which means the beauty of the webpage and how a page looks on the browser's screen.
In simple language -
Suppose HTML is the pillar of the house then CSS is the wall to create rooms and color on walls.
</p>

### How can we use CSS in HTML?
Using CSS in HTML is a very easy process.
There are 3 major ways to add CSS in HTML. 

<b>Methods of adding CSS</b>:<br>
 1. Inline CSS
 2. Internal CSS
 3. External CSS


### How to use-
<b>Inline CSS</b> - We can style HTML elements by adding a style attribute in the opening tag as below
<pre>
 &lth1 style="color : red"&gtThis is a heading of Inline CSS&lt/h1&gt
 &ltdiv style="color : yellow"&gt
            &ltp&gt style="background-color: black; color : white"&gtThis is a para&lt/p&gt
            &ltp&gt style="font-family: 'Helvetica'; background-color: blue;"&gtThis is a another para&lt/p&gt
            &ltbutton&gt style="border : 1px solid grey; border-radius: 5px;"&gtClick Me&lt/button&gt
 &lt/div&gt
</pre>
  <b>Internal CSS</b> - We can style HTML elements by creating a style tag in the head as below. For selecting any element we will call them by 
   using CSS selector. We will study this in brief CSS selectors in upcoming chapters.
<pre>
&lthead&gt
    &ltstyle&gt
        .internal {
            font-family: Verdana, Geneva, Tahoma, sans-serif;
        }
        .internal h2 {
            color : blue;
            background-color: aqua;
        }
        .internal div > button {
            font-size: 30px;
        }
    &lt/style&gt
&lt/head&gt

&ltbody&gt
    &ltsection class="internal"&gt
        &lth2&gt>This is heading of Internal CSS&lt/h2&gt
        &ltdiv&gt
            &ltp&gtThis is a para of Internal CSS section&lt/p&gt
            &ltbutton&gt>Click Here&lt/button&gt
        &lt/div&gt
    &lt/section&gt
&lt/body&gt
</pre>
