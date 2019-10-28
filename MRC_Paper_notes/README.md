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