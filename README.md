# animate.css-Instructions
animate.css手册
以下样式直接以class的形式写到元素上即可，注意一定要额外加上一个class为animated的类，否则无效，如<div class="animated flash"></div>
某些效果的表现受元素位置的影响，尤其是靠近边框的时候

Attention Seekers / 关注者

bounce / 上下弹（类似于皮球掉地上）
flash/一闪一闪
pulse/慢慢颤抖放大再缩小
rubberBand/橡皮筋（拉扁再恢复）
shake/左右摇一摇（同一水平方向）
swing/摆动（挂在墙上的东西摆动了一下）
tada/
wobble/摆动（类似于抓在手上的竹签顶端被拨弄了一下的晃动）
jello/果冻（以四边形的方式拉动晃晃）
Bouncing Entrances / 进入（有晃动效果）

bounceIn/放大式弹入
bounceInDown/从上方掉入，落地的时候弹一弹
bounceInLeft/从左边进入，到目的地的时候晃一晃
bounceInRight/从右边进入，到目的地的时候晃一晃
bounceInUp/从下方进入，到目的地的时候晃一晃
Bouncing Exits / 离开（有晃动效果）

bounceOut/离开式弹出
bounceOutDown/晃一晃，向下离开
bounceOutLeft/晃一晃，向左离开
bounceOutRight/晃一晃，向右离开
bounceOutUp/晃一晃，向上离开
Fading Entrances / 淡入

fadeIn/淡入
fadeInDown/由上向下淡入
fadeInDownBig/大幅度由上向下淡入（从浏览器上边进入）
fadeInLeft/由左向右淡入
fadeInLeftBig/大幅度由左向右淡入（从浏览器左边进入）
fadeInRight/由右向左淡入
fadeInRightBig/大幅度由右向左淡入（从浏览器右边进入）
fadeInUp/由下向上淡入
fadeInUpBig/大幅度由下向上淡入（从浏览器底边进入）
Fading Exits / 淡出

fadeOut/淡出
fadeOutDown/由上向下淡出
fadeOutDownBig/大幅度由上向下淡出（从浏览器下边淡出）
fadeOutLeft/由右向左淡出
fadeOutLeftBig/大幅度由右向左淡出（从浏览器左边淡出）
fadeOutRight/由左向右淡出
fadeOutRightBig/大幅度由左向右淡出（从浏览器右边淡出）
fadeOutUp/由下向上淡出
fadeOutUpBig/大幅度由下向上淡出（从浏览器上边进入）
Flippers / 翻转

flip/翻转
flipInX/以X轴翻转淡入
flipInY/以Y轴翻转淡入
flipOutX/以X轴翻转淡出
flipOutY/以Y轴翻转淡出
Lightspeed / 光速（有刹不住车的感觉）

lightSpeedIn/光速淡入
lightSpeedOut/光速淡出
Rotating Entrances / 旋转淡入

rotateIn/旋转淡入
rotateInDownLeft/以左下角为原点正角度旋转淡入
rotateInDownRight/以右下角为原点正角度旋转淡入
rotateInUpLeft/以左下角为原点负角度旋转淡入
rotateInUpRight/以右下角为原点负角度旋转淡入
Rotating Exits / 旋转淡出

rotateOut/旋转淡出
rotateOutDownLeft/以左下角为原点正角度旋转淡出
rotateOutDownRight/以右下角为原点正角度旋转淡出
rotateOutUpLeft/以左下角为原点负角度旋转淡出
rotateOutUpRight/以右下角为原点负角度旋转淡出
Sliding Entrances / 滑动进入

slideInUp/由下向上滑动（由下方到原点）
slideInDown/由上向下滑动（由上方到原点）
slideInLeft/由左向右滑动（由左边到原点）
slideInRight/由右向左滑动（由右边到原点）
Sliding Exits / 滑动退出（不消失）

slideOutUp/由下向上滑动（由原点向上）
slideOutDown/由上向下滑动（由原点向下）
slideOutLeft/由左向右滑动（由原点到左边）
slideOutRight/由右向左滑动（由原点到右边）
Zoom Entrances缩放（由小变大，先缩放后位置移动）（自己测试无效）

zoomIn/缩放（由小变大）
zoomInDown/由上向下缩放变大
zoomInLeft/由左向右缩放变大
zoomInRight/由右向左缩放变大
zoomInUp/由下向上缩放变大
Zoom Exits缩放（由大变小，先缩放后位置移动）（自己测试无效）

zoomOut/缩放（由大变小）
zoomOutDown/由原来的位置缩放向下直至消失
zoomOutLeft/由原来的位置缩放向左直至消失
zoomOutRight/由原来的位置缩放向右直至消失
zoomOutUp/由原来的位置缩放向上直至消失
Specials / 特别的

hinge/类似于钉在墙上的画框只剩一个钉子掉下来的感觉
rollIn/从左向右180度旋转扔进来
rollOut/从右向左180度旋转扔出去

为什么不使用jQuery?
大家都知道jQuery中有一个Animate可以制作动画效果，那为什么不使用jQuery的Animate呢？主要因为CSS3的animate是一个很棒的属性，他不像jQuery的Animate靠硬件来加速。而且我们还可以使用Modernizr来检测浏览器对CSS3的animate支持程度，然后使用jQuery的Animate来制作其他浏览器不支技的动画效果。

http://daneden.github.io/animate.css/ 官方github网址
http://www.w3cplus.com/css3/animate-css  分析说明
