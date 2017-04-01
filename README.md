<!DOCTYPE html>
<html>
<head lang="en">
    <meta name="viewport" content="width=device-width,minimum-scale=1.0,maximum-scale=1.0 user-scalable=no"/>
    <meta charset="UTF-8">
    <title>school</title>
    <link rel="stylesheet" href="css/style.css"/>
    <link rel="stylesheet" href="css/swiper.min.css"/>
    <style>
        #xuezidongtai {
            overflow: hidden;
        }
        #xuezidongtai .swiper-wrapper ul{
            background-color: white;
            padding:12px;
            border-radius: 2%;
            border-top-left-radius: 0;
            border-top-right-radius: 0;
        }
        #xuezidongtai .swiper-wrapper>ul li{
            margin-left:12px;
            line-height: 22px;
            list-style-type: square;
            color:#3077B5;
        }
        #xuezidongtai .swiper-wrapper>ul li a{
            color:black;
        }
        #xuezidongtai .swiper-wrapper>ul li a:hover{
            color:red;
        }
        #xuezidongtai .swiper-pagination-bullet{
            display: table-cell;
            vertical-align:middle;
            padding-left:26px;
            border-radius: 0;
            width:80px;
            height:24px;
            border-right:1px solid #BABABA;
            opacity: 1;
            color:#2775B3;
            background: url("images/blue_dot.png")13px center no-repeat;
        }
        #xuezidongtai .swiper-pagination-bullet-active{
            background-color: white;
            background-image: url("images/red_dot.png");
            background-position:13px center;
            background-repeat: no-repeat;
            color:#D80106;
            border-right:1px solid #BABABA;
        }
        #xuezidongtai h3{
            background-image: none;
            padding:0;
            margin-bottom:0;
        }
        #xuezidongtai .tabs-top{
            padding:0;
            padding-right:13px;
        }
        #xuezidongtai ul li{
            line-height: 12px !important;
            margin-top:10px;
        }
        #xuezidongtai ul li a{
            display: inline-block;
            width:264px;
            color:black;
            overflow:hidden;
            text-overflow:ellipsis;
            white-space: nowrap;  /*兼容谷歌，火狐，IE*/
        }
    </style>
</head>
<body>
<!--头部-->
    <div class="top">
        <div class="top-content">
            <div class="top-l">
                <img src="images/badge.png" alt="校徽"/>
                <div>
                    <div>
                        <img src="images/school_name.png" alt="校名"/>
                        <span class="fenxiao">珠海分校</span>
                    </div>
                    <h2>信&nbsp&nbsp息&nbsp&nbsp技&nbsp&nbsp&nbsp术&nbsp&nbsp学&nbsp&nbsp&nbsp院<span></span></h2>
                </div>
            </div>
            <div class="top-r fr">
                <input class="seach" type="text" placeholder="请输入搜索关键词"/>
                <input class="btn" type="button" value="搜索"/>
            </div>
        </div>
    </div>
<!--导航-->
    <div class="nav">
        <ul>
            <li><a href="javascript:" style="padding:12px 34px">首页</a></li>
            <li><a href="javascript:">学院概况</a></li>
            <li class="sup-menu"><a href="javascript:">教学管理</a>
                <ul class="sub-menu">
                    <img src="images/dot.png" alt="dot"/>
                    <li><a href="javascript:">教务通知</a></li>
                    <li><a href="javascript:">资料下载</a></li>
                    <li><a href="javascript:">院务管理系统</a></li>
                    <li><a href="javascript:">毕业生信息管理系统</a></li>
                    <li><a href="javascript:">家校互动服务平台</a></li>
                </ul>
            </li>
            <li class="sup-menu"><a href="javascript:">学科专业</a>
                <ul class="sub-menu">
                    <img src="images/dot.png" alt="dot"/>
                    <li><a href="javascript:">数学与统计</a></li>
                    <li><a href="javascript:">生物科学</a></li>
                    <li><a href="javascript:">计算机应用</a></li>
                    <li><a href="javascript:">艺术专业</a></li>
                    <li><a href="javascript:">商务类专业</a></li>
                </ul>
            </li>
            <li><a href="javascript:">科学研究</a></li>
            <li><a href="javascript:">党群建设</a></li>
            <li><a href="javascript:">国际合作</a></li>
            <li><a href="javascript:">学生工作</a></li>
            <li><a href="javascript:">就业培训</a></li>
            <li><a href="javascript:">在线展示</a></li>
        </ul>
    </div>
