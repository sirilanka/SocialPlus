#社交网络分析平台

##功能

1. 支持各大常见社交平台接入，之后可以进行相应的统计分析。
2. 统计分析包括（以微博为例），包括以下方面
	1. 微博转发数、评论数、点赞数
	2. 微博转发人群性别比例
	3. 微博以时间线为横坐标，转发数为纵坐标折线图
	4. 微博地理位置（省份）为权的地理位置统计
	5. 微博转发历史无向图（以转发者为节点）
	6. 微博关键字分析
	7. 微博热点（可选）
3. 接入方式：
	1. 统一的对外API
	2. 社交平台本身提供相应API的，直接调用
	3. 不支持API的，通过爬虫等方式手动获取
4. 目标支持社交平台
	1. 微博
	2. 腾讯微博
	3. 人人
	4. Facebook
	5. Twitter
5. 实现方式
	1. J2EE
	2. 数据库MySQL/LevelDB/MongoDB?
	3. Redis
	4. 关键词分析：LDA
