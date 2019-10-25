### Multi-hop MRC 
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