# Js基础-day1
## ECMAScript入门
### 1.Js介绍
### 2.JavaScript变量
==数据类型==
- Number
----parseInt()
----parseFloat()
- String-字符串，带双引号
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

==定义变量==
定义变量的语法：
```
var wan = "大碗宽面";
console.log(wan);
var wan = "鸡蛋";
console.log(wan);
var s1 = "a3";
var s2 = 'a2';
var s3 = `a4`;
var n1 = 123;
var f1 = true;
```
**var a; // 变量被定义的时候默认赋值 undefined = 找不到值**
什么是对象？
对象 你就给他想象成一块布 能包很多东西，对象是用来包数据的，函数就是用来包行为的。

==if条件判断==
语法：
```
    // if(条件){
    //     // 十九执行
    // }else if(条件2){
    //     // 条件2执行
    // }else{
    //     // 执行语句
    // }

```
案例：
```

    // if(typeof(bl) == "number"){
    //     console.log("变量是一个数字");
    //
    // }else if(typeof(bl) == "string"){
    //     console.log("变量是一个字符串");
    // }else if(typeof(bl) == "boolean"){
    //     console.log("变量是一个布尔值");
    //
    // }

```
==for循环==
语法：
```
    // for(var i=0;i<10;i = i + 1){
    //     // 循环体
    //
    //     console.log(i);
    //
    // }

```
**在一行输出0-9 数字加数字还是数字 但是 字符串加字符串 连接字符串 字符串加数字 字符串**
案例：
```
    // var str = "";
    // for(var i=0;i<10;i = i + 1){
    //     str = str + i
    // }
    //
    // console.log(str);


```
==字符串的拼接==
```

    // var s1 = "木瓜太香";
    //
    // var s2 = "苹果太大";
    //
    // var sumStr = s1 + "||" + s2;
    // console.log(sumStr);

```
==方式二：模板字符串==
```
// var str = `${s1}||${s2}fdsfdsfs`;
    
    // console.log(str);
    // var n1 = 123;
    //
    //
    // var str = `发送到${s1}范德萨范
    //     ${n1}德萨发生的`
    // console.log(str);

```
==数据转换==
```
    // var n1 = 123;
    //
    // var str = n1 + "";
    //
    // var str2 = n1.toString(); // 很多数据类型都有 toString 方法 就是返回当前调用者的字符串表示
    //
    //
    // console.log(str2);
    //
    // console.log(str.toString());
    //
    // console.log(true.toString());
    
    // console.log(String(123));

```
案例：九九乘法表的实现
```
<script>
          var str="";
          for (var i=1;i<=9;i++){

              for(var j=i;j<=9;j++){
                  str=str+`${i}*${j}=${i*j}\t`
              }
              // str=str+"\n\n";
              str=str+"<br/>"
          }
          // console.log(str);
          document.write(str)

</script>

```










