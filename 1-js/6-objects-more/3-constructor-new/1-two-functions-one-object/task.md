# Две функции один объект

[importance 2]

Возможны ли такие функции `A` и `B` в примере ниже, что соответствующие объекты `a,b` равны (см. код ниже)?

```js
//+ no-beautify
function A() { ... }
function B() { ... }

var a = new A;
var b = new B;

alert( a == b ); // true
```

Если да -- приведите пример кода с такими функциями. 