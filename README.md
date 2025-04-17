中文文本分析相关资源汇总
- [LIST | 社科(经管)数据挖掘文献资料汇总](https://textdata.cn/blog/the_text_analysis_list_about_ms/)
- [LIST | 可供社科(经管)领域使用的数据集汇总](https://textdata.cn/blog/datasets_available_for_management_science/)
- [教程 | 使用Ollama与大模型将文本数据转化为结构化数据](https://textdata.cn/blog/2025-02-14-using-online-large-model-api-to-transform-text-data-into-structured-data/)
- [https://textdata.cn/](https://textdata.cn/blog/)
- 
<br><br>

# 1. Python库

| 项目                                  | 地址                                                      | 简介                                                         |
| ------------------------------------- | --------------------------------------------------------- | :----------------------------------------------------------- |
| jieba分词                             | https://github.com/fxsjy/jieba                            | 中文分词库                                                   |
| **cntext开源版**                             | https://github.com/hidadeng/cntext                    | 中文文本情感分析、情绪分析库                                 |
| **cntext2.x**                             | https://cntext.readthedocs.io/zh-cn/latest//                    | 增加了更多新功能， 如无必要可先用开源版cntext                                 |
| multistop                       | https://github.com/hidadeng/multistop            | 停用词表，支持中英法德等15种语言                                            |
| cnsenti                               | https://github.com/hidadeng/cnsenti                     | 中文文本情感分析、情绪分析库                                 |
| tomotopy                                 | https://github.com/bab2min/tomotopy                     | 最快的主题模型，C的速度                        |
| 快速构建专属领域中文情感词典          | https://github.com/hidadeng/wordexpansion               | 使用SO_PMI互信息算法简单快速构建不同领域(手机、汽车等)的专业情感词典 |
| eventextraction                       | https://github.com/hidadeng/eventextraction             | 计算文本逻辑性                                               |
| 中文复杂事件的概念与显式模式          | https://github.com/hidadeng/eventextraction             | 中文复合事件的概念与显式模式，包括条件事件、因果事件、顺承事件、反转事件等事件抽取，并形成事理图谱。 |
| 中文信息抽取工具                      | https://github.com/fighting41love/cocoNLP                 | 从中文文本数据中抽取出结构化的信息，如时间、手机号、运营商、邮箱、地址、人名、身份证 |
| 图片识别                              | https://github.com/breezedeus/cnocr                       | 识别出图片中的中文文本                                       |
| label-studio多媒体标注工具            | https://github.com/heartexlabs/label-studio               | 可对文本、图片、音频和视频数据进行标注                       |
| 中文可读性                            | https://github.com/cdimascio/py-readability-metrics       | 可读性算法包括Flesch-Kincaid Grade Level, Gunning Fog, ARI, Dale Chall, SMOG |
| Synonyms                              | https://github.com/huyingxi/Synonyms                      | 用于自然语言理解的很多任务：文本对齐，推荐算法，相似度计算，语义偏移，关键字提取，概念提取，自动摘要，搜索引擎等。 |
| SpaCy 中文模型                        | https://github.com/howl-anderson/Chinese_models_for_SpaCy | SpaCy 中文模型                                               |
| Scattertext可视化                     | https://github.com/JasonKessler/scattertext               | 能否分析出某个类别的文本与其他文本的用词差异；简单修改后可支持中文 |
| HarvestText文本挖掘和预处理工具       | https://github.com/blmoistawinde/HarvestText              | 文本挖掘和预处理工具（文本清洗、新词发现、情感分析、实体识别链接、句法分析等），无监督或弱监督（种子词）方法 |
| 开源金融大数据                        | https://github.com/PKUJohnson/OpenData                    | 股票、基金、期货、宏观等金融数据。还有非金融数据，如空气质量、高考录取分、院线票房等非金融数据 |
| 中日韩分词                            | https://github.com/jeongukjae/python-mecab                | 中日韩分词工具                                               |
| 汉字数字(中文数字)-阿拉伯数字转换工具 | https://github.com/Wall-ee/chinese2digits                 | 最好的汉字数字(中文数字)-阿拉伯数字转换工具。                |
| 中文地址提取工具                           | https://github.com/shibing624/addressparser     | 中文地址提取工具，支持中国三级区划地址（省、市、区）提取和映射，支持地址热力图绘制。 |
| 中文公司名称分词工具                           | https://github.com/shibing624/companynameparser    | 中文公司名称分词工具，支持公司名称中的地名，品牌名（主词），行业词，公司名后缀提取。 |


<br>
<br>

# 2. 语料(数据)

| 资源名             | 地址                                                 | 介绍                                                         |
| ------------------ | ---------------------------------------------------- | ------------------------------------------------------------ |
| 微信公众号语料库   | https://github.com/SophonPlus/ChineseNlpCorpus       | 搜集、整理、发布 中文 自然语言处理 语料/数据集，与 有志之士 共同 促进 中文 自然语言处理 的 发展。 |
| 中文公司名语料库   | https://github.com/wainshine/Company-Names-Corpus    | 公司简称,缩写,品牌词,企业名。可用于中文分词、机构名实体识别。 |
| 微信公众号语料库   | https://github.com/nonamestreet/weixin_public_corpus | 数据量3G；纯文本,每行一篇，JSON格式。name是微信公众号名字，account是微信公众号ID，title是题目，content是正文。 |
| 多语言音频数据     | https://voice.mozilla.org/en/datasets                | 多种语言音频数据，包括来自42,000名贡献者超过1,400小时的语音样本，涵github |
| 知识问答           | https://github.com/liuhuanyong/MiningZhiDaoQACorpus  | 百度知道问答语料库，包括超过580万的问题，938万的答案，5800个分类标签。基于该问答语料库，可支持多种应用，如闲聊问答，逻辑挖掘。 |
| 中文任务基准测评   | https://github.com/CLUEbenchmark/CLUE                | 中文语言理解测评基准，包括代表性的数据集、基准(预训练)模型、语料库、排行榜 |
| 中文突发事件语料库 | https://github.com/shijiebei2009/CEC-Corpus          | 中文突发事件语料库（Chinese Emergency Corpus）-上海大学-语义智能实验室 |
|                    |                                                      |                                                              |
|                    |                                                      |                                                              |



<br>
<br>

# 3. 预训练模型

使用 cntext2.x 训练得到的中文预训练模型资源，汇总如下

对中文语料进行了近义测试和类比测试， 其中斯皮尔曼秩系数(Spearman's Rank Coeficient) 取值[-1,1], 取值越大表示模型越符合人类的认知。

类比测试有首都国家（CapitalOfCountries）、省会省份（CityInProvince）、家人关系（FamilyRelationship）、社会科学(管理、经济、心理等 SocialScience) 的类别准确率测试。

<br>

| 数据集                                                                                              | 词向量                                                                                                                    | 网盘                                                      | 斯皮尔曼秩系数 | 首都国家(%) | 省会省份(%) | 家人关系(%) | 社会科学(%) |
| --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- | -------------- | ----------- | ----------- | ----------- | ----------- |
| [中国政府工作报告](https://textdata.cn/blog/2023-12-17-gov-anual-report-dataset/)                   | **_人民政府(国省市)工作报告-GloVe.200.15.bin_**                                                                           | https://pan.baidu.com/s/1IdK8RU9L8mp6I2nhcoSmyA?pwd=ht2s  | 0.38           | 30.73       | 98.86       | 0.00        | 0.00        |
| [中国政府工作报告](https://textdata.cn/blog/2023-12-17-gov-anual-report-dataset/)                   | **_人民政府(国省市)工作报告-Word2Vec.200.15.bin_**                                                                        | https://pan.baidu.com/s/1GoTjMbUcYS4jN6w4GqlqBA?pwd=qb5b  | 0.35           | 30.06       | 96.00       | 0.00        | 16.67       |
| [中国裁判文书网](https://textdata.cn/blog/2023-05-07-china-law-judgment-documents-datasets/)        | **_裁判文书-GloVe.200.15.bin_**                                                                                           | https://pan.baidu.com/s/1a0Fisvnkl8UaQZrHP7olCQ?pwd=8w49  | 0.37           | 7.69        | 98.86       | 75.53       | 25.00       |
| [留言板](https://textdata.cn/blog/2023-12-22-renmin-gov-leader-comment-board/)                      | **_留言板-Word2Vec.200.15.bin_**                                                                                          | https://pan.baidu.com/s/1n7vwCOBnrye1CYrt_IBqZA?pwd=9m42  | 0.45           | 19.33       | 100         | 61.40       | 20%         |
| [A 股年报](https://textdata.cn/blog/2023-03-23-china-a-share-market-dataset-mda-from-01-to-21/)     | **_mda01-23-GloVe.200.15.bin_**                                                                                           | https://pan.baidu.com/s/1vXvbomHjOaFBeEz7GV0R6A?pwd=y6hd  | 0.34           | 78.13       | 100         | 0           | 37.50       |
| [A 股年报](https://textdata.cn/blog/2023-03-23-china-a-share-market-dataset-mda-from-01-to-21/)     | **_mda01-23-Word2Vec.200.15.bin_**                                                                                        | https://pan.baidu.com/s/11V1RyqH_cKE9eju0Mm-1TQ?pwd=kcwx  | 0.41           | 27.27       | 97.14       | 10          | 44.44       |
| [港股年报](https://textdata.cn/blog/2024-01-21-hk-stock-market-anual-report/)                       | **_英文港股年报-Word2Vec.200.15.bin_**                                                                                    | https://pan.baidu.com/s/1ISGAoZnA_1Ben6M2DCliOQ?pwd=nagx  | ---            | ---         | ---         | ---         | ---         |
| [港股年报](https://textdata.cn/blog/2024-01-21-hk-stock-market-anual-report/)                       | **_中文港股年报-Word2Vec.200.15.bin_**                                                                                    | hhttps://pan.baidu.com/s/1smMcrPtIP8g635YABCodig?pwd=sjdj | 0.35           | 25.20       | 79.43       | 18.59       | 25          |
| [人民日报](https://textdata.cn/blog/2023-12-14-daily-news-dataset/)                                 | [年份 Word2Vec](https://textdata.cn/blog/2023-12-28-visualize-the-culture-change-using-people-daily-dataset/)             | https://pan.baidu.com/s/1Ru_wxu9egsmhM7lATjSlgQ?pwd=bcea  |                |             |             |             |             |
| [人民日报](https://textdata.cn/blog/2023-12-14-daily-news-dataset/)                                 | [对齐模型 Aligned_Word2Vec](https://textdata.cn/blog/2023-12-28-visualize-the-culture-change-using-people-daily-dataset/) | https://pan.baidu.com/s/1IVgP0MyQpez0hpoJyEyFdA?pwd=7qsu  |                |             |             |             |             |
| [专利申请](https://textdata.cn/blog/2023-04-13-3571w-patent-dataset-in-china-mainland/)             | **_专利摘要-Word2Vec.200.15.bin_**                                                                                        | https://pan.baidu.com/s/1FHI_J7wU9eQGRckD12QB5g?pwd=6rr2  | 0.46           | 3.78        | 25.14       | 33.33       | 37.50       |
| [专利申请](https://textdata.cn/blog/2023-11-20-word2vec-by-year-by-province/)                       | **_province_w2vs 分省份训练词向量_**                                                                                      | https://pan.baidu.com/s/1eBFTIZcv2DWssLiaRnCqZQ?pwd=ikpu  |                |             |             |             |             |
| [专利申请](https://textdata.cn/blog/2023-11-20-word2vec-by-year-by-province/)                       | **_year_w2vs 分年份训练词向量_**                                                                                          | https://pan.baidu.com/s/1lrVkML92cVJdHQa1HQyAwA?pwd=4gqa  |                |             |             |             |             |
| 大众点评评论语料                                                                                    | **_大众点评-评论-Word2Vec.200.15.bin_**                                                                                   | https://pan.baidu.com/s/15He728XGzoXDFYrUWDTaqQ?pwd=eg6x  | 0.34           | 50.31       | 89.71       | 70.00       | 0.00        |
| 中文歌词                                                                                            | **_中文歌词-Word2Vec.200.15.bin_**                                                                                        | https://pan.baidu.com/s/1h1g1mOACmpCwn5pz8jR3vQ?pwd=ub2z  | 0.06           | 0.00        | 0.00        | 0.9         | 0.00        |
| 英文歌词                                                                                            | **_英文歌词-Word2Vec.200.15.bin_**                                                                                        | https://pan.baidu.com/s/1ycy-BTSa8zqW_xbIoshy6Q?pwd=hu1v  |                |             |             |             |             |
| [黑猫消费者投诉](https://textdata.cn/blog/2025-03-05-consumer-complaint-dataset/)                   | **_消费者黑猫投诉-Word2Vec.200.15.bin_**                                                                                  | https://pan.baidu.com/s/1FOI2BIVRojOswdKfqaNbsw?pwd=catc  | 0.32           | 16.18       | 68          | 28.57       | 0.00        |
| [豆瓣影评](https://textdata.cn/blog/2024-04-16-douban-movie-1000w-ratings-comments-dataset)         | **_douban-movie-1000w-Word2Vec.200.15.bin_**                                                                              | https://pan.baidu.com/s/1uq6Ti7HbEWyT4CgktKrMng?pwd=63jg  | 0.43           | 39.02       | 28.57       | 92.65       | 25.00       |
| [B 站](https://textdata.cn/blog/2023-11-12-using-100m-bilibili-user-sign-data-to-training-word2vec) | **_B 站签名-Word2Vec.200.15.bin_**                                                                                        | https://pan.baidu.com/s/1OtBU9BzitcNxkmPzhzH6FQ?pwd=m3iv  | 0.34           | 25.56       | 33.71       | 44.17       | 0.00        |
| [B 站弹幕](https://github.com/Viscount/IUI-Paper)| **_B 站弹幕-Word2Vec.200.15.bin_**        |   https://pan.baidu.com/s/1LNDLed5uP3KnUMmrKf_uhg?pwd=x4t8  | 0.42           | 11.67       | 65.81       | 44.17       | 25.00       |



<br>
<br>


# 4. 课程

如果您是经管人文社科专业背景，编程小白，面临海量文本数据采集和处理分析艰巨任务，可以参看 [《Python实证指标构建与文本分析》](https://textdata.cn/blog/management_python_course/)视频课。作为文科生，一样也是从两眼一抹黑开始，这门课程是用五年时间凝缩出来的。自认为讲的很通俗易懂 o(*￣︶￣*)o，

- Python 语法入门
- Python网络爬虫
- pandas数据操作
- 文本分析(词典法)
- 文本分析 (机器学习)
- 词嵌入与态度认知


感兴趣的童鞋不妨戳一下 [《Python实证指标构建与文本分析》](https://textdata.cn/blog/management_python_course/) 进来看看~

[![](img/management_data_mining_with_python_course2.png)]( https://textdata.cn/blog/management_python_course/ )


<br>
<br>

# 5. 更多

- [B站:大邓和他的python](https://space.bilibili.com/122592901/channel/detail?cid=66008)

- 公众号：大邓和他的python




![](img/大邓和他的Python.png)
