# 实现单行文本居中和多行文本左对齐超出显示。


- 单行文本居中

```CSS

.single-text{
    width: 500px;    
    font-size: 18px;
    font-weight: bold;
    text-align: center;
    color: white;
    background-color: lightblue;
    display: box;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}


```


- 多行文本左对齐。

```CSS

.multi-text{
    
    width: 50%;
    height: 4.5rem;
    line-height:1.5;
    padding:20px;
    background:lightblue;
    overflow:hidden;
    position:relative;
    box-sizing: border-box;
    
    &::after {
        content:'...';
        height:1.5rem;
        position: absolute;
        bottom: 5px;
        right: 5px;
     }
}

```