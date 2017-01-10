/*------------------------------------------------------------------
[Master Stylesheet]

Project:	Profile For Blog
Version:	1.0.0
Last change:	--/--/--
Assigned to:	Song Vi Blogger
-------------------------------------------------------------------*/
/*------------------------------------------------------------------
[Table of contents]

1. Body
2. Header / #header
3. Navigation / #navbar
4. Content / #content
5. Left column / #leftcolumn
6. Right column / #rightcolumn
7. Footer / #footer
-------------------------------------------------------------------*/
@charset "utf-8";
@import "style.css";
@font-face {
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 400;
  src: local('Open Sans'), local('OpenSans'), url(/frontend/css/font/59ZRklaO5bWGqF5A9baEET8E0i7KZn-EPnyo3HZu7kw.woff) format('woff');
}
@font-face {
  font-family: 'Open Sans';
  font-style: normal;
  font-weight: 600;
  src: local('Open Sans Semibold'), local('OpenSans-Semibold'), url(/frontend/css/font/MTP_ySUJH_bn48VBG8sNSnwUvq1pQaUIDqPgpae5ItU.woff) format('woff');
}
@font-face {
  font-family: 'Open Sans Condensed';
  font-style: normal;
  font-weight: 300;
  src: local('Open Sans Cond Light'), local('OpenSans-CondensedLight'), url(/frontend/css/font/gk5FxslNkTTHtojXrkp-xKzhfLGYMo1TX3XnL4EHuCg.woff) format('woff');
}
@font-face {
  font-family: 'Open Sans Condensed';
  font-style: normal;
  font-weight: 700;
  src: local('Open Sans Condensed Bold'), local('OpenSans-CondensedBold'), url(/frontend/css/font/gk5FxslNkTTHtojXrkp-xCCpk0U-A1e26dz4Hiu3OHc.woff) format('woff');
}

/*------------------------------------------------------------------
# [Color codes]

# Orange (text, links): #FF9900
# Dark Orange (headings,hover) #C96
# */
/*------------------------------------------------------------------
[Typography]

Body copy:		1.2em/1.6em Open Sans
Headers:		2.7em/1.3em Open Sans Bold;
Input, textarea:1.1em Open Sans;
Menu:			1.5em Open Sans Condensed;

Notes:	decreasing heading by 0.4em with every subsequent heading level
-------------------------------------------------------------------*/
/*
.grey-gradient{background: rgb(38,38,38);
background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iIzI2MjYyNiIgc3RvcC1vcGFjaXR5PSIxIi8+CiAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiMwMTAxMDEiIHN0b3Atb3BhY2l0eT0iMSIvPgogIDwvbGluZWFyR3JhZGllbnQ+CiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+);
background: -moz-linear-gradient(top,  rgba(38,38,38,1) 0%, rgba(1,1,1,1) 100%);
background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(38,38,38,1)), color-stop(100%,rgba(1,1,1,1)));
background: -webkit-linear-gradient(top,  rgba(38,38,38,1) 0%,rgba(1,1,1,1) 100%);
background: -o-linear-gradient(top,  rgba(38,38,38,1) 0%,rgba(1,1,1,1) 100%);
background: -ms-linear-gradient(top,  rgba(38,38,38,1) 0%,rgba(1,1,1,1) 100%);
background: linear-gradient(to bottom,  rgba(38,38,38,1) 0%,rgba(1,1,1,1) 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#262626', endColorstr='#010101',GradientType=0 )}
.grey-gradient-reverse{background: rgb(11,11,11);
background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iIzBiMGIwYiIgc3RvcC1vcGFjaXR5PSIxIi8+CiAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiMyNDIzMjQiIHN0b3Atb3BhY2l0eT0iMSIvPgogIDwvbGluZWFyR3JhZGllbnQ+CiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+);
background: -moz-linear-gradient(top,  rgba(11,11,11,1) 0%, rgba(36,35,36,1) 100%);
background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(11,11,11,1)), color-stop(100%,rgba(36,35,36,1)));
background: -webkit-linear-gradient(top,  rgba(11,11,11,1) 0%,rgba(36,35,36,1) 100%);
background: -o-linear-gradient(top,  rgba(11,11,11,1) 0%,rgba(36,35,36,1) 100%);
background: -ms-linear-gradient(top,  rgba(11,11,11,1) 0%,rgba(36,35,36,1) 100%);
background: linear-gradient(to bottom,  rgba(11,11,11,1) 0%,rgba(36,35,36,1) 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#0b0b0b', endColorstr='#242324',GradientType=0 )}*/

