# animate.css-Instructions
animate.css手册
以下样式直接以class的形式写到元素上即可，注意一定要额外加上一个class为animated的类，否则无效，如<div class="animated flash"></div>
某些效果的表现受元素位置的影响，尤其是靠近边框的时候

Attention Seekers / 关注者 <br>

bounce / 上下弹（类似于皮球掉地上）<br>
flash/一闪一闪<br>
pulse/慢慢颤抖放大再缩小<br>
rubberBand/橡皮筋（拉扁再恢复）<br>
shake/左右摇一摇（同一水平方向）<br>
swing/摆动（挂在墙上的东西摆动了一下）<br>
tada/
wobble/摆动（类似于抓在手上的竹签顶端被拨弄了一下的晃动）<br>
jello/果冻（以四边形的方式拉动晃晃）<br>
Bouncing Entrances / 进入（有晃动效果）<br>

bounceIn/放大式弹入 <br>
bounceInDown/从上方掉入，落地的时候弹一弹<br>
bounceInLeft/从左边进入，到目的地的时候晃一晃<br>
bounceInRight/从右边进入，到目的地的时候晃一晃<br>
bounceInUp/从下方进入，到目的地的时候晃一晃<br>
Bouncing Exits / 离开（有晃动效果）<br>

bounceOut/离开式弹出 <br>
bounceOutDown/晃一晃，向下离开<br>
bounceOutLeft/晃一晃，向左离开<br>
bounceOutRight/晃一晃，向右离开<br>
bounceOutUp/晃一晃，向上离开<br>
Fading Entrances / 淡入<br>

fadeIn/淡入<br>
fadeInDown/由上向下淡入<br>
fadeInDownBig/大幅度由上向下淡入（从浏览器上边进入）<br>
fadeInLeft/由左向右淡入<br>
fadeInLeftBig/大幅度由左向右淡入（从浏览器左边进入）<br>
fadeInRight/由右向左淡入<br>
fadeInRightBig/大幅度由右向左淡入（从浏览器右边进入）<br>
fadeInUp/由下向上淡入<br>
fadeInUpBig/大幅度由下向上淡入（从浏览器底边进入）<br>
Fading Exits / 淡出<br>

fadeOut/淡出<br>
fadeOutDown/由上向下淡出<br>
fadeOutDownBig/大幅度由上向下淡出（从浏览器下边淡出）<br>
fadeOutLeft/由右向左淡出<br>
fadeOutLeftBig/大幅度由右向左淡出（从浏览器左边淡出）<br>
fadeOutRight/由左向右淡出<br>
fadeOutRightBig/大幅度由左向右淡出（从浏览器右边淡出）<br>
fadeOutUp/由下向上淡出<br>
fadeOutUpBig/大幅度由下向上淡出（从浏览器上边进入）<br>
Flippers / 翻转<br>

flip/翻转<br>
flipInX/以X轴翻转淡入<br>
flipInY/以Y轴翻转淡入<br>
flipOutX/以X轴翻转淡出<br>
flipOutY/以Y轴翻转淡出<br>
Lightspeed / 光速（有刹不住车的感觉）<br>

lightSpeedIn/光速淡入<br>
lightSpeedOut/光速淡出<br>
Rotating Entrances / 旋转淡入<br>

rotateIn/旋转淡入<br>
rotateInDownLeft/以左下角为原点正角度旋转淡入<br>
rotateInDownRight/以右下角为原点正角度旋转淡入<br>
rotateInUpLeft/以左下角为原点负角度旋转淡入<br>
rotateInUpRight/以右下角为原点负角度旋转淡入<br>
Rotating Exits / 旋转淡出<br>

rotateOut/旋转淡出<br>
rotateOutDownLeft/以左下角为原点正角度旋转淡出<br>
rotateOutDownRight/以右下角为原点正角度旋转淡出<br>
rotateOutUpLeft/以左下角为原点负角度旋转淡出<br>
rotateOutUpRight/以右下角为原点负角度旋转淡出<br>
Sliding Entrances / 滑动进入<br>

slideInUp/由下向上滑动（由下方到原点）<br>
slideInDown/由上向下滑动（由上方到原点）<br>
slideInLeft/由左向右滑动（由左边到原点）<br>
slideInRight/由右向左滑动（由右边到原点）<br>
Sliding Exits / 滑动退出（不消失）<br>

slideOutUp/由下向上滑动（由原点向上）<br>
slideOutDown/由上向下滑动（由原点向下）<br>
slideOutLeft/由左向右滑动（由原点到左边）<br>
slideOutRight/由右向左滑动（由原点到右边）<br>
Zoom Entrances缩放（由小变大，先缩放后位置移动）（自己测试无效）<br>

zoomIn/缩放（由小变大）<br>
zoomInDown/由上向下缩放变大<br>
zoomInLeft/由左向右缩放变大<br>
zoomInRight/由右向左缩放变大<br>
zoomInUp/由下向上缩放变大<br>
Zoom Exits缩放（由大变小，先缩放后位置移动）（自己测试无效）<br>

zoomOut/缩放（由大变小）<br>
zoomOutDown/由原来的位置缩放向下直至消失<br>
zoomOutLeft/由原来的位置缩放向左直至消失<br>
zoomOutRight/由原来的位置缩放向右直至消失<br>
zoomOutUp/由原来的位置缩放向上直至消失<br>
Specials / 特别的<br>

hinge/类似于钉在墙上的画框只剩一个钉子掉下来的感觉<br>
rollIn/从左向右180度旋转扔进来<br>
rollOut/从右向左180度旋转扔出去<br>

为什么不使用jQuery?<br>
大家都知道jQuery中有一个Animate可以制作动画效果，那为什么不使用jQuery的Animate呢？主要因为CSS3的animate是一个很棒的属性，他不像jQuery的Animate靠硬件来加速。而且我们还可以使用Modernizr来检测浏览器对CSS3的animate支持程度，然后使用jQuery的Animate来制作其他浏览器不支技的动画效果。<br>

http://daneden.github.io/animate.css/ 官方github网址<br>
http://www.w3cplus.com/css3/animate-css  分析说明<br>
需配合wow.js使用<br>
wow.js使用前记得在引用后加<code>new WOW().init();</code>
