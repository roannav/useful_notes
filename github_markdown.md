### Highlighting Code

Use single backtick to spotlight code within a sentence.

use `try`, `except`, `else`, and `finally`.


Use triple backtick to spotlight a BLOCK of code.

``` python
try:
    <i>do something</i>
except Exception as e:
    <b>handle the exception</b>
else:
    **do something, when there is no error or exception**
finally:
    *always do this*
```

FAIL: `<b>` or `<i>` within the code block to bold or italicize.<br>
FAIL: `**` or `*` within the code block to bold or italicize.
<br><br><br>


### Syntax Highlighting Code
Specify the programming language just after the opening triple backticks.

##### Markdown code:
<pre>
``` cpp
bool getBit(int n, int i) {
  return (n >> i) & 1;
}
```
</pre>

##### Result:
``` cpp
bool getBit(int n, int i) {
  return (n >> i) & 1;
}
```
<br><br>

##### Markdown code:
<pre>
``` javascript
window.print();
document.getElementById("name").innerHTML = "Serena";
```
</pre>

##### Result:
``` javascript
window.print();
document.getElementById("name").innerHTML = "Serena";
```
<br><br>

##### Markdown code:
begins with ` ``` html `  and ends with ` ``` `
``` 
<!DOCTYPE html>
<html>
<body>
<h2>Order Form</h2>
<p id="taco">Best TACOS in the world!</p>
<button type="button" onclick="orderTacos()">Order now</button>

<script>
function orderTacos() {
  document.getElementById("taco").innerHTML = "Thank you for your order.";
}
</script>
</body>
</html>
```


##### Result:
``` HTML
<!DOCTYPE html>
<html>
<body>
<h2>Order Form</h2>
<p id="taco">Best TACOS in the world!</p>
<button type="button" onclick="orderTacos()">Order now</button>

<script>
function orderTacos() {
  document.getElementById("taco").innerHTML = "Thank you for your order.";
}
</script>
</body>
</html>
```

##### Markdown code:
<pre>
``` css
.box3 {
  float: left;
  width: 100px;
  height: 100px;
  border: 1px solid grey;

  -webkit-animation: three-color-change 2s;
  animation: three-color-change 2s;
}
```
</pre>

##### Result:
``` css
.box3 {
  float: left;
  width: 100px;
  height: 100px;
  border: 1px solid grey;

  -webkit-animation: three-color-change 2s;
  animation: three-color-change 2s;
}
```
<br><br>


You can specify other languages such as Java, Jupyter Notebook, NumPy, PHP, Perl, SQL, Shell, etc.<br>
See a list of [supported languages](https://gist.github.com/vidaaudrey/14b121a491d889af019e).
<br><br><br>



### Highlighting Text (not code) does not work
``` text
FAIL: <span style="background-color: #FFFF00">hilight me</span>
FAIL: ==hilight me==
FAIL: <mark>hilight me</mark>
```
RESULTS:<BR>
FAIL: <span style="background-color: #FFFF00">hilight me</span><BR>
FAIL: ==hilight me==<BR>
FAIL: <mark>hilight me</mark><BR>
