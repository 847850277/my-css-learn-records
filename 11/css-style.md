# style标签写在body前和body后的区别是什么
    
        
        在HTML4的时候，不应该把style放在body中间。
    
        在浏览器在渲染页面时DOM和CSSDOM是并行的，然后两者结合形成RENDER TREE显示页面。
        从直觉上来说，style写在body前不会对DOM的渲染进行阻塞；而写在body内会对DOM渲染进行
        阻塞。会产生FOUC(Flash of Unstyled Content)的现象，即一瞬间的白屏或者样式的突然
        变化(重新渲染Render Tree)

        在W3C的HTML5.2的定义中对于style标签的定义允许将style放在body中

```CSS
Contexts in which this element can be used:
Where metadata content is expected.
In a noscript element that is a child of a head element.
In the body, where flow content is expected.

```