/*------------------------------------------------------------------
Body*/
*{outline:none !important}
a{color:#990000;cursor:pointer}
.text-red{color:#C00}
.text-blue{color:#69c}
.text-purple{color:#96c}
.bg-blue{background-color:#990000;color:#FFF}
.bg-purple{background-color:#FF9900;color:#FFF}
.highlight{color:#FF9900}
a:link,a:hover{text-decoration:none}
body{font-family:Arial,Tahoma;font-size:14px;color:#333;background:#232323 url(../img/bg_main.jpg) top center no-repeat}
.container{width:980px}
.yellow,.yellow a{ color:#F30 !important; }
thead{background-color:#205887}
h1{font-size:22px;text-align:center;color:#990000;text-transform:uppercase}
h1, h2, h3, h4, h5, h6{font-family:'Open Sans Condensed';font-weight:700}
.media{border-bottom:1px solid #ccc; padding-bottom:15px; margin-bottom:25px;}
.media:last-child{border-bottom:none}
.media-body p{font-size:16px}
.media > .pull-left{margin-bottom:10px; margin-right:20px}
.nav-content p,.nav-content li{margin-bottom:15px;font-size:14px;line-height:20px}
.nav-content p.lead{font-size:18px;line-height:26px}
.video-container{border:4px solid #000;display:inline-flex;background-color:#000}
.section{margin-bottom:30px}
.pager li > a, .pager li > span,.pagination ul > li > a:hover, .pagination ul > li > a:focus, .pagination ul > .active > a, .pagination ul > .active > span,.pagination ul > li > a, .pagination ul > li > span{background-color:#333;}
.pagination ul > li > a:hover,.pagination ul > li > a:focus{background-color:#3e3e3e; color:#fff}
.pagination ul > .active > a,.pagination ul > .active > span{background-color:#666}
.counter{display:none}
.pagination ul li a { color:#fff !important}
.table-nobordered th, .table-nobordered td{border-top:none}
/*------------------------------------------------------------------
Header + Navbar*/
.header-wrapper { border-bottom:#16a5e8 solid 2px; background-color:#1a1d27}
.navbar{margin-bottom:0}
.navbar .nav > li > a,.nav > li > a{color:#fff;text-transform:uppercase;font-family:'Open Sans Condensed'; font-weight:bold;font-size:18px; display: inline-block;}
.header-wrapper .navbar{margin-right:20px}

.header-wrapper .navbar .nav > li > a{font-size:11px;font-family:'Open Sans';padding:9px}
.header .brand{padding:7px 0;}
.navbar .nav > li > a:hover,.dropdown-menu > li > a:hover{color:#C96}
.navbar .nav > li { display: inline-block;}
.navbar .nav > li .avatar { background:url(/frontend/img/avatar.png) left no-repeat; padding-left:20px !important; line-height:20px;  color:#FF9900 !important; margin-left:3px;}
.navbar .nav > li .avatar:hover, .logout:hover { text-decoration:underline !important}
.logout {  color:#FF9900 !important;}
.nav > .active > a, .navbar .nav > .active > a:hover, .navbar .nav > .active > a:focus,.navbar .nav li.dropdown.open > .dropdown-toggle, .navbar .nav li.dropdown.active > .dropdown-toggle, .navbar .nav li.dropdown.open.active > .dropdown-toggle,.navbar .nav > .active > a, .navbar .nav > .active > a:hover, .navbar .nav > .active > a:focus{background-color:transparent;color:#FF9900}
.navbar-wrapper{/* background:#e2e2e2*/}
.navbar-wrapper .container{width:980px}
.navbar-wrapper .navbar{margin-top:80px;position:relative}
.navbar-inner a.brand{margin-top:-74px; margin-bottom:5px;}
.navbar-inner{/*border-top:1px solid #967431;*/margin:px;height:80px}
.navbar-inner .nav {margin-top:0px; width:100%;background-image: linear-gradient(to bottom, #363636, #000000);}
.navbar-inner .nav li {background:url(../img/linebg.png) center right no-repeat; padding:0 3px}
.boxjoin { position:absolute; top:-30px; right:10px}
.boxjoin .join { background: #000 url(/frontend/img/join.png) 5px center no-repeat; padding:7px 7px 7px 45px; color:#fff; border-radius:5px; border:1px solid #ccc}
.boxjoin .join:hover { background-color:#3a3a3a}
.alert { margin-top:20px;}

/*------------------------------------------------------------------
Content*/
.wrapper .container-texture{/*background:url(/frontend/img/tmp/texture.png) no-repeat 0 0 #222 padding-top:30px;*/ }
.wrapper .container{position:relative; background-color:#fff;-moz-border-radius-bottomright: 3px;-webkit-border-bottom-right-radius: 3px;
border-bottom-right-radius: 3px;-moz-border-radius-bottomleft: 3px;-webkit-border-bottom-left-radius: 3px;border-bottom-left-radius: 3px;  padding-bottom:30px}
.wrapper .container #rightshadow{right:-30px;background:url(/frontend/img/tmp/right-shadow-wrapper.png) no-repeat right 0}
.wrapper .inner-container{margin:20px;min-height:600px}
.wrapper .inner-container h2{font-size:18px;line-height:22px}
.wrapper .inner-container h3{font-size:14px;line-height:18px}
/*------------------------------------------------------------------
Wrapper-menu*/
.wrapper .nav-pills{border:1px solid #666;border-left:none;border-right:none}
.wrapper .nav-pills li{margin-top:-1px;border-top:2px solid transparent;-webkit-transition:all 0.2s ease-in-out;-moz-transition:all 0.2s ease-in-out;-o-transition:all 0.2s ease-in-out;transition:all 0.2s ease-in-out}
.wrapper .nav-pills li > a{color:#333;text-transform:uppercase;font-weight: bold;font-size:18px;margin:2px 0;}
.wrapper .nav-pills li.active,.wrapper .nav-pills li.active:hover{border-top:2px solid #990000}
.wrapper .nav-pills li.active a{color:#990000}
.wrapper .nav-pills li:hover{border-top:2px solid #CCC}
/*------------------------------------------------------------------
Slide Team*/
#boxSlide{text-align:center; margin:0 auto; width:980px}
#boxSlide p{ margin: 0px; }

/*.slide-team{position:relative}
.slide-team .slide-wrapper-top{background:url(/frontend/img/tmp/frame-sprite.png) no-repeat center 0;height:50px;width:942px;position:absolute;top:-22px;left:-1px;z-index:1}
.slide-team .slide-wrapper-bottom{background:url(/frontend/img/tmp/frame-sprite.png) no-repeat center bottom;height:50px;width:942px;position:absolute;right:-1px;bottom:-20px;z-index:1}
.slide-team .slide{background:url(/frontend/img/tmp/frame-center.png) repeat-y center 0;padding:0 15px}*/
.carousel-indicators{
	background-color:#000;background-color:rgba(0,0,0,.8);
	/*left:0;right:0;*/
	width:912px;margin:0 auto
}
.lt-ie10 .carousel-indicators{left:14px}
.lt-ie8 .carousel-indicators li{float:left;width:104px}
.carousel-indicators li img{
	opacity:0.4;filter:alpha(opacity=40);-webkit-opacity:0.4;-moz-opacity:0.4;-o-opacity:0.4;
	-khtml-opacity:0.4;opacity:0.4;-ms-border-radius:2px;-o-border-radius:2px;
	-webkit-border-radius:2px;-moz-border-radius:2px;border-radius:2px;
}
.carousel-indicators li.active img,.carousel-indicators li:hover img{opacity:1.0;filter:alpha(opacity=100);}
/*------------------------------------------------------------------
Info Tournament*/
.icon-type-tournament{background:url(/frontend/img/tmp/sprite.png) no-repeat 0 0;width:99px;height:80px}
#img-semi-gold{background-position:0 -93px}
#img-semi-silver{background-position:0 -204px;height:100px}
#img-semi-bronze{background-position:0 -322px;height:100px}
#img-serie-c-cup{background-position:0 -438px}
.section-tournament-law .row-fluid{width:830px}
.section-common-info{text-align:center}
.icon-common-info{background-image:url(/frontend/img/tmp/sprite.png);background-repeat:no-repeat;height:85px;width:100px;display:inline-block}
.icon-time{background-position:center -537px}
.icon-type{background-position:center -637px}
.icon-prize{background-position:center -736px}
.section-notice h2{text-transform:uppercase}
.section-notice h2 .menu-group{margin-right:30px}
.section-notice h2 .datetime{margin-left:30px;font-size:12px}
.section-notice h2 .datetime i{margin-right:3px}
.section-schedule h2{margin-top:3px}
.section-board table tr { background-color:#FFF; border-bottom:1px solid #ccc}
.section-board table th,.section-board table td{text-align:center;font-size:22px;font-weight:bold;vertical-align:middle}
.section-board table th{height:29px;font-size:16px;line-height:26px;text-transform:uppercase}
.section-schedule th,.section-schedule table td{text-align:center;font-size:16px;vertical-align:middle}
.nav-board-content table td{padding:8px}
.section-board tr:last-child td{padding-bottom:20px !important}
.section-board table thead tr { color:#fff; background-color:#333}
.ie10 .section-board table thead{background-position:0 0}
.section-squad a{width:100%}
.row-fluid{margin-bottom:25px}
.section-squad img{border:1px solid #333}
.well{margin:20px 0;background-color:#222;color:#DDD;border:1px solid #333}
.section-team-detail .span3 img{margin-bottom:10px}
.section-team-detail .span3 p{text-align:center;margin-bottom:5px}
.section-team-detail .span3 .text-blue{font-weight:bold}
.section-board .span-img{width:100px;margin-left:0;float:none;display:inline-block;text-align:center}
.section-board .span-img img{display:inline-block}
.section-board .text-blue{display:inline-block;text-align:left;width:80px}
/*------------------------------------------------------------------
Map*/
.section-map-area .span6,.section-map-area .map{position:relative}
.mcTooltipInner h3{margin:0;white-space:nowrap}
.mcTooltipInner ul{width:100%;margin-top:10px}
.mcTooltipInner li{display:inline-block;margin-bottom:5px;width:200px}
.noticemap{margin-top:450px}
.noticemap li{display:inline-block;width:49%}
.lt-ie8 .noticemap li,.lt-ie8 .innerarea li{float:left}
.noticemap .badge{height:15px;width:15px;display:inline-block;margin-right:10px;padding:0;-webkit-border-radius:2px;-moz-border-radius:2px;border-radius:2px}
.noticemap #areatb{background-color:#73BF44}
.noticemap #areadb{background-color:#00C5E9}
.noticemap #areahn{background-color:#002FE9}
.noticemap #areatn{background-color:#00A986}
.noticemap #areadn{background-color:#FF9600}
.noticemap #areadg{background-color:#C1E900}
.noticemap #areahc{background-color:#E30000}
.noticemap #areamt{background-color:#B71AEA}
/*------------------------------------------------------------------
Bracket*/
.container-bracket{width:100%}
.container-bracket .shadow{display:none}
.container-bracket .nav-pills{width:980px;margin:auto}
.wrapper .container-bracket .inner-container{margin:20px 0}
/*------------------------------------------------------------------
Profile*/
.nav-profile{padding-top:30px}
.nav-profile .profileL{ width:48%; float:left; background:url(/frontend/img/tmp/bgd_line.jpg) top right no-repeat; margin-right:2%;}
.nav-profile dl{ overflow:hidden}
.nav-profile dl dd{ float:left; margin:0 20px 0 0}
.nav-profile dl dd img{border:1px solid #333}
.nav-profile dl span{ display:block}

.nav-profile .profileR{ width:48%; float:right}
.nav-profile .profileR dl span{font-size:24px;}
.nav-profile .profileR li span{ padding:0 20px 0 0}

.header-inner .welcome{ float:right; padding:9px;}

/*------------------------------------------------------------------
Login*/
.nav-login form{ width:50%; margin:60px auto; padding:20px; background:#1e1e1e; border-radius:10px; box-shadow:0 -15px 20px rgba(0, 0, 0, 0.2);-webkit-box-shadow:0 -15px 20px rgba(0, 0, 0, 0.2);-moz-box-shadow:0 -15px 20px rgba(0, 0, 0, 0.2)}
.nav-login form fieldset{background:#141414; padding:10px; border-radius:10px;}

.nav-login .control-group{ overflow:hidden; margin-bottom:2px}
.nav-login .control-group label{ float:left; width:35%; color:#fff; padding-top:5px;}
.nav-login .control-group label.checkbox{font-size:10px;}
.nav-login .control-group input{ float:left; background:#000; border-color:#333; color:#CCC}
.nav-login form .large{ width:100%}
/*------------------------------------------------------------------
Footer
.footer{margin-top:30px;font-size:11px;background-color: #1A1D27;
    border-top: 2px solid #16A5E8;}
.footer p{text-align:center;margin-bottom:0; color:#CCC}
.footer li{margin-bottom:5px;list-style:none;color:#999;}
.footer a{color:#999;-webkit-transition:all 0.2s ease-in-out;-moz-transition:all 0.2s ease-in-out;-o-transition:all 0.2s ease-in-out;transition:all 0.2s ease-in-out}
.footer a:hover{color:#EEE}
.footer .container{padding:10px 0}
.icon-social{background:url(/frontend/img/tmp/logo-social.png) no-repeat 0 0;width:15px;height:23px;display:inline-block}
#youtube{background-position:right 0;width:30px}
.logo-footer{background:url(/frontend/img/tmp/logo-footer.png);height:100px;width:110px;display:inline-block}
#logo-lmht{background:url(/frontend/img/fo3.png) no-repeat; width:167px; height:73px; margin-top:10px;}
#logo-ve{margin-right:20px}*/

#footer{margin-top:30px;font-size:11px;background-color: #1A1D27;  border-top: 2px solid #16A5E8; padding:30px 0}
#footer .container { background:none}
#footer ul{list-style:none;overflow:hidden;margin:0}
#footer li{float:left;margin:0 5px}
#footer li#text-copy{font:10px/14px Arial, Helvetica, sans-serif;color:#999;width:580px; text-align:justify; line-height:10px; margin:0 20px}

/*========= Css Tan Loc ========================*/

/*==== table =======*/
.listteam table {	width : 100%;color:#fff}
.listteam  table tbody td {background:#dcdcdc !important; padding:7px 10px !important; text-align:center; color:#333; border-bottom:1px solid #ccc}

.listteam  table tr.even td {background:#f1f1f1 !important; border-bottom:1px solid #ccc}

.listteam table thead td,.listteam table thead th {background :#205887;padding : 7px 10px;font-weight:bold; color:#fff; text-align:center;text-transform: uppercase; border:none}

.listteam table tfoot td {padding : 7px 10px!important;}
.listteam  table input { padding:3px 10px; border-radius:5px; border:none; color:#666;}
.listteam  table input:hover { color:#FF9900 !important}


.searchlist { overflow:hidden; margin-bottom:10px}
.searchlist input,.searchlist select { float:left; margin-right:10px;}
.searchlist .name { width:150px; background:#FFF; padding:4px 10px; height:17px;}
.searchlist .provine { width:150px; background:#FFF; padding:3px; height:25px;}
.searchlist .step { width:100px; background:#FFF; padding:4px 10px; height:17px;}
.searchlist .position { width:100px; background:#FFF; padding:4px 10px; height:17px;}
.searchlist .bt { background:url(/frontend/img/tmp/thead.gif) repeat-x; border:none; padding:5px 10px;}
.searchlist .bt:hover { color:#FFF}


 /*=====      Danh sach giai dau    ====*/

.tabslist { overflow:hidden; margin:0; padding:0; border-bottom:2px solid #990000;}
.tabslist li {overflow:hidden;height:30px;line-height:30px;-moz-border-radius:3px;	-webkit-border-radius:3px;	border-radius:3px; float:left; padding:3px 15px; margin-right:10px; background-color:#333; margin-bottom:-3px; font-size:16px; text-transform:uppercase}
.tabslist li a { color:#fff}
.tabslist li.active,.tabslist li:hover {background-color:#990000;color:#333 !important}
.tabslist li a:hover ,.tabslist li:hover a{color:#333}
.contentList { overflow:hidden; padding:10px 0;}
.contentList ul.list { list-style:none; margin-left:-15px; overflow:hidden}

.contentList ul.list li {float:left; margin:10px 0 10px 15px;padding:15px;width:430px; min-height:150px; border:1px solid #666}

.contentList ul.list li img { float:left; margin-right:15px; width:150px; height:125px;border: 1px solid #CCCCCC;
    padding: 4px;padding: 4px;}
.contentList ul.list li .boxtext { float:right; width:250px; color:#666;}
.contentList ul.list li .boxtext a{ color:#990000;font-size:16px; font-weight:bold}
.contentList ul.list li .boxtext a:hover {color:#F00;}
.contentList ul.list li .boxtext p { margin-top:10px;}
/*======= Detail ====================*/
.h1 { font-weight:bold; font-size:20px; color:#666;}
.img {background-color: #292929; border: 1px solid #666;   border-radius: 3px;padding: 4px;}
.contTour { overflow:hidden; margin:10px 0; padding:20px 0; line-height:22px}
.contTour .left { width:500px; float:left;}
.contTour .right { width:380px; float:right;}
.contTour .right img { width:365px; height:310px;background-color: #292929; border: 1px solid #494949;   border-radius: 3px;padding: 4px;}
.dateRegis {font-size: 12px; color:#666; /*float: left; width:110px;*/}
.datePlay {font-size: 12px;color: #666; /*float: right; width:110px;*/}
.dateRegis strong,.datePlay strong{ color:#F30;}
/*==== End table =======*/


/*=========== Profile ===================*/
.boxprofile { background-color:#fff; padding:15px; margin:20px 0; overflow:hidden;}
.boxprofile .colum1 { width:210px; float:left; margin:0 10px;}
.boxprofile .colum2 { width:450px; float:left; margin:0 10px;}
.boxprofile .avatatPro { width:210px; float:left; padding-top:10px;}
.boxprofile .rowPro { min-height:80px; color:#990000}
.boxprofile .rowPro h2 { font-weight:bold; color:#333; border-bottom:1px dashed #ccc; padding-bottom:2px; margin-bottom:10px; text-align:left; font-size:14px; text-transform:uppercase}
.boxprofile .avatatPro img { width:190px; height:180px; background-color: #fff; border: 1px solid #ccc;  padding: 4px; margin-bottom:20px;}

.boxprofile .selecleader{  width:210px; background:#FFF; padding:3px; height:25px;}
.boxprofile .bt { background:url(/frontend/img/tmp/thead.gif) repeat-x; border:none; padding:5px 10px; border-radius:3px;}
.boxprofile .bt:hover { color:#333}
/*====== end =================*/
/*========== Intro ==================*/

.boxintro { padding:20px; text-align:justify}
.boxintro h6 { text-align:center}
.boxintro h6 img {    background-color: #292929; border: 1px solid #666666; border-radius: 3px;padding: 4px; margin:20px 0; max-width:700px;}









/** User Guide Page */
    .rows { margin:30px 30px 20px 0; overflow:hidden;}
    .myButton,.btdetail {       
        background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #F30), color-stop(1, #990000));
        background:-moz-linear-gradient(top, #F30 5%, #990000 100%);
        background:-webkit-linear-gradient(top, #F30 5%, #990000 100%);
        background:-o-linear-gradient(top, #F30 5%, #990000 100%);
        background:-ms-linear-gradient(top, #F30 5%, #990000 100%);
        background:linear-gradient(to bottom, #F30 5%, #990000 100%);
        filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffc477', endColorstr='#fb9e25',GradientType=0);
        background-color:#990000;display:inline-block; -moz-border-radius:7px;-webkit-border-radius:7px; border-radius:7px;
        color:#ffffff !important;font-family:arial;font-size:15px;font-weight:bold;padding:5px 24px;text-decoration:none; text-transform:uppercase; margin-right:30px;}
    .myButton:hover,.btdetail:hover {
        background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #fb9e25), color-stop(1, #990000));
        background:-moz-linear-gradient(top, #fb9e25 5%, #990000 100%);
        background:-webkit-linear-gradient(top, #fb9e25 5%, #990000 100%);
        background:-o-linear-gradient(top, #fb9e25 5%, #990000 100%);
        background:-ms-linear-gradient(top, #fb9e25 5%, #990000 100%);
        background:linear-gradient(to bottom, #fb9e25 5%, #990000 100%);
        filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#fb9e25', endColorstr='#990000',GradientType=0);
        background-color:#fb9e25;
        color:#fff
    }

    .bottonBlue {-moz-box-shadow:inset 0px 1px 0px 0px #97c4fe;-webkit-box-shadow:inset 0px 1px 0px 0px #97c4fe;box-shadow:inset 0px 1px 0px 0px #97c4fe;background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #3d94f6), color-stop(1, #1e62d0));
        background:-moz-linear-gradient(top, #3d94f6 5%, #1e62d0 100%);
        background:-webkit-linear-gradient(top, #3d94f6 5%, #1e62d0 100%);
        background:-o-linear-gradient(top, #3d94f6 5%, #1e62d0 100%);
        background:-ms-linear-gradient(top, #3d94f6 5%, #1e62d0 100%);
        background:linear-gradient(to bottom, #3d94f6 5%, #1e62d0 100%);
        filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#3d94f6', endColorstr='#1e62d0',GradientType=0);
        background-color:#3d94f6; -moz-border-radius:20px;-webkit-border-radius:20px; border-radius:20px; border:1px solid #337fed;display:inline-block;
        color:#ffffff;  font-family:arial;font-size:15px;font-weight:bold; padding:10px 24px;text-decoration:none;text-shadow:0px 1px 0px #1570cd;text-transform:uppercase;}
    .bottonBlue:hover {
        background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #1e62d0), color-stop(1, #3d94f6));
        background:-moz-linear-gradient(top, #1e62d0 5%, #3d94f6 100%);
        background:-webkit-linear-gradient(top, #1e62d0 5%, #3d94f6 100%);
        background:-o-linear-gradient(top, #1e62d0 5%, #3d94f6 100%);
        background:-ms-linear-gradient(top, #1e62d0 5%, #3d94f6 100%);
        background:linear-gradient(to bottom, #1e62d0 5%, #3d94f6 100%);
        filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#1e62d0', endColorstr='#3d94f6',GradientType=0);
        background-color:#1e62d0; color:#fff
    }

/*   Profile*/
.nav-profile{padding-top:30px}
.nav-profile .profileL{ width:48%; float:left; background:url(../images/bgd_line.jpg) top right no-repeat; margin-right:2%;}
.nav-profile dl{ overflow:hidden}
.nav-profile dl dd{ float:left; margin:0 20px 0 0}
.nav-profile dl dd img{border:1px solid #333}
.nav-profile dl span{ display:block}

.nav-profile .profileR{ width:48%; float:right}
.nav-profile .profileR dl span{font-size:24px;}
.nav-profile .profileR li span{ padding:0 20px 0 0}

.header-inner .welcome{ float:right; padding:9px;}




/*=== boxnote =====*/
.boxnote { background-color:#232323; padding:10px;border: 1px solid #3E3E3E !important; width:500px; margin:30px auto}
.error404 { margin:30px}

    .rows { margin:30px 30px 20px 0; overflow:hidden;}
	.hidden { overflow:hidden}
    .myButton {
        -moz-box-shadow:inset 0px 1px 0px 0px #fce2c1;-webkit-box-shadow:inset 0px 1px 0px 0px #fce2c1;box-shadow:inset 0px 1px 0px 0px #fce2c1;
        background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #ffc477), color-stop(1, #fb9e25));
        background:-moz-linear-gradient(top, #ffc477 5%, #fb9e25 100%);
        background:-webkit-linear-gradient(top, #ffc477 5%, #fb9e25 100%);
        background:-o-linear-gradient(top, #ffc477 5%, #fb9e25 100%);
        background:-ms-linear-gradient(top, #ffc477 5%, #fb9e25 100%);
        background:linear-gradient(to bottom, #ffc477 5%, #fb9e25 100%);
        filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#ffc477', endColorstr='#fb9e25',GradientType=0);
        background-color:#ffc477;-moz-border-radius:20px;-webkit-border-radius:20px;border-radius:20px; border:1px solid #eeb44f; display:inline-block;
        color:#ffffff;font-family:arial;font-size:15px;font-weight:bold;padding:10px 24px;text-decoration:none;text-shadow:0px 1px 0px #cc9f52; text-transform:uppercase; margin-right:30px;}
    .myButton:hover {
        background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #fb9e25), color-stop(1, #ffc477));
        background:-moz-linear-gradient(top, #fb9e25 5%, #ffc477 100%);
        background:-webkit-linear-gradient(top, #fb9e25 5%, #ffc477 100%);
        background:-o-linear-gradient(top, #fb9e25 5%, #ffc477 100%);
        background:-ms-linear-gradient(top, #fb9e25 5%, #ffc477 100%);
        background:linear-gradient(to bottom, #fb9e25 5%, #ffc477 100%);
        filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#fb9e25', endColorstr='#ffc477',GradientType=0);
        background-color:#fb9e25;
        color:#fff
    }

    .bottonBlue {-moz-box-shadow:inset 0px 1px 0px 0px #97c4fe;-webkit-box-shadow:inset 0px 1px 0px 0px #97c4fe;box-shadow:inset 0px 1px 0px 0px #97c4fe;background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #3d94f6), color-stop(1, #1e62d0));
        background:-moz-linear-gradient(top, #3d94f6 5%, #1e62d0 100%);
        background:-webkit-linear-gradient(top, #3d94f6 5%, #1e62d0 100%);
        background:-o-linear-gradient(top, #3d94f6 5%, #1e62d0 100%);
        background:-ms-linear-gradient(top, #3d94f6 5%, #1e62d0 100%);
        background:linear-gradient(to bottom, #3d94f6 5%, #1e62d0 100%);
        filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#3d94f6', endColorstr='#1e62d0',GradientType=0);
        background-color:#3d94f6; -moz-border-radius:20px;-webkit-border-radius:20px; border-radius:20px; border:1px solid #337fed;display:inline-block;
        color:#ffffff;  font-family:arial;font-size:15px;font-weight:bold; padding:10px 24px;text-decoration:none;text-shadow:0px 1px 0px #1570cd;text-transform:uppercase;}
    .bottonBlue:hover {
        background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #1e62d0), color-stop(1, #3d94f6));
        background:-moz-linear-gradient(top, #1e62d0 5%, #3d94f6 100%);
        background:-webkit-linear-gradient(top, #1e62d0 5%, #3d94f6 100%);
        background:-o-linear-gradient(top, #1e62d0 5%, #3d94f6 100%);
        background:-ms-linear-gradient(top, #1e62d0 5%, #3d94f6 100%);
        background:linear-gradient(to bottom, #1e62d0 5%, #3d94f6 100%);
        filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#1e62d0', endColorstr='#3d94f6',GradientType=0);
        background-color:#1e62d0; color:#fff
    }
.error{
    color:red;
}

/* ---------------------------- CSS FOR SERIES B -----------------------------------*/
#SerieB .tabslist {
    border-bottom: 2px solid #990000;
    margin: 0;
    overflow: hidden;
    padding: 0 0 0 7px;
}
#SerieB .tabslist li {
    background-color: #333333;
    border-radius: 3px;
    float: left;
    font-size: 15px;
    height: 30px;
    line-height: 30px;
    margin-bottom: -3px;
    margin-right: 5px;
    overflow: hidden;
    padding: 3px 10px;
    text-transform: uppercase;
}

#SerieB .tabslist li.active,#SerieB .tabslist li:hover {
    background-color: #990000;
    color: #333333 !important;
}
.row_mar .btn,.join-team {  background-color: #333;
    background-image: linear-gradient(to bottom, #666, #333);
    background-repeat: repeat-x;
    border:none !important;
    color: #FFFFFF;
    text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25);
}
#SerieB .formChooseBracket .btn {   background-color: #e4685d; background-image: linear-gradient(to bottom, #e4685d, #e67a73); background-repeat: repeat-x; border: none !important; color: #FFFFFF; text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.25)}
#formChooseBracket .active{  background-color: #666; }
#SerieB .table-bordered th,#SerieB .table-bordered td { 
    border-left: 1px solid #222222;
}
#SerieB .table td {
    border-top: 1px solid #333333 !important;
    line-height: 20px;
    padding: 8px;
    text-align: left;
    vertical-align: top;
}
#SerieB .table-bordered {
    -moz-border-bottom-colors: none;
    -moz-border-left-colors: none;
    -moz-border-right-colors: none;
    -moz-border-top-colors: none;
    border-collapse: separate;
    border-color: #222222 !important;
    border-image: none;
    border-style: solid solid solid none;
    border-width: 1px 1px 1px 0;
}
.row_mar {}
.row_mar h2 {color: #990000;font-size: 22px !important;text-transform: uppercase; border-bottom:2px solid #666; padding-bottom:5px; width:930px !important; margin-bottom:10px; padding-left:10px}
.champion-unplayer{
	background:url("/frontend/img/icon_cup.png") no-repeat scroll center center rgba(0, 136, 221, 0.3) !important;
}
.champion-winner{
	background:url("/frontend/img/icon_cup.png") no-repeat scroll center center rgba(111, 175, 30, 0.2) !important;
}


/* ---------------------------- CSS FOR HOMEPAGE -----------------------------------*/
#img-teemo-cup {
    background-position: 0 -438px;
}
.da-slide h2>a,.da-slide h2>a:hover,.da-slide h2>a:active{
    color: #CC9966 !important;
}
.openbeta {
    background: url("/frontend/img/openbeta.png") no-repeat scroll 0 0 rgba(0, 0, 0, 0);
    display: block;
    height: 136px;
    overflow: hidden;
    position: absolute;
    right: 0;
    text-indent: -999px;
    top: 0;
    width: 150px;
    z-index: 999;
}
.logo-team-hp{
    width: 40px;
    height: auto;
}
.boxprofile .disabled{
    color: #333333 !important;
}

/* ---------------------------- CSS FOR SERIE A -----------------------------------*/
#SerieA select{   
    border-color: #ccc;
}
#SerieA select:focus{
    border-color: rgba(82, 168, 236, 0.8);
    box-shadow: 0 1px 1px rgba(0, 0, 0, 0.075) inset, 0 0 8px rgba(82, 168, 236, 0.6);
    color: #EEEEEE;
    outline: thin dotted #333333;
    outline-offset: -2px;
}
#terms-tournament{
    margin-top: 20px;
}
#terms-tournament li{
    color: #B94A48 !important;
}
.min-height-slide-team{
    height: 316px;
}
#SerieA .table th{
	font-size: 12px !important;
}
#SerieA .table td{
    font-size: 18px !important;
}
.serie-a-show-bracket{
	float:left;width:100%;margin-top: 20px;
}

/* ---------------------------- OPENID -----------------------------------*/
.blueButtonOpendId {
    border: medium none;
    float: left;
}
.blueButtonOpendId.blue .pluginButton {
    background: linear-gradient(#4C69BA, #3B55A0) repeat scroll 0 0 rgba(0, 0, 0, 0);
    border: medium none;
    border-radius: 2px;
    color: #FFFFFF;
    height: 20px;
    line-height: 20px;
    text-shadow: 0 -1px 0 #354C8C;
}
.blueButtonOpendId .pluginButton {
    font-weight: bold;
    padding: 0;
}
.pluginButton {
    background: none repeat scroll 0 0 #ECEEF5;
    border: 1px solid #CAD4E7;
    border-radius: 3px;
    color: #3B5998;
    cursor: pointer;
    padding: 2px 6px 4px;
    white-space: nowrap;
}
.blueButtonOpendId .pluginButton .pluginButtonImage {
    display: inline-block;
}
.pluginButton button {
    background: none repeat scroll 0 0 rgba(0, 0, 0, 0);
    border: 0 none;
    color: inherit;
    cursor: pointer;
    font: inherit;
    margin: -1px;
    padding: 0;
}
.blueButtonOpendId.blue .pluginButton button {
    text-shadow: 0 -1px 0 #354C8C;
}
.blueButtonOpendId .pluginButton button {
    font-weight: bold;
    outline: medium none;
}

.blueButtonOpendId.blue .pluginButton .pluginButtonIcon {
    margin: 0 4px;
    top: 3px;
}
.blueButtonOpendId .pluginButton .pluginButtonIcon {
    height: 14px;
    left: 0;
    position: relative;
    vertical-align: top;
    width: 14px;
}
.sx_e2959e {
    background-position: 1px -32px;
}
.sp_6lt5t8 {
    background-image: url("/frontend/img/t_KUFQ1650z.png");
    background-repeat: no-repeat;
    background-size: auto auto;
    display: inline-block;
    height: 14px;
    width: 14px;
}
.blueButtonOpendId.blue .pluginButton .pluginButtonLabel{
    padding: 0 5px 0 0;
    font-size: 13px;
    color: white;
}
.pluginButtonLabel:active,.pluginButtonLabel:hover{
    color: white;
}
.blueButtonOpendId .pluginButton .pluginButtonLabel {
    position: relative;
    vertical-align: top;
}
#OpenId{
    float: left;
    width: 100%;
    margin-bottom: 20px;
    margin-top: 20px;
}
#OpenIdLabel{
    float: left;
    margin-right: 10px;
}
#EventDetail h1{
    text-align: left !important;
}

#choose-tournament-type{float: right;}
#warpper-choose-tournament-type{margin-bottom: 20px;width: 100%;float: left;}

#description-tournament{float: left;width: 100%;}
.profile-team-history-log{ font-size: 10px;color:#333; }

/* === Css for index  */
.systemsrating{ background:url(../img/systemsrating.jpg) left no-repeat; height:127px; padding-left:20px; margin-bottom:20px;}
.systemsrating a { line-height:127px;color: #fff;font-size: 28px;text-transform: uppercase;font-family: Roboto,sans-serif,Arial; font-weight:bold}
.systemsrating a:hover { color:#F90}
.acttitle {color:#626262; font-size:28px;text-shadow: 0 1px 1px #FFFFFF; text-transform: uppercase;font-family: Roboto, sans-serif, Arial;}
.lineweek { border-bottom:1px solid #CCC; height:15px; margin-bottom:50px; margin-top:20px}
.lineweek .boxtime { background-color:#c9cccd; height:30px; width:262px; margin:0 auto; overflow:hidden;}
.lineweek .boxtime .nextweek { background: #000 url(../img/leftnerow.png) center no-repeat; width:30px; height:30px; float:left}
.lineweek .boxtime .preweek { background: #000 url(../img/rightnerow.png) center no-repeat; width:30px; height:30px; float:right}
.lineweek .boxtime .preweek:hover ,.lineweek .boxtime .nextweek:hover { background-color:#333} 
.lineweek .boxtime .timeweek { font-weight:bold; color:#333; line-height:30px; text-align:center; float:left; width:200px; font-size:18px}

/*css box slider parkner-------------------------------------*/	
.module_games { position:relative;}
.module_games .caroufredsel_wrapper { margin:0 auto; width:910px !important; min-height:165px; color:#F4F4F4}
.module_games .prevarrow {	position:absolute;top:50px;left:-15px;		background:url(../img/pre01.png) no-repeat;	width:30px;	height:60px;z-index:100;opacity:0.4;filter:alpha(opacity=40);}
.module_games .nextarrow {	position:absolute;	top:50px;right:-15px;	background:url(../img/next01.png) no-repeat;	width:30px;	height:60px;z-index:100;opacity:0.4;filter:alpha(opacity=40);}
.module_games .prevarrow:hover,.module_games .nextarrow:hover {opacity:10;filter:alpha(opacity=100);}
.module_games .games { margin:0; padding:0; text-align:center; width:940px !important}
.module_games .games li { background:#c7312e;margin: 0 10px 10px 0;overflow: hidden;position: relative;width: 220px; text-align:center; display:inline-block}
.module_games .games li.vea { background:#205887 !important;}
.module_games .games li .live { background: url(../img/star.png) no-repeat; width:21px; height:20px; position:absolute; right:10px; bottom:10px}
.module_games .nomacth { margin:20px auto; background: url(../img/nomatch.jpg) no-repeat; width:295px; height:150px; display:block} 
.notable { margin:20px auto; background: url(../img/notable.jpg) no-repeat; width:295px; height:150px; display:block} 
.module_games .games li  .cname { color:#fff}
.module_games .games li .logos { background: none repeat scroll 0 0 #efefef; float: left;text-align: center; width: 100%;}
.module_games .games li .logos .away, .module_games .games li .logos .home {display: inline-block; height: 60px; padding: 15px 5px;    width: 60px;}
.module_games .games li .logos .away img, .module_games .games li .logos .home img {height: 100%; max-width: 100%;}
.module_games .games li .logos .middle { background: url("../img/vs-logo.png") no-repeat scroll center center rgba(0, 0, 0, 0);   display: inline-block;height: 40px; padding: 25px 5px; position: relative; text-align: center;vertical-align: top; width: 48px;}
.module_games .games li .logos .middle .hour {color: #333; display: block;font-size: 18px; padding: 3px 0;}
.module_games .games li .logos .middle .date { color: #333; display: block;font-size: 12px;line-height: 14px;}
.module_games .games li .info { float: left; padding: 5px 0px; position: relative; width: 100%;}
.module_games .games li .info h2 a { color: #FFFFFF;display: block; font-size: 15px;line-height: 18px; overflow: hidden;  text-overflow: ellipsis; white-space: nowrap;}

/*== listmatch===*/
.listmatch {border-bottom:1px solid #CCC; border-top:1px solid #CCC; margin:20px 0 30px 0; text-align:center; overflow:hidden}
.listmatch li { display: inline-block; min-width:150px;margin:0 2px;}
.listmatch li a { color:#333; line-height:35px; text-align:center; display: block; font-size:18px; text-transform:uppercase; font-weight:bold;font-family: 'Open Sans Condensed';}
.listmatch li.active  a {border-bottom:2px #990000 solid; color:#990000}
/*== listmatchvea===*/
.listmatchvea {border-bottom:1px solid #CCC; border-top:1px solid #CCC; margin:20px 0 30px 0; text-align:center; overflow:hidden}
.listmatchvea li { display: inline-block; min-width:150px;margin:0 2px;}
.listmatchvea li a { color:#333; line-height:35px; text-align:center; display: block; font-size:18px; text-transform:uppercase; font-weight:bold;font-family: 'Open Sans Condensed';}
.listmatchvea li.active  a {border-bottom:2px #990000 solid; color:#990000}

/*== listtable===*/
.listtable  {border-bottom:1px solid #CCC; border-top:1px solid #CCC; margin:20px 0 30px 0; text-align:center; overflow:hidden}
.listtable li { display: inline-block; min-width:150px;margin:0 2px;}
.listtable  li a { color:#333; line-height:35px; text-align:center; display: block; font-size:18px; text-transform:uppercase; font-weight:bold;font-family: 'Open Sans Condensed';}
.listtable  li.active  a {border-bottom:2px #990000 solid; color:#990000}

.contmacth {}
.nonTable { background: none repeat scroll 0 0 #289C8E;overflow: hidden;position: relative;
width: 260px; text-align:center; margin:0 auto}


/*==  Promotion =====*/

.titlePro { background-color:#333; line-height:35px; font-size:20px; padding-left:20px; margin-bottom:20px; color:#fff}
.contentPro { overflow:hidden; margin-bottom:20px;}
.contentPro .imgleft{ border:3px solid #ccc; float:left; margin-right:30px; width:465px; height:275px;}
.contentPro .imgright{ border:3px solid #ccc; float:right; margin-left:30px; width:465px; height:275px;}




#listmatch1 .module_games .games li ,#listmatch2 .module_games .games li {width: 170px;}
#listmatch1 .module_games .games li .info, #listmatch2 .module_games .games li .info, #listmatch1 .module_games .games li .logos, #listmatch2 .module_games .games li .logos  {height: 90px;}
#listmatch1 .module_games .games li .logos .away, #listmatch1 .module_games .games li .logos .home, #listmatch2 .module_games .games li .logos .away, #listmatch2 .module_games .games li .logos .home {height: 45px;width: 45px;}
#listmatch1 .module_games .games li .logos .middle, #listmatch2 .module_games .games li .logos .middle{width:38px;}
#listmatch1 .module_games .games, #listmatch2 .module_games .games{width: 920px !important;}
