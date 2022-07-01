# 说下line-height三种赋值方式的区别

            
            line-height是具有继承性的，如果直接在某个元素上直接使用line-height,那么这三种写法是没有区别的，
        比如给所有的p标签添加行高属性。最后效果是一样的。这三种方式的区别在于，给父元素设置行高的时候子元素的继承
        方式。
        例如，我们有一个父div类名称为parent，另一个父div的类名为parent2，均包含类一个类名为child的子div。
        
        继承line-height的时候，带单位的先计算再继承，不带单位的直接继承。
        
```CSS
p{line-height: 1.5em;}
p{line-height: 1.5;}
p{line-height: 150%;}

```
