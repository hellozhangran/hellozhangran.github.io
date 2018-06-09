## Zhangran Blog

文章收集：

* [雅虎前端优化的35条军规](http://www.cnblogs.com/xianyulaodi/p/5755079.html)




思考题：


``` javascript
function Ran(){
    console.log('hello')
}

var ran = new Ran()
// 此刻ran得到的是什么 ？

function Ran(){
    return {
        name: 'zhangran'
    }
}

var ran = new Ran()
//此刻ran得到的是什么？

function Ran(){
    return 1
}

var ran = new Ran()
//此刻ran得到的是什么 ？
```