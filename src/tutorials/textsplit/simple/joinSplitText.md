## Text Split - BDFD Tutorials

Hello, here you'll learn how to use the `$joinSplitText[]` function. This is a simple example and advanced ones will be shown later.

This is what BDFD provides us:
```js
$joinSplitText[Seperator]
```
This seems real easy, so let's not loose any time.

So you define the seperator in $textSplit, but you can change it with this function. For example if your seperator is "-" and you want to make it "#" you can use the function. This will change every "-" to "#".
```js
$textSplit[this is a text-this is another text;-]
$joinSplitText[#] $c[The separator is now "#".]
```
