# onload_animation
H5页面动画，用于加载整个动画所需要的图片资源
动画是液体逐渐充满瓶子，下面有数字显示进度。
原生js+css3 keyframes动画写的，但也基于zepto。

主要原理是，一个定时器是假的，这个定时器可以设置自己想要的液体填充的时间，在这个定时器中，改变液体图片的bottom属性。
真正的加载时间可能只有几毫秒，在另外的定时器中执行
