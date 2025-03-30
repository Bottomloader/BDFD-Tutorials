## Text Split - BDFD Tutorials

Hello, here you'll learn how to use the `$textSplit[]` function. This is a simple example and advanced ones will be shown later.

This is what BDFD provides us:
```js
$textSplit[SomeSEPARATORtext;Separator]
```
Seems confusing right? What does it mean by "seperator", when and why will I use that? I will explain all of those.

Now seperator is for separating the texts in the first argument. Now let's say our seperator is "#" how will I use it? It isn't that hard to guess. You put "#" in between text's you want to seperate. Like "this is a text#this is another text".
```js
$textSplit[this is a text#this is another text;#]
```
If you don't know the syntax of BDFD, ";" is for seperating the texts and the seperator. 
