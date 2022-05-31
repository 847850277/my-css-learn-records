# 在页面上隐藏元素的方法有哪些

[访问地址](https://github.com/haizlin/fe-interview/issues/8)


- 全局属性 hidden
  
            hidden: 布尔属性表示元素尚未或不再相关。例如，它可以用于隐藏在登陆过程
        完成之前无法使用的页面元素。浏览器不会渲染此类元素。不得使用此属性隐藏可以合法
        显示的内容
            这个方法的隐藏元素不会在页面中占据位置

- display: none
            
            这个属性会让元素在页面消失，不占据实际空间
          
- visible: hidden
            
            这个属性会让元素在页面中'隐身'，也就是说只是单纯看不见了，但是原来的空间仍然被该
        元素占据。

- 使用定位
    - 通过z-index
            
            position: absolute;让元素脱标，不占实际位置
            z-index: -1;使用层级隐藏在其他元素之下
            
    - 通过位置或者margin
            
            left: -500%、margin-left:-500%;让元素的位置在当前的可见区域之外

    - 使用transform
            
            必须配合position使用，让元素脱标，不然还会占据空间
    - 使用透明度
            
            调整为完全透明
    