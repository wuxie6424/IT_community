# IT_community
基于内容推荐的专业IT社区设计与实现

项目要求实现的都已实现。    


********************************************************
任务书的内容、要求:  
2020-2021（2）  
课题名称	基于内容推荐的专业IT社区设计与实现  
学生姓名	XXX(组长)、XXX、XXX、XXX、XXX、XXX	专业班级	17级软工    班	组号	第    组  
主要内容	主要内容：  
借鉴中国最大的软件开发者联盟论坛CSDN，结合Java Web开发框架和内容推荐等关键技术，设计和实现一套专业性IT技术社区，为广大软件开发爱好者们提供学习、技术交流以及趣事分享等服务，打造一个更有针对性和时效性的网上大家园。要求用户注册和登录社区论坛后可以查看自己的论坛等级排名，可以根据最新或者最热查看自己感兴趣的内容。同时论坛可以根据用户浏览的内容结合内容推荐算法，向其自动推送可能感兴趣的帖子或者主体内容。  
一、主要模块：  
1)注册登录：  
用户可以根据短信验证的方式的进行注册或者登录论坛，当然也可以用账号和账号密码验证的方式注册或者登录网站。  
2)我要发帖：用户可以在此模块发布帖子，为了防止发帖刷分，半小时之内最多只能发布一个帖子。  
3)帖子导航:  
根据内容的不同将帖子划分在不同的模块，从而达到方便用户进行查找的目的（模块分类，例如：Web前端、编程语言、数据库技术、操作系统、云计算、大数据.....）。在每个子模块下，用户都可以根据最新发布或者最热帖子对当前模块的帖子进行排序同时以20条帖子为一页对所有的帖子进行分页管理，方便用户查找所需信息。用户可以在每一个帖子下面发表自己的评论，可以与作者或者其他评论人进行互动交流，可以收藏帖子方便用户以后浏览，为了防止恶意刷分，2分钟内禁止连续发表评论。用户可以根据精确查询或者模糊查询输入关键字，查找所需要的帖子。     
4)论坛牛人：  
本模块可划分三个子模块：每日一帖、论坛牛人、本周牛人、论坛牛帖、本周牛帖。在每日一贴子模块，所有的用户都可以在此帖子中随意发言，需要注意的的是本模块发表的评论不计入加分规则中。在本模块用户可以吐槽一下周围同学、可以是新手求帮助、可以是设法认识一些同行、可以是分享自己的当天心情等等，畅所欲言。同时，论坛设置敏感词汇过滤功能，不允许发布不符合社会主义现代观念的言论。论坛牛人是将所有用户中积分排名前十的用户挂在论坛此模块，类似于一种夸奖的手法，表示赞同，让其他用户引以为榜样。本周牛人是取本周积分排名前十的用户。论坛牛帖，是将所有的帖子中排名浏览量排名前十的帖子置顶，本周牛帖是将本周点击量排名前十的帖子置顶。设置本模块的主要目的在于，用这种类似于奖赏机制，激起其他用户在本论坛的使用量以及在发帖的时候更加的用心提高帖子的质量，同时让更多的人认识这些技术比较好的同学和大牛们。
补充：  
积分获取规则：没发布一条帖子并且拥有其他用户的超过20条评论可以获得10积分，评论他人帖子并且评论超过15个字可以获得1积分每个帖子最多可获得5积分，上过一次本周牛人榜可以获得20积分，上过一次论坛牛人榜可以获得40积分，榜单没周更新一次。  
积分扣除规则：发表不好言论的管理员可以接进行扣除50积分（最少是0积分），若多次发表不好言论管理员可以直接冻结此账号并且不可再使用。  
5)帖子推荐：  
基于内容推荐算法，根据用户所浏览的帖子、收藏的帖子推荐一些用户可能感兴趣的帖子，以方便用户浏览查阅。  
6)我的论坛：  
修改个人资料、我的积分、我发布的帖子、我回复的帖子、我收藏的帖子。  
7)服务专区：  
社区公告、积分规则查看、论坛问题反馈专区、论坛帮助。  
二、管理员功能：  
1)管理员的注册登录注销退出。  
2)菜单管理：可以对导航栏中的子模块进行管理。  
3)帖子管理：可以对所有用户发布的所有帖子进行管理。  
4)评论管理：可以对所有的评论进行管理，若发现有用户发布不好的言论可以进行扣除积分。  
5)对论坛的各种文档进行管理：可以修改积分规则、修改帮助文档、修改社区公告、对用户的反馈信息进行核实、做出相应的处理并回复用户。  
6)公共信息维护：前台注册用户管理、后台用户个人信息维护，修改密码、基础数据配置、用户权限管理。  
进度要求	（遵照学校网上教学校历计算）  
第1周开题  
第5周考核  
主要参考文献及  
资料收集	[1] 和璇.MVC模式在JAVA WEB中的应用[J]. 计算机光盘软件与应用，2014,（16）：311-312.  
[2] 陈甫.Bootstrap3在Java Web项目中的应用[J]. 电脑编程技巧与维护，2014,（17）：27-28+32.  
[3]傅鹏,殷旻昊.基于SpringMVC+Spring+Mybatis+Ajax技术的科研管理系统设计[J].软件导刊,2009,8(1):135-136.  
[4] 聂帅华.基于内容推荐/协同过滤推荐算法的智能交友网站的设计&实现[D]. 华中师范大学，2015.  
[5] 贾忠涛.基于协同过滤算法的电影个性化推荐系统设计与实现[J]. 软件导刊，2015年01期.  
[6] 王国霞,刘贺平.个性化推荐系统综述[J].计算机工程与应用,2012年07期.  
  
起止日期	2020.02.17---2020.03.13  
备注	  
  
