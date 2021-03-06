# 描述下所了解的图片格式和使用场景



| 图片格式 | 优点    | 缺点 | 适用场景 |
|----------|---------|------|----------|
| GIF        | GIF是动态的；支持无损压缩和透明度 | 详细的图片和写实摄影图片会丢失颜色信息；在大多数情况需下，无损压缩效果不如JPEG或PNG格式；GIF支持有限的透明度，没有半透明效果或者褪色效果   | 比较小的动态图标         |
| PNG        | PNG格式的图片是无损压缩图片，能在保证最不失真的情况下尽可能压缩图像文件的大小；图片质量高；色彩表现好；支持透明效果；提供锋利的线条和边缘，所以做出的LOGO等小图标效果会更好；更好的展示文字、颜色相近的图片 | 占用内存大，导致网页加载慢；对于需要高保真的较复杂的图像，虽然无损压缩，但文件较大，不使用在Web页面上   |主要用于小图标或者颜色简单对比强烈的小背景         |
| JPG        | 占用内存小，图片加载快 | JPG图片是有损压缩图片，有损压缩会使原始图片数据质量下降，即JPG会在压缩图片是降低品质  | 由于这种格式图片对色彩表现比较好，所以适用于色彩丰富的图片。主要用于摄像作用或者大的背景图等。不适合文字比较多的图片         |
| SVG        | SVG是矢量图形，不受像素影响，在不同平台上都表现良好；可以通过JS控制动画效果 | DOM比正常的图形慢，而且如果其节点多而杂，就更慢；不能与HTML内容集成   | 主要用于设计模型展示等         |
| WebP        | WebP格式，谷歌开发的一种旨在加快图片加载速度的图片格式。图片压缩体积大约只有JPEG的2/3，并能节省大量的服务器带宽和数据资源 | 相较编码JPEG文件，编码同样质量的WebP文件需要占用更多的计算资源，兼容性不好   | WebP既能有损压缩，又能无损压缩。将来可能是JPEG的替代品         |

