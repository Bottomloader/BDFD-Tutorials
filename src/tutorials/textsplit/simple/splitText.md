## Text Split - BDFD Tutorials

Hello, here you'll learn how to use the `$splitText[]` function. This is a simple example and advanced ones will be shown later.


This is what BDFD provides us:
```js
$splitText[Index]
```
Now this doesn't seems confusing as placholder but it still makes you question what does it mean by index.

Index is for getting a text from `$textSplit`. For example let's say the seperator is "#" "text#another text". "text"'s index is 1 and "another text"'s is 2. Now why? This will make it easier for us just to get the texts instead of writing long things. "text#anothed text#bdfd is nice" now "bdfd is nice"'s index is 3. In short in start we start with 1 and when we see the seperator we sum the number and that's the index for the text next to it.
```js
$textSplit[this is a text#this is another text;#]
$splitText[2] $c[This returns "this is another text".]
```
You can type "<" or ">" instead of a number. "<" is for the first index and ">" is for the last index. I won't talk much about them.

That's the main idea for text split's

Related Functions - <br>
[$textSplit | Simple](./textSplit.md)<br>
[$getTextSplitIndex | Simple](./getTextSplitIndex.md)<br>
[$editSplitText | Simple](./editSplitText.md)
