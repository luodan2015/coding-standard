#### 缩进 {#221-%E7%BC%A9%E8%BF%9B}

##### \[强制\] 使用`4`个空格做为一个缩进层级，不允许使用`2`个空格 或`tab`字符。 {#%E5%BC%BA%E5%88%B6-%E4%BD%BF%E7%94%A8-4-%E4%B8%AA%E7%A9%BA%E6%A0%BC%E5%81%9A%E4%B8%BA%E4%B8%80%E4%B8%AA%E7%BC%A9%E8%BF%9B%E5%B1%82%E7%BA%A7%E4%B8%8D%E5%85%81%E8%AE%B8%E4%BD%BF%E7%94%A8-2-%E4%B8%AA%E7%A9%BA%E6%A0%BC-%E6%88%96-tab-%E5%AD%97%E7%AC%A6}

##### \[强制\]`switch`下的`case`和`default`必须增加一个缩进层级。 {#%E5%BC%BA%E5%88%B6-switch-%E4%B8%8B%E7%9A%84-case-%E5%92%8C-default-%E5%BF%85%E9%A1%BB%E5%A2%9E%E5%8A%A0%E4%B8%80%E4%B8%AA%E7%BC%A9%E8%BF%9B%E5%B1%82%E7%BA%A7}

示例：

```js
// good
switch (variable) {

    case '1':
        // do...
        break;

    case '2':
        // do...
        break;

    default:
        // do...

}

// bad
switch (variable) {

case '1':
    // do...
    break;

case '2':
    // do...
    break;

default:
    // do...

}
```



