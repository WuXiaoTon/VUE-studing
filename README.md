# VUE-studing

##  :coffee: 写在前面
    此项目写于本人大四上半学期实习期，在学校学艺不精、JS掌握情况普通，书写格式紊乱。
    此项目更多的是个人练习，通过实验一点点掌握技巧。
    每日的发现与疑惑会记在这里。
    * 本人生性絮叨，这些文本与代码可能看着让人十分火大。
    
## :thought_balloon: 笔记

### [1.属性-基本属性填入值](https://github.com/WuXiaoTon/VUE-studing/blob/master/html/test1.html)
    总结：简单使用{{}}、new VUE({})中el（填#id）、data（填键值对）、methods（函数）三个属性。
    发现：
      1.函数中引用值为字符串，直接加为字符串拼接
此处引出问题：若为减会怎样
        11.20更新：测试后证明减法为数值计算
### [2.模板语法](https://github.com/WuXiaoTon/VUE-studing/blob/master/html/test2.html)
    总结：练习了最基本的几种符号。
    1.v-bind:class="属性名"  简写为:class="属性名"
    2.v-bind:class="{'值1':属性1,'值2':属性2}"
    3.{{计算式}}
    4.{{属性?'值1':'值2'}}
    5.{{属性.split('').reverse().join('')}}
    6.v-if='seen'
    7.v-on:click='方法名'  简写为@click='方法名'
    8.v-model="属性" {{message}}双向绑定
    9.{{属性 | 过滤器名}}
    发现：
        1.VUE是按顺序读的，大div里套小div时，那个id的vue先被读到，就绑定哪个VUE的
        2.过滤器和方法（函数）在VUE里不是一个东西
        
