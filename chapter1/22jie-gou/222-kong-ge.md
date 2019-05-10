#### 空格 {#222-%E7%A9%BA%E6%A0%BC}

##### \[强制\] 二元运算符两侧必须有一个空格，一元运算符与操作对象之间不允许有空格。 {#%E5%BC%BA%E5%88%B6-%E4%BA%8C%E5%85%83%E8%BF%90%E7%AE%97%E7%AC%A6%E4%B8%A4%E4%BE%A7%E5%BF%85%E9%A1%BB%E6%9C%89%E4%B8%80%E4%B8%AA%E7%A9%BA%E6%A0%BC%E4%B8%80%E5%85%83%E8%BF%90%E7%AE%97%E7%AC%A6%E4%B8%8E%E6%93%8D%E4%BD%9C%E5%AF%B9%E8%B1%A1%E4%B9%8B%E9%97%B4%E4%B8%8D%E5%85%81%E8%AE%B8%E6%9C%89%E7%A9%BA%E6%A0%BC}

示例：

```js
var a = !arr.length;
a++;
a = b + c;
```

##### \[强制\] 用作代码块起始的左花括号`{`前必须有一个空格。 {#%E5%BC%BA%E5%88%B6-%E7%94%A8%E4%BD%9C%E4%BB%A3%E7%A0%81%E5%9D%97%E8%B5%B7%E5%A7%8B%E7%9A%84%E5%B7%A6%E8%8A%B1%E6%8B%AC%E5%8F%B7-%E5%89%8D%E5%BF%85%E9%A1%BB%E6%9C%89%E4%B8%80%E4%B8%AA%E7%A9%BA%E6%A0%BC}

示例：

```js
// good
if (condition) {
}

while (condition) {
}

function funcName() {
}

// bad
if (condition){
}

while (condition){
}

function funcName(){
}
```

##### \[强制\]`if / else / for / while / function / switch / do / try / catch / finally`关键字后，必须有一个空格。 {#%E5%BC%BA%E5%88%B6-if-else-for-while-function-switch-do-try-catch-finally-%E5%85%B3%E9%94%AE%E5%AD%97%E5%90%8E%E5%BF%85%E9%A1%BB%E6%9C%89%E4%B8%80%E4%B8%AA%E7%A9%BA%E6%A0%BC}

示例：

```js
// good
if (condition) {
}

while (condition) {
}

(function () {
})();

// bad
if(condition) {
}

while(condition) {
}

(function() {
})();
```

##### \[强制\] 在对象创建时，属性中的`:`之后必须有空格，`:`之前不允许有空格。 {#%E5%BC%BA%E5%88%B6-%E5%9C%A8%E5%AF%B9%E8%B1%A1%E5%88%9B%E5%BB%BA%E6%97%B6%E5%B1%9E%E6%80%A7%E4%B8%AD%E7%9A%84-%E4%B9%8B%E5%90%8E%E5%BF%85%E9%A1%BB%E6%9C%89%E7%A9%BA%E6%A0%BC-%E4%B9%8B%E5%89%8D%E4%B8%8D%E5%85%81%E8%AE%B8%E6%9C%89%E7%A9%BA%E6%A0%BC}

示例：

```js
// good
var obj = {
    a: 1,
    b: 2,
    c: 3
};

// bad
var obj = {
    a : 1,
    b:2,
    c :3
};
```

##### \[强制\] 函数声明、具名函数表达式、函数调用中，函数名和`(`之间不允许有空格。 {#%E5%BC%BA%E5%88%B6-%E5%87%BD%E6%95%B0%E5%A3%B0%E6%98%8E-%E5%85%B7%E5%90%8D%E5%87%BD%E6%95%B0%E8%A1%A8%E8%BE%BE%E5%BC%8F-%E5%87%BD%E6%95%B0%E8%B0%83%E7%94%A8%E4%B8%AD%E5%87%BD%E6%95%B0%E5%90%8D%E5%92%8C-%E4%B9%8B%E9%97%B4%E4%B8%8D%E5%85%81%E8%AE%B8%E6%9C%89%E7%A9%BA%E6%A0%BC}

示例：

