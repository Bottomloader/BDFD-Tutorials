# Does it take longer than 40 minutes for you to cum? No worries, we've got you covered, with a trick that lets you bypass the 40 minute limit of thr `$replyIn` function!
But before we get started, please give daddy a kiss on the cheek. I did not specify face cheek or ass cheek so do whichever you want.

Set the stupid fucking variable `duration` to a positive integer, you fucking moron. Keep in mind that node restarts can break this, so drop a nuclear missile on bdfd.
```js
$var[duration;123456]

$if[$var[duration]>2400] $eval[$replaceText[$calculate[10**($var[duration]/2400)-1];9;$$c[]replyIn[40m\]]] $endif
$replyIn[$calculate[$var[duration]%2400+1]s]
```
