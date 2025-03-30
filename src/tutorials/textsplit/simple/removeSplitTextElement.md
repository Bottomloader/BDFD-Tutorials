## Text Split - BDFD Tutorials

Hello, here you'll learn how to use the `$removeSplitTextElement[]` function. This is a simple example and advanced ones will be shown later.

This is what BDFD provides us:
```js
$removeSplitTextElement[Index]
```
This seems easy, let's get to it.

You created a lovely `$textSplit` but you wanted to remove the text "hello" which is in index 1. This is where this function comes in hand. It can deleted text splits indexs.
```js
$textSplit[this is a text#this is another text#this is a cooler text!;#]
$removeSplitTextElement[1] $c[Removes "this is a text"]
$splitText[1] $c[Returns "this is another text".]
```


Related Functions - <br>
[$textSplit | Simple](./textSplit.md)<br>
[$splitText | Simple](./splitText.md)<br>
[$getTextSplitIndex | Simple](./getTextSplitIndex.md)<br>
[$editSplitText | Simple](./editSplitText.md)
[$joinSplitText | Simple](./joinSplitText.md)