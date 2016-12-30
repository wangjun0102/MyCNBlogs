* 数据挖掘岗面经：

```html
   (一) 数据挖掘概念:
     数据挖掘  =  业务知识  +  自然语言处理技术（ NLP ） +  计算机视觉技术（ CV ） +  机器学习 / 深度学习（ ML/DL ）
   (1) 其中业务知识具体指的是个性化推荐，计算广告，搜索，互联网金融等； NLP ， CV 分别是处理文本，图像视频数据的领域技术，
   可以理解为是将非结构化数据提取转换成结构化数据；最后的 ml/dl 技术则是属于模型学习理论；
   (2) 在选择岗位时，各个公司都没有一套标准的称呼，但是所做的事情无非 2 个大方向，一种是主要钻研某个领域的技术，
   比如自然语言处理工程师，计算机视觉工程师，机器学习工程师等；
   一种是将各种领域技术应用到业务场景中去解决业务需求，比如数据挖掘工程师，推荐系统工程师等；
   具体的称呼不重要，重要的是平时的工作内容；
   (3) PS ：在互联网行业，数据挖掘相关技术应用比较成功的主要是推荐以及计算广告领域，而其中涉及到的数据主要也是文本，
   所以 NLP 技术相对来讲比较重要，至于 CV 技术主要还是在人工智能领域（无人车，人脸识别等）应用较多.
   (4) 3 种基本能力分别是业务经验，算法能力与工程能力.
   
 (二) 入门
   1. 工程能力:
   (1) 编程基础：需要掌握一大一小两门语言，大的指 C++ 或者 JAVA ，小的指 python 或者 shell 脚本；需要掌握基本的数据库语言.
     建议： MySQL + python + C++ ；语言只是一种工具，看看语法就好.
     推荐书籍：《C++ primer plus》
   (2) 开发平台：Linux.
     建议：掌握常见的命令，掌握 Linux 下的源码编译原理.
     推荐书籍：《鸟哥的 Linux 私房菜》
   (3) 数据结构与算法分析基础：掌握常见的数据结构以及操作（线性表，队，列，字符串，树，图等），
     掌握常见的计算机算法（排序算法，查找算法，动态规划，递归等）.
     建议：多敲代码，多上 OJ 平台刷题.
     推荐书籍：《大话数据结构》《剑指 offer》
   (4) 海量数据处理平台： hadoop（mr计算模型， java开发）或者spark（rdd计算模型， scala开发），重点推荐后者.
     建议：主要是会使用，有精力的话可以看看源码了解集群调度机制之类的.
     推荐书籍：《大数据 spark 企业级实战》
     
   2.算法能力:
   (1) 数学基础：概率论，数理统计，线性代数，随机过程，最优化理论.
     建议：这些是必须要了解的，即使没法做到基础扎实，起码也要掌握每门学科的理论体系，涉及到相应知识点时通过查阅资料可以做到无障碍理解.
   (2) 机器学习 / 深度学习：掌握 常见的机器学习模型（线性回归，逻辑回归， SVM ，感知机；决策树，随机森林， GBDT ， XGBoost ；
   贝叶斯， KNN ， K-means ， EM 等）；掌握常见的机器学习理论（过拟合问题，交叉验证问题，模型选择问题，模型融合问题等）；
   掌握常见的深度学习模型（ CNN ， RNN 等）.
     建议：这里的掌握指的是能够熟悉推导公式并能知道模型的适用场景.
推荐书籍：《统计学习方法》《机器学习》《机器学习实战》《 UFLDL 》
   (3) 自然语言处理：掌握常见的方法（ tf-idf ， word2vec ， LDA ）.
   
   3.业务经验:
   (1) 了解推荐以及计算广告相关知识.
   推荐书籍：《推荐系统实践》《计算广告》
   (2) 通过参加数据挖掘竞赛熟悉相关业务场景，常见的比赛有 Kaggle ，阿里天池， datacastle 等.
   PS: 以上都是一些入门级别的介绍，在长期的学习中，应该多看顶会 paper ，多读开源代码，多学习优秀解决方案.
   
```

（三）   求职

1.        简历

（ 1 ）格式：个人信息（姓名，联系方式，教育背景，求职意向，照片可有可无） +  竞赛经历 +  实习经历  +  项目经历  +  掌握技能  +  获奖情况；

PS: 最好写成一页；

（ 2 ）加分：博客， github ，竞赛 top10 ，顶会 paper ；

PS: 牛逼的简历可以让你有更多的面试机会，更关键的是让面试官在面试时潜意识给你打高分，当然前提是简历要真实，所以平时得为了牛逼的简历多做准备工作；

2.        海投

（ 1 ）国内设有该岗位且还不错的公司：

百度，腾讯，阿里，网易（互联网，游戏，有道），华为，今日头条，滴滴研究院，一点咨讯， 360 ，美团等；

（ 2 ）如果选择留在广东深圳发展，就业的机会比较少，比较好的主要就是百度深研，腾讯总部，华为深圳，京东好像在深圳也有个做数据挖掘的团队；（楼主倾向去深圳发展）

（ 3 ）个人建议在 3 月份的时候可以通过实习生的身份进入相关企业，争取实习生留用；一般企业给应届生的 hc 分配比例大概是实习生留用：校招提前批：校招正式 =4 ： 3 ： 3 ，实习生留用相对比较容易；

