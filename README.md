### 基于微信的 flexbox布局工具

> 使用flexbox脚手架工具 很方便的帮助我们实现复杂布局,并且提升了页面的可读性.

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

[更多列表布局](./常用列表布局.md)


#### 快速使用
1. 拷贝 dist/flex.wxss 或 css 到项目中 引入
2. 使用方式:  
<pre>
      <view class="fx-row">
                    <view class="fx-1">1</view>
                    <view class="fx-3">3</view>
           </view>
</pre>


### 常用列表布局
[常用列表布局](./常用列表布局.md)