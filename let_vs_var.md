<h4>Concept of "var" and "let" :-</h4>
<hr/>

In Simple js we declare variable like as **`var x = 100;`**.

***Var :-*** "Var" uses **Function Scope**

There are basically **"Two"** types to assign varible :-

1) Local Variable
2) Global Variable

***Local Variable :-***  Those variables who declared in JavaScript Functions are known as "Local Variable" and they can only be accessed from within the function.

*Exa :-*

```
// outside of the fuction code, can not use variable x

function yourFunctionName(){

  var x = 100;
  
  // inside code of this fuction can use variable x
  
}
```
***Global Variable :-***  Those variables who declared outside of JavaScript Functions are known as "Global Variable" and they can be accessed by all functions.


*Exa :-*

```
var x = 100;

// code here can use variable x

function yourFunctionName(){
  
  // code here can also use variable x
  
}
```
