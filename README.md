# colog
colog



```js
var colog = function(str, color) {
	var code = {
		'black':   '\u001b[30m',
		'red':     '\u001b[31m',
		'green':   '\u001b[32m',
		'yellow':  '\u001b[33m',
		'blue':    '\u001b[34m',
		'magenta': '\u001b[35m',
		'cyan':    '\u001b[36m',
		'white':   '\u001b[37m',
	}[color];
	return code + str + '\u001b[0m';
};

console.log(colog("hoge", "red"));
console.log(colog("hoge", "green"));
console.log(colog("hoge", "blue"));
console.log(colog("hoge", "cyan"));
```
