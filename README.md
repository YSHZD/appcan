# appcan
# appcan
# appcan
# appcan


1.appcan 不支持es6（否则有些手机不支持）

2.appcan 极光推送（证书要对应）

3.appcan 在线打包时用的的插件可能要选择插件（比如打电话，文件下载，极光推送，友盟统计，微信分享等）

4.启动页 name : root 有可能被跳转重置 root 不起效果

5.苹果推送要配置 
<config desc="" type="ENTITLEMENTS">
  <entitlement type="apns"></entitlement>
</config> 

6.安卓打包应该选择压缩模式，输入框和键盘有'顶'的效果

7.建议不适用swiperjs的轮播图 （效果不好且不流畅，图片渲染延时等问题）用appcan自带的轮播组件

8.appcan 可以用flex布局 （毕竟比display:box更新）

9.很多用了 !imporant 调样式要注意

10.appcan 苹果手机最好别用window.location.href 跳转 页面会报错一连串字符 用appcan自带的页面跳转








 弹性布局 
 display:-webkit-box;
 父容器的属性：
    -webkit-box-orient: vertical;
    设置该属性可以使子容器从上到下垂直排列

    -webkit-box-direction: reverse;
    子容器在水平方向从右向左(就是说最右边的元素排在最左边),垂直方向从下向上(最下面的在最上面)
    
    -webkit-box-align: start | end | center | stretch
    父容器水平排列下 start:上,center:中,end:下,stretch:子容器不设置高度或高度为auto时,子容器会拉伸的和父容器一样高,设置高度同start
    父容器垂直排列下 start:左,center:中,end:右,stretch:子容器不设置宽度或宽度为auto时,子容器会拉伸的和父容器一样宽,设置宽度同start

    -webkit-box-pack: start | end | center | justify
    父容器水平排列下 start:左,center:中,end:右,justify:水平等分父容器宽度
    父容器垂直排列下 start:上,center:中,end:下,justify:水平等分父容器高度
    
    -webkit-box-flex: 1;
    定义子容器占的比例, 具体计算规则,父容器-定宽,剩余的按比例等分。


git init

git remote add origin url

git config --global user.name ''

git config --global user.email ''

git fetch origin master :ysh

git diff ysh

git merge ysh

git add .

git commit -m "..."

git push -u origin master