<!--内容区-->
    <div class="main-wrapper">
        <div class="main">
            <div class="main-l">
                <div class="news tabs">
                    <div class="tabs-top">
                        <h3>新闻动态</h3>
                        <a class="fr" href="javascript:">more</a>
                    </div>
                    <div class="tabs-content">
                        <div id="swiper-container" class="swiper-container">
                            <div class="swiper-wrapper">
                                <div class="swiper-slide"><a href="javascript:"><img src="images/news.jpg" alt="news"/></a></div>
                                <div class="swiper-slide"><a href="javascript:"><img src="images/news2.jpg" alt="news"/></a></div>
                                <div class="swiper-slide"><a href="javascript:"><img src="images/news3.jpg" alt="news"/></a></div>
                                <div class="swiper-slide"><a href="javascript:"><img src="images/news4.jpg" alt="news"/></a></div>
                            </div>

                            <div class="swiper-pagination"></div>
                        </div>
                        <ul style="margin-top:6px;color:#D95121">
                            <li><a href="javascript:">2011年下半年全国计算机等级考试报名通知</a><span>2011-12-12</span></li>
                            <li><a href="javascript:">全国计算机等级考试考生须知</a><span>2011-12-12</span></li>
                            <li><a href="javascript:">师生澳门参观学习，感受3D技术魅力</a><span>2011-12-12</span></li>
                            <li><a href="javascript:">第八届IT节之网佳科技杯计算机作品设计大赛</a><span>2011-12-12</span></li>
                            <li><a href="javascript:">2011年下半年全国计算机等级考试报名通知</a><span>2011-12-12</span></li>
                            <li><a href="javascript:">全国计算机等级考试考生须知</a><span>2011-12-12</span></li>
                            <li><a href="javascript:">师生澳门参观学习，感受3D技术魅力</a><span>2011-12-12</span></li>
                            <li><a href="javascript:">第八届IT节之网佳科技杯计算机作品设计大赛</a><span>2011-12-12</span></li>
                            <li><a href="javascript:">师生澳门参观学习，感受3D技术魅力</a><span>2011-12-12</span></li>
                            <li><a href="javascript:">全国计算机等级考试考生须知</a><span>2011-12-12</span></li>
                        </ul>
                    </div>
                </div>
                <div class="tabs" id="xuezidongtai" style="margin-top:30px;">
                    <div class="tabs-top">
                        <h3 class="swiper-pagination1"></h3>
                        <a class="fr" href="javascript:">more</a>
                    </div>
                    <div class="tabs-corntent swiper-wrapper">
                        <ul class="swiper-slide">
                            <li><a href="javascript:">学生会第八届主席团公开述职暨换届大会顺利召开</a></li>
                            <li><a href="javascript:">我院隆重召开第九次团员代表大会</a></li>
                            <li><a href="javascript:">首届“阳光体育嘉年华”胜利闭幕，我院运动健儿屡获佳绩</a></li>
                            <li><a href="javascript:">我院男篮时隔三年重回巅峰，称霸北师篮坛傲视群雄</a></li>
                            <li><a href="javascript:">电子系党支部换届选举及转正大会</a></li>
                            <li><a href="javascript:">我院健美操队惊艳亮相，搏击操双节棍大放异彩</a></li>
                            <li><a href="javascript:">院学生会召开本学期第四次部长例会</a></li>
                            <li><a href="javascript:">我们的“游戏”人生</a></li>
                            <li><a href="javascript:">院学生会为同学组织英语模拟考场</a></li>
                        </ul>
                        <ul class="swiper-slide">
                            <li><a href="javascript:">学生会第八届主席团公开述职暨换届大会顺利召开1</a></li>
                            <li><a href="javascript:">学生会第八届主席团公开述职暨换届大会顺利召开1</a></li>
                            <li><a href="javascript:">学生会第八届主席团公开述职暨换届大会顺利召开1</a></li>
                            <li><a href="javascript:">学生会第八届主席团公开述职暨换届大会顺利召开1</a></li>
                            <li><a href="javascript:">学生会第八届主席团公开述职暨换届大会顺利召开1</a></li>
                            <li><a href="javascript:">学生会第八届主席团公开述职暨换届大会顺利召开1</a></li>
                            <li><a href="javascript:">学生会第八届主席团公开述职暨换届大会顺利召开1</a></li>
                            <li><a href="javascript:">学生会第八届主席团公开述职暨换届大会顺利召开1</a></li>
                            <li><a href="javascript:">学生会第八届主席团公开述职暨换届大会顺利召开1</a></li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="main-c">
                <div class="tabs">
                    <div class="tabs-top">
                        <h3>教务通知</h3>
                        <a class="fr" href="javascript:">more</a>
                    </div>
                    <div class="tabs-content">
                        <ul>
                            <li><a href="javascript:">【转发教学部】关于2011-2012学年第一学期学生纪律检查结果</a></li>
                            <li><a href="javascript:">信息技术学院2011-2012-1学期专业课程表</a></li>
                            <li><a href="javascript:">【转发教学部】关于2011-2012学年第二学期评教通知</a></li>
                            <li><a href="javascript:">【转发教学部】关于2011-2012学年第二学期…</a></li>
                            <li><a href="javascript:">【转发教学部】关于2011年上半年办…</a></li>
                            <li><a href="javascript:">关于2011届同学领取学位英语准考证的通知</a></li>
                            <li><a href="javascript:">【转发教学部】关于调整学位英语…</a></li>
                            <li><a href="javascript:">关于《信息安全基础》临时调课的通知</a></li>
                            <li><a href="javascript:">【转发教学部】关于2007级毕业生工作日报安排</a></li>
                        </ul>
                    </div>
                </div>
                <div class="tabs">
                    <div class="tabs-top">
                        <h3>学务通知</h3>
                        <a class="fr" href="javascript:">more</a>
                    </div>
                    <div class="tabs-content">
                        <ul>
                            <li><a href="javascript:">关于信息技术学院学生会第九届主席团成员…</a></li>
                            <li><a href="javascript:">第九届团代会选举结果的通知</a></li>
                            <li><a href="javascript:">关于召开第九次团代会的通知</a></li>
                            <li><a href="javascript:">关于第九次团代会代表名单的公告</a></li>
                            <li><a href="javascript:">关于第九届团委委员候选人公示的通知</a></li>
                            <li><a href="javascript:">关于报送第九次团员代表大会代表的通知</a></li>
                            <li><a href="javascript:">关于竞选第九届团委委员的报名通知</a></li>
                            <li><a href="javascript:">关于《信息安全基础》临时调课的通知</a></li>
                            <li><a href="javascript:">关于成立第九次团代会筹备委员会的公告</a></li>
                        </ul>
                    </div>
                </div>
                <div class="students tabs">
                    <div class="tabs-top">
                        <h3>优秀毕业生</h3>
                        <a class="fr" href="javascript:">more</a>
                    </div>
                    <div class="tabs-content">
                        <ul>
                            <li>
                                <img src="images/student_1.jpg" alt="优秀毕业生"/>
                                <p>02届 韩梅梅</p>
                            </li>
                            <li>
                                <img src="images/student_2.jpg" alt="优秀毕业生"/>
                                <p>03届 韩梅梅</p>
                            </li>
                            <li>
                                <img src="images/student_3.jpg" alt="优秀毕业生"/>
                                <p>04届 韩梅梅</p>
                            </li>
                            <li>
                                <img src="images/student_4.jpg" alt="优秀毕业生"/>
                                <p>05届 韩梅梅</p>
                            </li>
                            <li>
                                <img src="images/student_5.jpg" alt="优秀毕业生"/>
                                <p>06届 韩梅梅</p>
                            </li>
                            <li>
                                <img src="images/student_6.jpg" alt="优秀毕业生"/>
                                <p>07届 韩梅梅</p>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="main-r">
                <div class="motto tabs">
                    <img src="images/motto.png" alt="校训"/>
                </div>
                <div class="students tabs" style="margin-bottom:2px;">
                    <div class="tabs-top">
                        <h3>学生作品</h3>
                        <a class="fr" href="javascript:">more</a>
                    </div>
                    <div class="tabs-content">
                        <img src="images/student_works.png" alt="学生作品"/>
                    </div>
                </div>
                <div class="link">
                    <a href="javascript:">学 院 资 源  ﹀<span></span>
                        <ul class="sub-menu">
                            <img src="images/dot2.jpg" alt="dot"/>
                            <li><a href="javascript:">教务通知</a></li>
                            <li><a href="javascript:">资料下载</a></li>
                            <li><a href="javascript:">院务管理系统</a></li>
                            <li><a href="javascript:">毕业生信息管理系统</a></li>
                            <li><a href="javascript:">家校互动服务平台</a></li>
                        </ul>
                    </a>
                    <a href="javascript:" style="margin-left:60px;"><span>招生信息专题网站</span></a>
                </div>
            </div>
            <div class="lines">
                <img src="images/lines.png" alt=""/>
            </div>
            <div class="bottom">
                <p>
                    <img src="images/badge.png" alt="校徽" style="width:32px;"/>
                    <span>2001-2011 &copy 北京师范大学珠海分校 信息技术学院 版权所有</span>
                </p>
                <p>地址：广东省 珠海市 香洲区 金凤路18号 北京师范大学珠海分校 邮编：519085 | <a href="javascript:">管理登录</a></p>
                <p>
                    <span>Design and Code by osmn00</span>
                    <select name="school-nav" id="school-nav">
                        <option value="">--院际导航--</option>
                        <option value="math">--数学院--</option>
                        <option value="business">--商学院--</option>
                        <option value="physics">--物理学院--</option>
                    </select>
                </p>
            </div>
        </div>
    </div>
</body>
<script src="js/swiper.min.js"></script>
<script>
    var swiper = new Swiper('#swiper-container', {
        loop:true,
        autoplay:3000,
        autoplayDisableOnInteraction:false,
        pagination: '.swiper-pagination',
        paginationClickable: true,
        paginationBulletRender: function (swiper, index, className) {
            return '<span class="' + className + '">' + (index + 1) + '</span>';
        }
    });

    var xuezidongtai = new Swiper('#xuezidongtai',{
        pagination: '.swiper-pagination1',
        paginationClickable: true,
        paginationBulletRender: function (swiper, index, className) {
            if(index == 0){
                return '<span class="' + className + '">学子风采</span>';
            }else{
                return '<span class="' + className + '">留学动态</span>';
            }
        }
    })
</script>

</html>