```js
// good
function funcName() {
}

var funcName = function funcName() {
};

funcName();

// bad
function funcName () {
}

var funcName = function funcName () {
};

funcName ();
```

##### \[强制\]`,`和`;`前不允许有空格。如果不位于行尾，`,`和`;`后必须跟一个空格。 {#%E5%BC%BA%E5%88%B6-%E5%92%8C-%E5%89%8D%E4%B8%8D%E5%85%81%E8%AE%B8%E6%9C%89%E7%A9%BA%E6%A0%BC-%E5%A6%82%E6%9E%9C%E4%B8%8D%E4%BD%8D%E4%BA%8E%E8%A1%8C%E5%B0%BE-%E5%92%8C-%E5%90%8E%E5%BF%85%E9%A1%BB%E8%B7%9F%E4%B8%80%E4%B8%AA%E7%A9%BA%E6%A0%BC}

示例：

```js
// good
callFunc(a, b);

// bad
callFunc(a , b) ;

```

##### \[强制\] 在函数调用、函数声明、括号表达式、属性访问、`if / for / while / switch / catch`等语句中，`()`和`[]`内紧贴括号部分不允许有空格。 {#%E5%BC%BA%E5%88%B6-%E5%9C%A8%E5%87%BD%E6%95%B0%E8%B0%83%E7%94%A8-%E5%87%BD%E6%95%B0%E5%A3%B0%E6%98%8E-%E6%8B%AC%E5%8F%B7%E8%A1%A8%E8%BE%BE%E5%BC%8F-%E5%B1%9E%E6%80%A7%E8%AE%BF%E9%97%AE-if-for-while-switch-catch-%E7%AD%89%E8%AF%AD%E5%8F%A5%E4%B8%AD-%E5%92%8C-%E5%86%85%E7%B4%A7%E8%B4%B4%E6%8B%AC%E5%8F%B7%E9%83%A8%E5%88%86%E4%B8%8D%E5%85%81%E8%AE%B8%E6%9C%89%E7%A9%BA%E6%A0%BC}

示例：

```js
// good

callFunc(param1, param2, param3);

save(this.list[this.indexes[i]]);

needIncream && (variable += increament);

if (num > list.length) {
}

while (len--) {
}


// bad

callFunc( param1, param2, param3 );

save( this.list[ this.indexes[ i ] ] );

needIncreament && ( variable += increament );

if ( num > list.length ) {
}

while ( len-- ) {
}
```

##### \[强制\] 单行声明的数组与对象，如果包含元素，`{}`和`[]`内紧贴括号部分不允许包含空格。 {#%E5%BC%BA%E5%88%B6-%E5%8D%95%E8%A1%8C%E5%A3%B0%E6%98%8E%E7%9A%84%E6%95%B0%E7%BB%84%E4%B8%8E%E5%AF%B9%E8%B1%A1%E5%A6%82%E6%9E%9C%E5%8C%85%E5%90%AB%E5%85%83%E7%B4%A0-%E5%92%8C-%E5%86%85%E7%B4%A7%E8%B4%B4%E6%8B%AC%E5%8F%B7%E9%83%A8%E5%88%86%E4%B8%8D%E5%85%81%E8%AE%B8%E5%8C%85%E5%90%AB%E7%A9%BA%E6%A0%BC}

解释：

声明包含元素的数组与对象，只有当内部元素的形式较为简单时，才允许写在一行。元素复杂的情况，还是应该换行书写。

示例：

```js
// good
var arr1 = [];
var arr2 = [1, 2, 3];
var obj1 = {};
var obj2 = {name: 'obj'};
var obj3 = {
    name: 'obj',
    age: 20,
    sex: 1
};

// bad
var arr1 = [ ];
var arr2 = [ 1, 2, 3 ];
var obj1 = { };
var obj2 = { name: 'obj' };
var obj3 = {name: 'obj', age: 20, sex: 1};
```

##### \[强制\] 行尾不得有多余的空格。 {#%E5%BC%BA%E5%88%B6-%E8%A1%8C%E5%B0%BE%E4%B8%8D%E5%BE%97%E6%9C%89%E5%A4%9A%E4%BD%99%E7%9A%84%E7%A9%BA%E6%A0%BC}



