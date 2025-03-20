## Text Split - BDFD Tutorials

Hello, here you'll learn how to use the `$getTextSplitIndex[]` function. This is a simple example and advanced ones will be shown later.

This is what BDFD provides us:
```js
$getTextSplitIndex[Value]
```
This one seems easy enough, it's like a browser. If it exists in the database it shows them. 

Think `$textSplit` is our database and `$getTextSplitIndex` is our browser. If we write an existing value to the function it returns the text's index. If you provide a non-existing text it will return "-1". I have talk about what is index so I won't talk about it here. 
```js
$textSplit[this is a text#this is another text;#]
$getTextSplitIndex[this is another text] $c[Returns "2"]
$getTextSplitIndex[BDFD is the best] $c[Returns "-1" as this doesn't exist.]
```

Related Functions - <br>
[$textSplit | Simple](./textSplit.md)<br>
[$splitText | Simple](./splitText.md)<br>
[$editSplitText | Simple](./editSplitText.md)
