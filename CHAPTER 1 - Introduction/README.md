# CHAPTER 1
## Introduction of CSS <img src="https://github.com/Ninja-Vikash/Assets/blob/main/Asset%20Icon/cssLogo.png" height="20px"/>

🔵 **What is CSS?**
 
CSS stands for **Cascading Style Sheet** <br>
It is used to style HTML pages, Which means the beauty of the webpage and how a page looks on the browser's screen. <br>
In simple language -
Suppose HTML is the pillar of the house then CSS is the wall to create rooms and color on walls.

### How can we use CSS in HTML?
Using CSS in HTML is a very easy process.
There are 3 major ways to add CSS in HTML. 

 1. Inline CSS
 2. Internal CSS
 3. External CSS


### Methods of adding CSS -

🔵 **Inline CSS** - We can style HTML elements by adding a style attribute in the opening tag as below
```html
 <h1 style="color : red">This is a heading of Inline CSS</h1>
 <div style="color : yellow">
     <p style="background-color: black; color : white">This is a para</p>
     <p style="font-family: 'Helvetica'; background-color: blue;">This is a another para</p>
     <button style="border : 1px solid grey; border-radius: 5px;">Click Me</button>
 </div>
```
In the above example &lt;h1&gt; has an attribute, which adds inline CSS to &lt;h1&gt; as  `<h1 style="color : red">--context--</h1>`

🔵 **Internal CSS** - We can style HTML elements by creating a `<style>` tag in the `<head>` as below. For selecting 
     any element we will call them by 
     using CSS selector. We will study this in brief CSS selectors in upcoming chapters.
```html
<head>
    <style>
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
    </style>
</head>

<body>
    <section class="internal">
        <h2>This is heading of Internal CSS</h2>
        <div>
            <p>This is a para of Internal CSS section<p>
            <button>Click Here</button>
        </div>
    </section>
</body>
```

**Note** : I used a class selector to style `<section>` by using a dot (.), `.internal` is a class of `<section>`. <br>
`<section class="internal">....</section>`

🔵 <b>External CSS</b> - We can style HTML elements by creating a separate style file and linking it in the head of HTML as below. For selecting elements we will use CSS selectors to select any element as internal CSS.<br>
### Methods of linking External CSS
Step 1 - Create a `<link>` tag inside ---> `<head>`
```html
<link rel="stylesheet" href=" ">
```
**Tip💡** - Here in the link tag rel attribute defines the relation of the linked file with the HTML file. That is `rel="stylesheet"`<br> <br>
Step 2 - Now create a style file as `'style.css'` <br> <br>
Step 3 - Paste the relative URL of `style.css` in the href attribute of `<link>` tag
```html
<link rel="stylesheet" href="style.css">
```

