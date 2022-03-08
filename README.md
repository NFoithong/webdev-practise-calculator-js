# Calculator with Javascript

## Setup
Setup unique name repository on github and remote to local machine to work on project

## HTML
 Set up and create button for calculator 

 ```
<div class="calculator-grid">
        <div class="output">
            <div class="previous-operand"></div>
            <div class="cuurent-operand"></div>
        </div>
        <button class="span-two">AC</button>
        <button>DEL</button>
        <button>÷</button>
        <button>1</button>
        <button>2</button>
        <button>3</button>
        <button>4</button>
        <button>5</button>
        <button>6</button>
        <button>7</button>
        <button>8</button>
        <button>9</button>
        <button>-</button>
        <button>.</button>
        <button>0</button>
        <button class="span-two">=</button>
    </div>
 ```

 ## CSS
 Select all around element include before and after element

 ```
 *, *::before, *::after {
     box-sizing: border-box;
     font-family: <should any font>
 }
 ```

 ## JavaScript

It's not working without starting with window.onload function

```
window.onload=function(){
    .....
    write code here
    .....
}
```

## Screenshot

![Calc screenshot](/Users/Yaiko-Taber/Desktop/webdevpractise/calculatorjs/image/Screen Shot.png)