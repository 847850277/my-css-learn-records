# 说说你对z-index的理解


            当网页上出现多个由绝对定位（position:absolute）或固定定位（position:fixed）所产生的浮动层时，必然就会产生一个问题，
        就是当这些层的位置产生重合时，谁在谁的上面呢？或者说谁看得见、谁看不见呢？这时候就可以通过设置z-index的值来解决，
        这个值较大的就在上面，较小的在下面。
            自己把这个值类比成PS中的图层概念。