# jQuery-test
MY exercises of javasript and jquery
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Travel route</title>
<style>
body{
	font-family:'Arial', Gadget, sans-serif; 
	font-weight:900;
	line-height:34px;
	background-image:url(img/sub-back.jpg);
	}
.list{
	width:80%;
	margin:0 auto;
	background:#999;
	border-radius:10px;
	font-size:22px;
	padding:10px;
	}
h1{
	color:#eee;
	}
.tip{
	font-size:0.8em;
	font-weight:200;
	}
#header{
	width:40%;
	margin:0 auto;
	border-radius:15px;
	color:#eee;
	font-size:51px;
	line-height:51px;
	text-align:center;
	text-shadow: 5px 5px 0 rgba(130, 30, 30, 0.5);
	}
.title{
	 color:#fff;
	 width:666px; height:70px; margin:0 auto; 
	 border-radius:18px;
	}
</style>
</head>

<body>
<div id="canvas"></div>

<div class="route">
<div class="title"><h1 align="center" style="line-height:70px;">06.08&nbsp;&nbsp;&nbsp;&nbsp;Day 1：&nbsp;&nbsp;Start our travel!</h1></div>
<div class="list">
<p style="text-indent:80px;">-&nbsp;&nbsp;香港机场12:00</p>
<p style="text-indent:140px;">-&nbsp;&nbsp;酒店（地铁佐敦站）-吃饭</p>
<p style="text-indent:190px;">-&nbsp;&nbsp;尖沙咀（星光大道，天星小轮，维多利亚港，轮渡）<span class="tip">（尖沙咀站E出口或尖沙咀地铁弥敦道朝天星小轮码头 东是尖沙嘴观景长廊。再往东就是星光大道，）观赏幻彩咏香江（每晚8点）最佳地点。大概半个小时。</span></p>
<p style="text-indent:240px;">-&nbsp;&nbsp;太平山顶（缆车，凌霄阁）</p>
<p style="text-indent:295px;">-&nbsp;&nbsp;铜锣湾时代广场(我要的墨镜！)</p>
<p style="text-indent:355px;">-&nbsp;&nbsp;香港木的地酒店</p>
</div>
</div>
<br/>

<div class="route">
<div class="title"><h1 align="center" style="line-height:70px;">06.09&nbsp;&nbsp;&nbsp;&nbsp;Day 2：&nbsp;&nbsp;Find fun!</h1></div>
<div class="list">
<p style="text-indent:80px;">-海洋乐园</p>
<p style="text-indent:145px;">-&nbsp;&nbsp;香港仔-湾仔美食夜市</p>
<p style="text-indent:220px;">-&nbsp;&nbsp;香港木的地酒店</p>
</div>
</div>
<br/>

<div class="route">
<div class="title"><h1 align="center" style="line-height:70px;">06.10&nbsp;&nbsp;&nbsp;&nbsp;Day 3&nbsp;&nbsp;I love shopping!</h1></div>
<div class="list">
<p style="text-indent:80px;">-&nbsp;&nbsp;尖沙咀（龙城大药房，海港城）</p>
<p style="text-indent:140px;">-&nbsp;&nbsp;黄大仙<span class="tip">地铁到黄大仙站B2出闸，再步行约3分钟，门票免费，求签免费，解签20-30港币一次。</span></p>
<p style="text-indent:195px;">-&nbsp;&nbsp;旺角（美食夜市，波鞋街，女人街）</p>
<p style="text-indent:257px;">-&nbsp;&nbsp;酒吧</p>
<p style="text-indent:312px;">-&nbsp;&nbsp;香港木的地酒店</p>
</div>
</div>
<br/>

<div class="route">
<div class="title" style="width:65%;"><h1 align="center" style="line-height:70px; color:#fcc;">❤❤❤06.11&nbsp;&nbsp;&nbsp;&nbsp;Day 4：&nbsp;&nbsp;Happniess in the sea!❤❤❤</h1></div>
<div class="list">
<p style="text-indent:80px;">-&nbsp;&nbsp;❤大屿山（昂坪缆车）<span class="tip">地铁佐敦站乘荃湾线到荔景站，对面转乘东涌线至终点东涌站，全程40分钟。B出口出沿指示能找到昂坪360缆车站，乘缆下车徒步可达”昂坪市集”，再由昂坪市集步行10分钟，就可抵达大屿山天坛大佛。</span></p>
<p style="text-indent:140px;">-&nbsp;&nbsp;❤浅水湾（下海啦！）</p>
<p style="text-indent:195px;">-&nbsp;&nbsp;❤美丽，浪漫，晚餐❤</p>
<p style="text-indent:260px;">-&nbsp;&nbsp;❤愉景湾酒店</p>
</div>
</div>
<br/>

<div class="route">
<div class="title"><h1 align="center" style="line-height:70px;"><h1 align="center" style="line-height:70px;">06.12&nbsp;&nbsp;&nbsp;&nbsp;Day 5:&nbsp;&nbsp;Disney land!</h1></div>
<div class="list">
<p style="text-indent:80px; font-size:28px;">-&nbsp;&nbsp;迪!</p>
<p style="text-indent:145px; font-size:28px;">-&nbsp;&nbsp;士!</p>
<p style="text-indent:205px; font-size:28px;">-&nbsp;&nbsp;尼!</p>
<p style="text-indent:270px;">-&nbsp;&nbsp;愉景湾酒店</p>
</div>
</div>
<br/>

<div class="route">
<div class="title"><h1 align="center" style="line-height:70px;">Day 6:&nbsp;&nbsp;BYEBYE HONGKONG!</h1></div>
<div class="list">
<p style="text-indent:80px;">-&nbsp;&nbsp;金紫荆广场<span class="tip">如果从湾仔地铁站A5出口，按指示沿着天桥穿过出入境管理大楼，朝会展中心前行，大约要走十五分钟吧. 还有金紫荆广场东侧就是天星小轮码头，如果是住在九龙岛，应该坐车到尖沙咀天星码头，在码头左侧入口坐天星小轮到湾仔码头，出了码头按沿路指示到达。</span></p>
<p style="text-indent:140px;">-&nbsp;&nbsp;中环</p>
<p style="text-indent:195px;">-&nbsp;&nbsp;兰桂坊<span class="tip">花园道缆车总站出来后向（坡）下走，过马路，从教堂左转。顺高等法院继续向山下走。过麦当劳后，有一个大的十字路口，指向左转（兰桂坊），向上步行200米就是。全程大约700米，步行十分钟即可。不需要乘车。</span></p>
<p style="text-indent:250px;">-&nbsp;&nbsp;机场</p>
</div>
</div>
<br/>

<script src="http://cdn.bootcss.com/jquery/2.1.4/jquery.js"></script> 
<script src="js/protoclass.js"></script>
<script src='js/box2d.js'></script>
<script src='js/Main.js'></script>
<script src="js/TravelRoute.js"></script>
</body>
</html>
