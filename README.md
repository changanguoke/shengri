

在线预览
http://119.23.212.211:8080/birthday-basic/
用户名：123 密码：123

模板介绍
修改密码
在当前目录下，有js/login.js文件：

//修改此处的123,123即可修改登录的用户名和密码
if(userName=="123" &&  pwd=="123"){
  event.preventDefault();
  $('form').fadeOut(500);
  $('.wrapper').addClass('form-success');
  setTimeout(function(){location.href="BirthdayCake.html";},2000);
}
替换memories页面文字和图片
以第三屏为例：

<!--第三屏-->

<div class="section">
    <!-- 下面两个div分别实现的左边那条轴和那个小球 -->
    <div class="timeline"></div>
    <div class="timepoint21"></div>
    <div class="ly-box21">
        <div class="ly-txt21">
            <!-- 这里更改日期 -->
            201X-1X-2X
        </div>
        <div class="ly-txt22">
          <!-- 这里更改内容，段落、换行用<p></p>包裹起来 -->
           <p> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</p>
           <p>XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</p>
        </div>
        <div class="ly-imgbox21">
          <!-- 这里更改图片，图片请先改好对应的名字并且放到img文件夹下面
              如果你不懂css，那么最好就裁剪图片至合适大小为止
              如果你会css，那么可以根据class名字去修改对应css的宽度设置-->
          <img class="ly-img21" src="img/2014.11.26-1.png">
        </div>
    </div>
    <div class="ly-triangle21"></div>

    <div class="ly-box22">
        <div class="ly-txt23">
          <!-- 与上面类似，不再多说 -->
            201X-1X-1X
        </div>
        <div class="ly-txt24">
            XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
        </div>
        <div class="ly-imgbox22">
          <img class="ly-img22" src="img/2014.12.19-1.png">
        </div>
    </div>
    <div class="ly-triangle22"></div>

     <div class="ly-box23">
        <div class="ly-txt25">
            201X-1X-2X
        </div>
        <div class="ly-txt26">
            XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
        </div>
        <div class="ly-imgbox23">
          <img class="ly-img23" src="img/2014.12.20-1.jpg">
        </div>
    </div>
    <div class="ly-triangle23"></div>
</div>
