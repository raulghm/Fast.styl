Fast.styl
=========

Fast.styl improve and accelerate stylus css projects.

Inspiration
==========

Awesome and recursive syntax: https://github.com/sergeche/emmet-sublime

Simple and intuitive css framework: https://github.com/jenius/roots-css

Install
==========
  1. Clone this repo in your project:
  ``` sh
  git clone git://github.com/raulghm/fast.styl.git
  ```
  2. Import *fast.styl* in your stylus sheet:
    
  ``` CSS
  @import "fast.styl"
  ```
  3. Enjoy fast.styl ;)

Usage
==========

Stylus File:
  
  ``` CSS
  .mySuperClass
    m 10 10
    p 20
    w 100
  	h 100
  	bg red
  	bgi n
  	bd 1px
  	bdc red
  	c blue
  	size 20
  	d b
  ``` 
  

CSS file result:
  ``` CSS
  .mySuperClass {  
    margin: 10px 10px;
    padding: 20px;
    width: 100px;
    height: 100px;
    background: #f00;
    background-image: none;
    border: 1px;
    border-color: #f00;
    color: #00f;
    width: 20px;
    height: 20px;
    display: block;
  }
  ``` 

TODO
==========
Complete documentation
