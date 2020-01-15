<h1 align='center'><font color='#2780e3'>  cnblogsUI </font></h1>

>

## 介绍

> 自己的博客园的样式，借鉴了大家的东西，欢迎大家使用。

## 示例

博客地址：[https://www.cnblogs.com/fsh001/](https://www.cnblogs.com/fsh001/)

![20200115130156.png](https://i.loli.net/2020/01/15/1Iol6u9gF4XfqYU.png)

## 功能

* :candy: 左上角的github链接功能
* :apple: 左下角的音乐播放器
* :lemon: 右边悬挂猫置顶按钮
* :watermelon: 顶部自定义页签图片
* :melon: 右侧自定义头像
* :pineapple: 定制评论样式
* :tomato: 定制背景图片
* :tangerine: 鼠标点击烟花
* :grapes: 鼠标点击小秘密
* :peach: 留言板功能
* :pear: 友链功能

## 食用方法

* 使用BlueSky皮肤
* 申请使用JS权限

#### 页面定制CSS代码
```css
/*复制按钮*/
.cnblogs-markdown pre {
  position: relative;
}
.cnblogs-markdown pre > span {
  position: absolute;
  top: 0;
  right: 0;
  border-radius: 2px;
  padding: 0 10px;
  font-size: 12px;
  background: rgba(0, 0, 0, 0.4);
  color: #fff;
  cursor: pointer;
}
.cnblogs-markdown pre > .copyed {
  background: #67c23a;
}

/* GitHub Cornor */
 .github-corner :hover .octo-arm {
 animation: octocat-wave 560ms ease-in-out;
 }
 @media (max-width: 991px) {
 .github-corner >svg {
 fill: #fff !important;
 color: #222 !important;
 }
 .github-corner .github-corner:hover .octo-arm {
 animation: none;
 }
 .github-corner .github-corner .octo-arm {
 animation: octocat-wave 560ms ease-in-out;
 }
 }
 @-moz-keyframes octocat-wave {
 0%, 100% {
 -webkit-transform: rotate(0);
 -moz-transform: rotate(0);
 -ms-transform: rotate(0);
 -o-transform: rotate(0);
 transform: rotate(0);
 }
 20%, 60% {
 -webkit-transform: rotate(-25deg);
 -moz-transform: rotate(-25deg);
 -ms-transform: rotate(-25deg);
 -o-transform: rotate(-25deg);
 transform: rotate(-25deg);
 }
 40%, 80% {
 -webkit-transform: rotate(10deg);
 -moz-transform: rotate(10deg);
 -ms-transform: rotate(10deg);
 -o-transform: rotate(10deg);
 transform: rotate(10deg);
 }
 }
 @-webkit-keyframes octocat-wave {
 0%, 100% {
 -webkit-transform: rotate(0);
 -moz-transform: rotate(0);
 -ms-transform: rotate(0);
 -o-transform: rotate(0);
 transform: rotate(0);
 }
 20%, 60% {
 -webkit-transform: rotate(-25deg);
 -moz-transform: rotate(-25deg);
 -ms-transform: rotate(-25deg);
 -o-transform: rotate(-25deg);
 transform: rotate(-25deg);
 }
 40%, 80% {
 -webkit-transform: rotate(10deg);
 -moz-transform: rotate(10deg);
 -ms-transform: rotate(10deg);
 -o-transform: rotate(10deg);
 transform: rotate(10deg);
 }
 }
 @-o-keyframes octocat-wave {
 0%, 100% {
 -webkit-transform: rotate(0);
 -moz-transform: rotate(0);
 -ms-transform: rotate(0);
 -o-transform: rotate(0);
 transform: rotate(0);
 }
 20%, 60% {
 -webkit-transform: rotate(-25deg);
 -moz-transform: rotate(-25deg);
 -ms-transform: rotate(-25deg);
 -o-transform: rotate(-25deg);
 transform: rotate(-25deg);
 }
 40%, 80% {
 -webkit-transform: rotate(10deg);
 -moz-transform: rotate(10deg);
 -ms-transform: rotate(10deg);
 -o-transform: rotate(10deg);
 transform: rotate(10deg);
 }
 }
 @keyframes octocat-wave {
 0%, 100% {
 -webkit-transform: rotate(0);
 -moz-transform: rotate(0);
 -ms-transform: rotate(0);
 -o-transform: rotate(0);
 transform: rotate(0);
 }
 20%, 60% {
 -webkit-transform: rotate(-25deg);
 -moz-transform: rotate(-25deg);
 -ms-transform: rotate(-25deg);
 -o-transform: rotate(-25deg);
 transform: rotate(-25deg);
 }
 40%, 80% {
 -webkit-transform: rotate(10deg);
 -moz-transform: rotate(10deg);
 -ms-transform: rotate(10deg);
 -o-transform: rotate(10deg);
 transform: rotate(10deg);
 }
 }
/* 背景图片 */
body {
color: #000;
background: url(https://i.loli.net/2020/01/14/hGIkXvLjCTo61ea.jpg
) fixed;
background-size: 100%;
background-repeat: no-repeat;
font-family: "Helvetica Neue",Helvetica,Verdana,Arial,sans-serif;
min-height: 101%;
}
/*评论区*/
#commentform_title, .feedback_area_title {font: normal normal 16px/35px"Microsoft YaHei";margin: 10px 0 30px;border-bottom: 2px solid #ccc;background-image: none;padding: 0;border-bottom: 0;}
#commentform_title:after, .feedback_area_title:after {content: '';display: block;width: 100%;text-align: center;position: relative;bottom: 16px;left: 110px;border-bottom: 1px dashed #e9e9e9;}
#tbCommentAuthor {padding-left: 10px;color: #555;border: 1px solid #ddd;border-radius: 3px;-moz-border-radius: 3px;-webkit-border-radius: 3px;width: 320px;height: 20px;background: #fff;}
.commentbox_title {width: 100%;}
div.commentform p{margin-bottom: 20px}
textarea#tbCommentBody {width: calc(100% - 20px);border-radius: 10px;outline: 0;padding: 10px;height: 200px;position: relative;background: #fff url(https://images.cnblogs.com/cnblogs_com/elkyo/1566714/o_comment-bg.png);background-size: contain;background-repeat: no-repeat;background-position: right;resize: vertical;}
/*评论列表*/
.feedbackItem {margin-top: 30px;}
.feedbackListSubtitle {clear: both;color: #a8a8a8;padding: 8px 5px;}
.feedbackManage {width: 200px;text-align: right;float: right;}
.feedbackListSubtitle a:link, .feedbackListSubtitle a:visited, .feedbackListSubtitle a:active {color: #777;font-weight: 450;}
.louzhu {background: transparent url(/images/icoLouZhu.gif) no-repeat scroll right top;padding-right: 16px;}
.feedbackCon {border-bottom: 1px solid #EEE;padding: 10px 20px 10px 5px;min-height: 35px;_height: 35px;margin-bottom: 1em;line-height: 1.5;}
.comment-avatar {width: 48px;height: 48px;border: 1px solid #dcd6b3;padding: 3px;border-radius: 50%;-webkit-transition: all .6s ease-out;-moz-transition: all .5s ease-out;-ms-transition: all .5s ease-out;-o-transition: all .5s ease-out;transition: all .5s ease-out;}
.blog_comment_body {display: inline-block;width: 70%;margin-left: 15px;vertical-align: initial!important;font-family: Lato, Helvetica, Arial, sans-serif;}
.comment_vote {padding-right: 10px;}
.comment_vote a {color: #999;}
.blog_comment_body a {color: #2daebf;}
.comment-avatar:hover {transform: rotateZ(360deg);}
#comment_nav{padding-top: 10px;}
.blog_comment_body img {max-width: 100px;}
/*提交评论*/
.comment_btn {width: 180px;height: 38px;padding: 8px 20px;text-align: center;font-size: 14px;color: #fff;border: 0;background: #7396a7 !important;border-radius: 3px;-moz-border-radius: 3px;-webkit-border-radius: 3px;-webkit-transition: all .4s ease;-moz-transition: all .4s ease;-o-transition: all .4s ease;-ms-transition: all .4s ease;transition: all .4s ease;cursor: pointer;display: inline-block;vertical-align: middle;outline: 0;text-decoration: none;}
.comment_btn:hover {background: #8cb7cc!important;}
p#commentbox_opt {text-align: center;}
/*移除广告*/
<!--去广告-->
#ad_t2,#cnblogs_c1,#under_post_news,#cnblogs_c2,#under_post_kb {display:none;!important}
.c_ad_block {
    display: none !important;
}
#ad_t2{
   display: none !important;
}
```

#### 博客侧边栏公告

```HTML
<!-- 头像 -->
<a href="https://www.cnblogs.com/fsh001">
<img height='150' width='200' src="https://i.loli.net/2020/01/14/bf9nj4x1C6HWZXs.png">
</a>
```

#### 页首HTML代码

```HTML
<!-- 上吊的猫 -->
<script type="text/javascript" src="https://blog-static.cnblogs.com/files/fsh001/szgotop.js"></script>
<link rel="stylesheet" type="text/css" href="https://blog-static.cnblogs.com/files/fsh001/szgotop.css" />
<div class="back-to-top cd-top faa-float animated cd-is-visible" style="top: -999px;"></div>
<!-- github页角 -->
<a href="https://github.com/cuttlin" class="github-corner" target="_blank" title="Follow me on GitHub" aria-label="Follow me on GitHub">
      <svg width="60" height="60" viewBox="0 0 250 250" style="fill:#151513; color:#fff; z-index: 999999; position: fixed; top: 0; border: 0; left: 0; transform: scale(-1, 1);" aria-hidden="true">
        <path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path><path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2" fill="currentColor" style="transform-origin: 130px 106px;" class="octo-arm"></path>
    <path d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z" fill="currentColor" class="octo-body"></path>
      </svg>
</a>
/* 自定义评论区 */
<link rel="stylesheet" href="https://blog-static.cnblogs.com/files/elkyo/OwO.min.css" />
<script src="https://blog-static.cnblogs.com/files/elkyo/OwO.min.js"></script>
<script>
/*文章评论*/
var le = $(".feedbackItem").length
for(var i = 0;i < le;i++){
  var src = $(".feedbackItem").eq(i).find(".feedbackCon").find("span").text()
  $(".feedbackCon").eq(i).prepend('<img class="comment-avatar" src="'+$.trim(src)+'">')
}
$("#tbCommentBody").attr("placeholder","请乖乖填写哦！ ...")
$("#tbCommentBody").after('<div class="OwO" onclick="load_face(this)"><div class="OwO-logo"><span>OωO<space><space>表情</span></div></div>')
var load_face = function(a){
  var OwO_demo = new OwO({
      logo: 'OωO表情',
      container: document.getElementsByClassName('OwO')[0],
      target: document.getElementById('tbCommentBody'),
      api: 'https://miluluyo.github.io/OwO.json',
      position: 'down',
      width: '70%',
      maxHeight: '250px'
  });
  a.classList.add('OwO-open');
  a.onclick=null
}
$("#commentbox_opt").nextAll().remove()
$("#btn_comment_submit").val("提交评论 (Ctrl + Enter)")
</script>
```

#### 页脚HTML代码

```HTML
<!-- 复制按钮 -->
<script src="https://cdn.bootcss.com/clipboard.js/2.0.4/clipboard.min.js"></script>
<script src="https://blog-static.cnblogs.com/files/wuliytTaotao/cp.js"></script>
<!-- 音乐 -->
 <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aplayer@1.10.0/dist/APlayer.min.css">
 <script src="https://blog-static.cnblogs.com/files/yjlaugus/APlayer.min.js"></script>
 <div id="aplayer" class="aplayer"  data-id="3192089837" data-server="netease" data-type="playlist" data-fixed="true" data-listfolded="true" data-order="random" data-theme="#F58EA8"></div>
 <script src="https://unpkg.com/meting@1.2/dist/Meting.min.js"></script>
<!-- 点击冒点 -->
<canvas width="1777" height="841" style="position: fixed; left: 0px; top: 0px; z-index: 2147483647; pointer-events: none;"></canvas><script src="https://blog-static.cnblogs.com/files/elkyo/mouse-click.js"></script>
<!-- 点击文字 -->
<script type="text/javascript">
/* 鼠标特效 */
var a_idx = 0;
jQuery(document).ready(function($) {
    $("body").click(function(e) {
        var a = new Array("❤烤猪蹄❤","❤烧排骨❤","❤可乐鸡翅❤","❤大火锅❤","❤烤羊蹄❤","❤大烤鱼❤","❤麻辣虾❤","❤冰阔落❤","❤好好吃呀！❤");
        var $i = $("<span></span>").text(a[a_idx]);
        a_idx = (a_idx + 1) % a.length;
        var x = e.pageX,
        y = e.pageY;
        $i.css({
            "z-index": 999999999999999999999999999999999999999999999999999999999999999999999,
            "top": y - 20,
            "left": x,
            "position": "absolute",
            "font-weight": "bold",
            "color": "rgb("+~~(255*Math.random())+","+~~(255*Math.random())+","+~~(255*Math.random())+")"
        });
        $("body").append($i);
        $i.animate({
            "top": y - 180,
            "opacity": 0
        },
        1500,
        function() {
            $i.remove();
        });
    });
    //设置页面底部
    document.getElementById("footer").innerHTML="Copyright ©2020 帅气的fsh001! <br /> ❤比心";
    //移除下面好文要顶等按钮
    var grc = document.getElementById("green_channel");
    
});
</script>
<script type="text/javascript" language="javascript">
　　//Setting ico for cnblogs设置新的标签页图标
　　var linkObject = document.createElement('link');
　　linkObject.rel = "shortcut icon";
　　linkObject.href = "https://i.loli.net/2020/01/14/ik5yO4lf8ZGomMq.png";
　　document.getElementsByTagName("head")[0].appendChild(linkObject);
    //添加自定义按钮
    var uli = document.getElementById("navList");
    var cli = document.createElement("li");
    cli.innerHTML = "<a href='https://www.cnblogs.com/fsh001/articles/12195239.html'>留言板</a>";
    uli.appendChild(cli);
    cli = document.createElement("li");
    cli.innerHTML = "<a href='#'>友链</a>";
    uli.appendChild(cli);
    
    
</script>

```