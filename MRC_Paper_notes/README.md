<<<<<<< HEAD
### MRC 文章  

### 说明: 根据目前见到的数据集的形式，以及公布的文章进行按照自己的理解对于阅读理解中的文章进行整理和归一化   
### 图标总览:
* MRC分类:
  * 按照陈丹绮按照数据集答案的形式: 1) 完形填空;  2) 选择题;  3) span;  4)free-text;
  * 按照自己的理解划分: 
    * 传统MRC[简单的对于context的理解]: 
    * Multi-hop MRC[得到答案所需句子角度]:
      * HotpotQA:
      * WikihopQA:
      * MultiRC
      * ...
    * Conversation MRC:
      * CoQA:
      * QuAC:
    * 情景-领域 MRC:
    * Reasoning MRC:
      * 常识推理:
        * CommonSenseQA:
        * ReCoRD:
      * 离散推理：
        * DROP:
        * MathQA:
      * 专业推理:
        * CosMos:
        * QuoRef:
        * ..
    * 会话理解:
      * DREAM:
      * 谷歌acl2019医疗问诊:
      * 医患回访对话:
    * Other task --> MRC:
      * NER->mrc
      * RE->MRC 
    * 多任务数据集:
    * 跨领域:
    * 跨模态:
    * few-shot/meta-learning/...

#### 一些简单说明:
* 整理仅仅按照自己片面的，几个月学习的理解;
* 本readme.md仅仅是MRC一个总的整理,具体到每一个小的方向可以按照链接/其对应的文件夹下面的readme.md再进行对应; 
* 原则上按照数据集的角度划分MRC的分类,其实很不精确,但是从发文章，读文章，整理文章的角度这样可能更容易理解一些; 
* 目前仅仅局限于英文数据集中文的数据集没有怎么关注; 
* 数据集的标注按照: [arxiv-时间][数据集来源domain-标注形式][答案类型-chendanqi][人类-sota比较][近期文章频率]  
* other
=======
### Multi-hop MRC   

#### 种一棵树最好的时间是10年前，其次是现在; 
1. 简单介绍:   
    1.1 Multi-hop 定义: 相较于一般的阅读理解任务,模拟生活中真实场景用户问的问题可能不仅仅是简单的问题，而是需要进行多跳推理才可以得到答案,比如: 2015年NBA季后赛的MVP在2018年在哪个球队打球?  1. 2015MVP-->A;  2.A--> 2018年所在球队;   
2. 数据集:   
    2.1 HotpotQA:  
        * 数据集介绍  
            * 数据集  
            * 难点  
            * 等  
        * Leadbord  
        * 自己分析   
    2.2 WikihopQA[Qangaroo]:  
3. 主流方法[文章角度]:   
    3.1 GCN建模 实体-句子-文章  
    3.2 问题分解 single-hop  
    3.3 启发式搜索最终答案  
    3.4 分析与对抗  
    3.5   
4. 文章列表:   
    * HotpotQA   

        * DFGN [ACL2019] [GCN] [distractor setting ]  
            * 文章笔记:   
                * 知乎  
                * 自己   
            * 代码  
                * 官方代码 [未开源]  
                * 复现版本[] []   
        * [ACL2019] [full-wiki setting]  
    * WikihopQA  
        * HDEGraph [ACL2019] [GCN] []  
>>>>>>> 839cb37945aa7cc9e48eae4ec8b11f4bdd0e6738
