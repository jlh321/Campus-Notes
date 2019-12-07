# JavaScript(V8 6.0.0) 刷题输入输出方法

## 1 处理单行输入问题

计算a+b的和，每行包含两个整数a和b

对于每行输入对应输出一行a和b的和

输入

1 5

输出

6

```javascript
//readLine得到的是字符串，需要用parseInt转换为数字
while(line=readline()){
    var lines = line.split(' ');
    var a = parseInt(lines[0]);   
    var b = parseInt(lines[1]);
    console.log (a+b);   //用console.log或者print输出
}

```

##  2 处理多行输入输出

输入

4
2 6 4 3


```javascript
var num=readline();
var arr=readline().split(' ');
```

