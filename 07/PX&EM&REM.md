# PX、EM、REM的区别

[链接](https://github.com/haizlin/fe-interview/issues/29)

            px、em、rem都是计量单位，都能表示尺寸，但是有所不同，而且各有各的优缺点
        
        px表示"绝对尺寸"(并非真正的绝对),实际上就是css中定义的像素，利用px设置字体大小
        及元素宽高等比较稳定精确。px的缺点是其不能适应浏览器缩放时产生变化，因此一般不用于
        响应式网站。
        
        em表示相对尺寸，其相对于当前对象内文本的font-size(如果当前对象内文本的font-size计量单位)
        也是em，则当前对象内文本的fot-size的参考对象为父元素文本font-size)。使用em可以较好的响应
        设备尺寸变化，但是在进行元素设置时都需要知道父元素文本的font-size及当前对象内文本的font-size,
        如有遗漏可能会导致错误。

        rem也表示相对尺寸，其参考对象为根元素的font-size，因此只需要确定这一个font-size。