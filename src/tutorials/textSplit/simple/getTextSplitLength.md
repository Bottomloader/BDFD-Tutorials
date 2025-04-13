## Text Split - BDFD Tutorials

Hello, here you'll learn how to use the `$getTextSplitLength[]` function. This is a simple example and advanced ones will be shown later.

This is what BDFD provides us:
...Nothing
But there's a reason for that, and that reason is it doesn't require **any** arguments!

This function returns how many index's are in the `$textSplit`. Here's an example:
```js
$textSplit[this is a text#this is another text;#]
$getTextSplitLength $c[Returns 2]
```
This returned 2 since there's two text's—"this is a text" and "this is another text"

See Next -<br>
[$getTextSplitIndex | Simple](./getTextSplitIndex.md)