#本仓库包含两个项目：分别是电影数据分析和电商销售分析

#电影数据分析项目：
本项目是一个关于互联网电影的数据分析，数据来源于互联网电影资料库（IMDb）,资料中包括了影片的信息、演员、片长、内容介绍、分级、评论等。 数据源：movie_metadata.csv 字段解释： 电影描述字段：movie_title 电影题目 language 语言 country 国家 content_rating 电影分级 #title_year 电影年份 color 色彩 duration 片长 genres 电影体裁/类型 plot_keywords 剧情关键字

电影制作字段：budget 制作成本 gross 总收入 aspect_ratio 画布比例

电影阵容字段：facenumber_in_poster 海报中的人脸数量 director_name 导演 director_facebook_likes 导演facebook粉丝数 actor_1_name 主演1姓名 actor_1_facebook_likes 主演1facebook粉丝数 actor_2_name 主演2姓名 actor_2_facebook_likes 主演2facebook粉丝数 actor_3_name 主演3姓名 actor_3_facebook_likes 主演3facebook粉丝数

电影评论字段：num_voted_users 投票人数 num_user_for_reviews 用户的评论数量 num_critic_for_reviews 评论家评论数 movie_facebook_likes 脸书上被点赞的数量 cast_total_facebook_likes Facebook上偷喜爱的总数 movie_imdb_link 电影数据链接 imdb_score imdb上的评分

本分析过程主要如下： 数据读取、数据清洗、数据分析


#电商销售数据分析
数据源：dataset.csv

字段说明： ROW ID 行编号 ORDER ID 订单ID ORDER DATE 订单日期 SHIP DATE 发货日期 SHIP MODE 发货模式 CUSTOMER ID 客户ID CUSTOMER NAME 客户姓名 SEGMENT 客户类别 CITY 客户所在城市 STATE 客户所在州 COUNTRY 客户所在国家 POSTAL CODE 邮编 MARKET 商店所属区域 REGION 商店所属洲 PRODUCT ID 产品ID CATEGORY 产品类别 SUB-CATEGORY 产品子类别 PRODUCT NAME 产品名称 SALES 销售额 DISCOUNT 折扣 PROFIT 利润 SHIPPNG COST 发货成本 ORDER PRIORITY 订单优先级

主要分析了电商的销售数据、用户分析(RFM)模型
