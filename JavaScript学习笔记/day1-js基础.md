# Js基础-day1
## ECMAScript入门
### 1.Js介绍
### 2.JavaScript变量
==数据类型==
- Number
----parseInt()
----parseFloat()
- String
----String()
----toString()
- Boolean
----**undefined、null、NaN、false、0、"" 转换成 boolean 值均为 false**
- NULL
```
var car = null
console.log(typeof(car)) // object

```

- Undefined
----undefined 和 null 都不能 .toString() 转换
```
console.log(null==undefined)//true undefined派生于null
console.log(null===undefined)//false

```

- Object
 Array、Object、Funtion

**检测数据类型的方法typeof（）**


