# CHAPTER 2
## Selectors in CSS <img src="https://github.com/Ninja-Vikash/Assets/blob/main/Asset%20Icon/cssLogo.png" height="20px">

### Useful selectors
|  | Selectors | Syntax |
|:---:|:---|:---|
|1| Type Selector | `h1{key : value}` |
|2| Universal Selector | `*{key : value}` |
|3| Class Selector | `.class{key : value}` |
|4| Id Selector | `#id{key : value}` |
|5| Attribute Selector | `input[type="text"]{key : value}` |
|6| Pseudo-class Selector | `div p:nth-child(1){key : value}` |
|7| Pseudo-element Selector | `p::firstline{key : value}` |
|8| Descendant Combinator | `div span{key : value}` |
|9| Child Combinator | `div > span{key : value}` |
|10| Adjacent Sibling Combinator | `span + h4{key : value}` |
|11| General Sibling Combinator | `div h3 ~ h5{key : value}` |
|12| Combined Selector | `div h3, div h4{key : value}` |

## More info about all selectors
### 🔵 Type Selector
A type selector in CSS is used to select an HTML tag/element in a document.
<pre>
header {
  height : 40px;
  width : 100%;
  background-color: red;
}
h1 {
  color : aqua;
}
</pre>
It is also known as a tag name selector or element selector. Type selectors are not case-sensitive, and they correspond with any HTML element type.

### 🔵 Universal Selector
The * selector selects all elements.
<pre>
* {
   margin : 0;
   padding : 0;
   box-sizing : border-box;
   font-family : 'Gilroy';
}
</pre>
The * selector can also select all elements inside another element.

### 🔵 Class Selector
The class selector selects elements with a specific class attribute. We use the syntax `.class` to select the specific element by its class name.
<pre>
.class1 {
  font-size: 20px;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  color : greenyellow;
  background-color: aliceblue;
}
.class2 {
  font-weight: 500;
  text-align: center;
}
</pre>
**Note**: We can give multiple classes to an element. We can use a class in multiple elements.<br>
`<h1 class="class1 class2">Hello World!</h1>`

### 🔵 Id Selector
The id selector selects elements with a specific id attribute. We use the syntax `#id` to select the specific element by its id name.
<pre>
#my-text {
  font-size: 30px;
  text-align: center;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  color : blueviolet;
  background-color: aqua;
}
</pre>
**Note**: We can give only one id to an element. If you use the same id in multiple elements, it will against of CSS rule. <br>
`<h2 id="username">Ninja Vikash</h2>`

### 🔵 Attribute Selector
The [attribute="value"] selector is used to select elements with a specified attribute and value.
<pre>
input[type="text"] {
  font-size : 20px;
  font-weight : 500;
</pre>

