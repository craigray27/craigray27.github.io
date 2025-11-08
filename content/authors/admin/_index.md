---
# Display name
title: 雷志远

# Name pronunciation (optional)
name_pronunciation:

# Full name (for SEO)
first_name: Craig
last_name: Ray

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: 数据分析师

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: 云南明博会计师事务所

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:eugray@hotmail.com'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/craigray27
    
interests:
  - Artificial Intelligence
  - 徒步
  - 数学

education:
  - area: MSc Finance And Computing Mathematics
    institution: University Of Nottingham
    date_start: 2021-09-01
    date_end: 2023-03-31
    summary: |
      主要研究AI技术在金融最优化控制方向的应用以及图神经网络（GNN）在风险传染方向上的应用。在期间，在导师Reuben O'dea的指导下共同完成了金融拆借风险的网络传染模型构建，利用Graph Embedding将网络结构转换为向量，在下游学习高风险的网络结构特征。
    button:
      text: 'Read Thesis'
      url: /publication/conference-paper/
  - area: BSc Math And Applied Mathematics
    institution: 上海财经大学
    date_start: 2017-09-01
    date_end: 2021-07-01
    summary: |
      GPA: 3.2/4.0
    
      Courses included:
      - Optimization, Numerical Computation
      - Financial Stochastic Processes, Econometrics
      - Coding, Big Data, Machine Learning
    button:
      text: 'Read Thesis'
      url: /publication/dissetation/

work:
  - position: 数据分析组组长
    company_name: 云南明博会计师事务所
    company_url: ''
    company_logo: ''
    date_start: 2023-07-01
    date_end: ''
    summary: |2-
      Experiences include:
      -   从事数据分析、AI训练相关工作，包括大数据清洗、数据库（ORACLE）的搭建与日常运维、架构大数据系统Hadoop+Spark、根据客户需要训练神经网络、建立数据管理系统、数据可视化展示并撰写数据分析报告。
      -   主持构建青海省失业保险、青海省城乡居民养老保险、贵州省机关事业单位养老保险精算模型，利用全省保险金缴纳明细、保险金发放明细等数据，对缴纳人数、领取人数、年龄构成比例、预期寿命、每年死亡人数等重要参数进行数学建模，以达到对未来五年保险收支情况进行预测的目的。
      -   主持研究贵州省工业与信息化专项资金、贵州省龙头企业与新增规模以上工业企业奖补专项资金、贵州文旅基金与生态基金投资成效。利用神经网络（KAN+LSTM）与图网络构建产业生态模型，寻找各产业薄弱环节并提出未来的投资方向与产业配套建议。
      -   为拉萨市墨竹工卡县农村“户厕分离”改造的数据信息、改造效果（改造前后图片）建立数据管理系统，以Spring+Django+Ajax+Redis框架为基础，在本地服务器上部署了数据系统与可视化大屏。
      -   参与云南省“一村一品”绩效评价项目，对全省1352个自然村的“一村一品”建设成果进行评价分析，依据行业的不同，使用AHP-Topsis-Reflection方法对目标的特征向量进行赋权评价，再依据评价的数值结果使用Dagum-Gini进行差异分析。最后，使用空间SLM模型分析全云南省的“一村一品”产业分布结构与空间集聚效应。
      -   将自然语言模型（NLP，模型：word2Vec，LSTM）部署在LLama开源模型上，方便进行一些日常的办公操作、数据匹配。
  - position: 数量投资助理（实习）
    company_name: 华夏基金管理有限公司（上海分公司）
    company_url: ''
    company_logo: ''
    date_start: 2021-03-01
    date_end: 2021-06-30
    summary: |
      Responsibilities include:
      -   协助证券分析师收集养老相关行业、国债期权相关数据并撰写行业报告，期间曾独立完成绿色国债期权市场的调研报告。
      -   协助基金经理更正、维护量化模型，期间参与协方差矩阵估计模型的更新（采用当时新的贝叶斯估计方法）。
      -   协助基金经理维护客户。

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: Python
        description: '使用Python的Tensorflow, Pytorch等框架搭建AI；使用Pyspark进行大数据运算；利用Python爬虫进行数据爬取；使用Python进行数据清洗、数据比对、数学建模等。'
        percent: 90
        icon: code-bracket
      - name: C++
        description: '使用C++搭建简单的底层代码。曾使用C++模拟可观测宇宙各天体运行轨迹数据（基于万有引力定律导出的常微分方程，不考虑极端天体）。'
        percent: 80
        icon: code-bracket
      - name: MATLAB
        description: '使用Matlab进行数学建模，主要集中于偏微分方程数值运算、大规模稀疏矩阵相关求解'
        percent: 85
        icon: code-bracket
      - name: Hadoop，Spark
        description: '部署Hadoop，Spark分布式数据框架。使用Hadoop大数据框架进行存储，辅以Spark框架进行流运算并使用Pyspark进行机器学习。'
        percent: 60
        icon: circle-stack
      - name: ORACLE，MySQL
        description: '数据库部署，数据的简单清洗与比对'
        percent: 60
        icon: circle-stack
      - name: R
        description: '使用R进行一些金融模型的参数估计，如CIR模型等'
        percent: 60
        icon: circle-stack

languages:
  - name: English
    percent: 75
  - name: 中文
    percent: 100
  - name: Deutsch
    percent: 25

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: '2020年高教社杯全国大学生数学建模竞赛本科组一等奖'
    url: /uploads/Model_competition.pdf
    certificate_url: http://www.mcm.edu.cn/upload_cn/node/593/ejsYC2sWca14e3b34ac748d4862444af0c44d1fd.pdf
    date: '2020-11-23'
    awarder: 中国工业与应用数学学会
    summary: |
       使用热传导方程，热辐射方程对加工工件内部温度变化进行建模，依据建模的数值结果绘出温度曲线，由于工件的特性，对工件在升温室、冷却室的最优时间长度进行求解，并由此来决定最优的传送带运行速度，实现数字化管控。
  - title: '上海财经大学数学学院优秀毕业论文'
    date: '2021-07-01'
    summary: |
      以彭实戈的倒向随机微分方程为基础，利用半参数、非参数方法对倒向随机微分方程进行非参数参数估计，并研究了它在蝶式期权上的数值实验效果。并研究了其在上证50指数期权价格预估上的应用。
  - title: '2019年美国大学生数学建模竞赛H奖'
    date: '2019-02-28'
    awarder: AMS
    summary: |
       使用Lasso，带正则项的Logistic模型，空间SLM模型对美国各州、郡的药物滥用数据进行建模，并分析影响药物滥用情况的特征，以及药物滥用情况在空间上的传播情况。数据量大致在70万上下。
  - title: '2018年高教社杯全国大学生数学建模竞赛上海赛区二等奖，2019年高教社杯全国大学生数学建模竞赛上海赛区三等奖'
    date: '2019-07-01'
    awarder: 中国工业与应用数学学会
---


