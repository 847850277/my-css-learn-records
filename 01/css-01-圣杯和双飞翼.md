# 圣杯布局和双飞翼布局的理解和区别，并用代码实现

    圣杯布局和双飞翼布局解决的问题一样，就是两边顶宽，中间自适应的三栏布局
    中间栏要是放在文档流前面以优先渲染

    区别：
        圣杯布局，为了中间div内容不被遮挡，将中间div设置了左右padding-left和padding-right后，
    将左右两个div用相对布局position:relative 分别配合right和left属性，以便左右两栏div移动后不遮挡
    中间div。
        双飞翼布局，为了中间div不被遮挡，直接在中间div内部创建子div放置内容，在该子div里面用margint-left
    和margin-right为左右两栏div留出位置。
