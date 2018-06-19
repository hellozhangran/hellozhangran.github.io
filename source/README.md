## Zhangran Blog

文章收集：

* [雅虎前端优化的35条军规](http://www.cnblogs.com/xianyulaodi/p/5755079.html)

* [写一个兼容AMD,CommandJS,全局变量的js库](https://75team.com/post/%E8%AF%91%E7%A5%9E%E9%A9%AC%E6%98%AFamd-commonjs-umd.html)

* [WebGL 技术储备指南](http://taobaofed.org/blog/2015/12/21/webgl-handbook)

* [CPU和GPU的区别](https://www.zhihu.com/question/19903344)

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

