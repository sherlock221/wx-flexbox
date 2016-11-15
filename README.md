### 基于微信的 flexbox布局工具

> 使用flexbox脚手架工具 很方便的帮助我们实现复杂布局,并且提升了页面代码的可读性.

  

![444444.png](http://upload-images.jianshu.io/upload_images/326507-9524cff38dfdea95.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
 <pre>

       <view class="fx-row fx-row-center">
                   <image src="" />
                   <view class="fx-auto">
                       <h3>标题</h3>
                       <p>内容</p>
                   </view>
                   <view>
                        <button>跳转</buton>
                   </view>
        </view>

 </pre>
 
 
  ![222.png](./imgs/双列换行.jpg)
   <pre>
   
       <view class="fx-row fx-wrap">
                  <view class="gird-50">
                      图片文字...
                  </view>
                  <view class="gird-50">
                      图片文字...
                  </view>
                  <view class="gird-50">
                      图片文字...
                  </view>
              </view>
              
   </pre>
   
    网格布局:
   ![gird.png](./imgs/栅格.png)  
   

[点击查看更多列表布局.....](./常用列表布局.md)



####快速使用

1. 拷贝 dist/flex.wxss 或 css 到项目中 引入
2. 书写布局代码:

                <view class="fx-row">
                    <view class="fx-1">1</view>
                    <view class="fx-3">3</view>
                </view>


####兼容性问题:
> 1. ios  ok
  2. android x5内核  ok
  3. 微信小程序 ok


####对齐方式
对齐方式遵循flexbox的标准
fx-row 为子元素横向排列
fx-column 为子元素竖向排列

横向排列:垂直方向的对齐策略:

类名 | 效果 | 原属性
------------ | -------------
fx-row-center | 垂直居中 |  center
fx-row-top |   顶部对齐 | flex-start
fx-row-bottom | 底部对齐 | flex-end
fx-row-stretch | 垂直拉满 | stretch
fx-row-baseline | 基线对齐 | baseline

横向排列:水平方向的对齐策略:

类名 | 效果 | 原属性
------------ | -------------
fx-row-left | 水平居左 |  flex-star
fx-row-middle |   水平居中 | center
fx-row-right | 靠右 | flex-end
fx-row-space-between | 均匀分布 | space-between
fx-row-space-around | 俩头分布 | baseline


竖向排列:垂直方向对齐策略
ps : 覆盖父元素的align-items属性，定义了单独的弹性子元素如何沿着侧轴排列

类名 | 效果 | 原属性
------------ | -------------
fx-col-center | 垂直居中 |  center
fx-col-top |   顶部对齐 | flex-start
fx-col-bottom | 底部对齐 | flex-end


竖向排列:水平方向对齐策略

类名 | 效果 | 原属性
------------ | -------------
fx-col-left | 水平居左 |  flex-star
fx-col-right |   水平居中 | center
fx-col-middle | 水平居右边 | flex-end
fx-col-space-between | 均匀分布 | space-between   
fx-col-space-around | 俩头分布 | baseline         



###网格布局支持

类名 | 效果                     
------------ | -------------            
col-5 | 5%的宽度 
col-10 | 10%的宽度 
col-15 | 15%的宽度
......

       





> 好东西需要你们的支持 动手点下star吧!