（ 4 ）一般投递简历时，尽量联系公司内部的师兄师姐或者熟人，帮忙将简历直接给到团队 leader 手中，这样做的好处是可以同时面试同个公司的多个团队，前提是简历在公司校招系统未被锁定的前提下，具体情况多咨询公司内部熟人，在求职过程中，信息来源非常重要，一定要注意这点，不然会踩很多坑；

（ 5 ）加入各种求职交流群，多认识些人，共享资源；

（ 6 ）投简历时候尽量内推，很多公司内推可以免笔试；

PS ：笔试纯属看 rp ，总之就是多刷题，上牛客网多练练并针对性复习就好；

3.        面试

（ 1 ）一般该岗位的面试起码都有 3 轮， 2 轮技术面， 1 面 hr 面， hr 面主要看情商，这里不多说； 2 轮技术面的区别就是越到后面面试官的级别越高，所以面试的风格也可能越偏向于技术视野等一些吹水的话题上；

（ 2 ）一般技术面有以下一些环节：自我介绍，项目介绍，算法提问（推公式），数据结构提问（写代码）；

1 ）自我介绍：一般尽量简短，主要讲清楚自己的研究方向，所取得成就以及优势所在即可；

2 ）项目介绍：简历上的项目一定要熟悉，介绍时候分三部曲：项目背景，项目方案，项目成果；对项目中涉及到的一些技术点一定要很熟悉；

3 ）算法提问：一般是问常见机器学习模型原理或者一些机器学习常见问题的解决方案（比如正负样本不平衡之类的），所以常见的机器学习模型一定要很清楚原理，必须会推公式，能知道工程实现的一些 trick 的话，那你就离 sp 不远了；

4 ）数据结构提问：常见的数据结构一定要掌握，基础的代码一定要会手写（快排，冒泡，堆排，归并排序，二分查找，二叉树的遍历，二叉树增删查改）；剑指 offer 的题目要会；有精力的话可以刷下 leetcode ；

（ 3 ）面试的时候多准备一些素材，在面试过程中主动引导面试官提问，比如面试官让你讲解 gbdt 原理时，这会你可以跟他说一般说起 gbdt ，我们都会跟 rf 以及 xgboost 一块讲，然后你就可以主动地向面试官输出你的知识；面试并不是死板地你问我答，而是一种沟通交流，所以尽可能地把面试转化成聊天式的对话，多输出自己一些有价值的观点而不是仅仅为了回答面试官的问题；

（ 4 ）在面试过程中，除了基础的东西要掌握，可以适当地向面试官展示你的一些其他的亮点，比如跟面试官谈论某些最近 paper 的进展以及一些技术方面的想法等，突出自己的与众不同；

（ 5 ）不同公司的面试风格都略有不同：

1 ）百度：技术派，现场面，最大的风格就是写代码， 2 面技术加一面经理面，技术面必写代码；

2 ）阿里：内推可以电话面，主要是聊项目跟问一些基础的数据结构方面的知识，看看剑指 offer 一般可以应付；

3 ）腾讯：内推可以电话面，主要聊项目跟推公式；

4 ）华为：主要聊项目，智力题以及聊价值观之类的东西；

5 ）滴滴研究院：百度系，面试风格跟百度差不多；

（ 6 ）常见面试题（由于有的面试时间较久，主要靠记忆写下来）

1 ）几种模型（ svm ， lr ， gbdt ， em ）的原理以及公式推导；

2 ） rf ， gbdt 的区别； gbdt ， xgboost 的区别（烂大街的问题最好从底层原理去分析回答）；

3 ）决策树处理连续值的方法；

4 ）特征选择的方法；

5 ）过拟合的解决方法；

6 ） kmeans 的原理，优缺点以及改进；

7 ）常见分类模型（ svm ，决策树，贝叶斯等）的优缺点，适用场景以及如何选型；

8 ） svm 为啥要引入拉格朗日的优化方法；

9 ）假设面试官什么都不懂，详细解释 CNN 的原理；

10 ）海量的 item 算文本相似度的优化方法；

11 ）梯度下降的优缺点；

12 ） em 与 kmeans 的关系；

13 ） L1 与 L2 的区别以及如何解决 L1 求导困难；

14 ）如何用尽可能少的样本训练模型同时又保证模型的性能；

15 ）解释 word2vec 的原理以及哈夫曼树的改进；

16 ）对推荐算法的未来看法；

17 ）在模型的训练迭代中，怎么评估效果；

18 ）有几个 G 的文本，每行记录了访问 ip 的 log ，如何快速统计 ip 出现次数最高的 10 个 ip ；如果只用 linux 指令又该怎么解决；

19 ）一个绳子烧完需要 1 个小时，假设所有绳子的材质都不一样，也不均匀，怎么取出 1 小时加 15 分钟；

20 ）假设有个 M*N 的方格，从最左下方开始往最右上方走，每次只能往右或者往上，问有多少种走法，假设中间有若干个格子不能走，又有多少种走法；

21 ）实现 hmm 的状态转移代码；

22 ）最短路径代码；

23 ）拼车软件是如何定价的以及如何优化；

24 ） 100 张牌，每次只能抽一张，抽过的牌会丢掉，怎么选出最大的牌；

25 ）怎么预测降雨量；

26 ） kmeans 代码；

27 ） mr 方案解决矩阵相乘的代码；

28 ） sql 语句的一些优化技巧；

29 ）关于集群调度的一些经验 trick 掌握多少；

30 ）设计一个系统可以实时统计任意 ip 在过去一个小时的访问量；

31 ）设计 LRU 系统；