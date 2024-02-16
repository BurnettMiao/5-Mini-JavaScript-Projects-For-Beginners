## 1-color-flipper

1. javascript 如果使用 getElementsByTagName 會回傳陣列(HTMLCollection)，因此則需要 index 它

```javascript
const body = document.getElementsByTagName('body')[0];

body.style.backgroundColor = 'red';
```
