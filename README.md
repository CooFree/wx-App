# wx-App


微信小程序开发实战<br>
http://lib.csdn.net/wechat/node/18

大量代码  开源库<br>
https://github.com/opendigg/awesome-github-wechat-weapp


CSS Flex弹性盒布局<br>
http://www.jianshu.com/p/07e0c16a4ff5#<br>
http://www.jianshu.com/p/baf4fc79374b<br>
http://www.ruanyifeng.com/blog/2015/07/flex-examples.html


```
微信小程序 wxml中的属性记录
1. view 标签中的属性

 style 中的参数
    margin-top:10px;  （向上距离）        
    display : flex;  （display : flex 容器声明）
    flex-direction:    (view中布局的方向)
          row;    （横向布局 ，从左到右）         
          column;    （垂直布局，布局从上往下）

          row-reverse; （横向布局 ，从右到左）   
          column-reverse;（垂直布局，布局从下到上）

    flex-wrap: (当布局一行里面的数据无法全部显示的时候，如何换行)

          nowrap;  (默认，不换行)

          wrap;  (换行，第一行在上面)

          wrap-reverse; (换行，第一行在下面)

    flex-flow: (是flex-direction和flex-wrap的简写，默认值是，row, nowrap)

          例子：flex-flow:row||nowrap;

    justify-content: (父布局对其中的子布局的对齐方式)

          flex-start;（左对齐）

          flex-end;（右对齐）

          center;（居中）

          space-between;（ 两端对齐，子控件之间的间隔等分）

          space-around;  （两侧，和子控件之间都有间隔，子控件的间隔是两个间隔的两倍）

    align-items:  (属性在交叉轴上如何对齐)

          flex-start;（交叉轴的起点对齐）

          flex-end;（交叉轴的终点对齐）

          center;（交叉轴的中点对齐）

          baseline;（项目第一行文字的基线对齐）

          stretch;（如果项目未设置高度或是设置为auto，将占满整个容器的高度）

    align-content:(子类里面有多行布局时的对齐方式，只有一个布局时，该属性不起作用)

          flex-start;（交叉轴的起点对齐）

          flex-end;（交叉轴的终点对齐）

          center;（交叉轴的中点对齐）

          space-between;（ 两端对齐，子控件之间的间隔等分）

          space-around;  （两侧，和子控件之间都有间隔，子控件的间隔是两个间隔的两倍

          stretch;（如果项目未设置高度或是设置为auto，将占满整个容器的高度）


    子布局中的属性

    order：（定义排序的顺序，数值越小排列约靠前，默认为0）

    flex-grow: (定义放大比例，就是剩下的空间，占的大小，相当于Android中的weight)

    flex-shrink:(定义缩小比例，当空间不够的时候，对项目进行缩小，和上面放大原理相同)

    align-self:(用来允许自己的布局和其他的子布局方式不同)

          flex-start;（交叉轴的起点对齐）

          flex-end;（交叉轴的终点对齐）

          center;（交叉轴的中点对齐）

          baseline;（项目第一行文字的基线对齐）

          stretch;（如果项目未设置高度或是设置为auto，将占满整个容器的高度）

 

    边距

    margin：

    margin: 20rpx 10rpx 25rpx 10rpx;  （如果提供了四个参数，将用在上，右，下，左的顺序上）

    margin: 20rpx; （如果只提供一个，就是作用在四个方向上）

    margin: 20rpx 10rpx; （提供两个，一个用于上下，一个用于左右）

    margin: 20rpx 10rpx 20rpx; (如果提供三个，第一个用于上，第二个用于左右，第三个用于下)

    如果两个相邻的都有margin，就会出现合并的现象，合并后取其中大的值

    margin-top,margin-right,margin-bottom,margin-left,分别对应上右下左的边距距离，可取值：auto/数值/百分比

    padding： 同上（margin）

    padding-top,padding-right,padding-bottom,padding-left,分别对应上右下左的内边距距离，可取值：auto/数值/百分比
```
