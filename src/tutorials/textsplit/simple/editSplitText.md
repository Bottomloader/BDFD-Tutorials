## Text Split - BDFD Tutorials

Hello, here you'll learn how to use the `$editSplitText[]` function. This is a simple example and advanced ones will be shown later.

This is what BDFD provides us:
```js
$editSplitText[Index;Value]
```
If we look at the wiki we see there is an long code newbie's will not understand it. But actually this function is very easy to use.

"Index" is where to edit, and "Value" is what to put instead of the old one. Like if the text split's first index is "hello" and we use the function like `$editSplitText[1;Hi]` the first index will get changed to "Hi"!
```js
$textSplit[this is a text#this is another text;#]
$splitText[1] $c[Returns "this is a text"]
$editSplitText[1;BDFD is nice]
$splitText[1] $c[Returns "BDFD is nice"]
```

You made it!
You finished the basics of text split.
