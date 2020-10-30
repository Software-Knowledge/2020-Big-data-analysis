Exam2-往年考试题目
---

# 1. 年:2019

## 1.1. 选择题
1. HDFS 2.x 的默认块大小：128MB
2. 社交网络的商业模式是长尾模式(疑问，还是二八模式)
3. 不是hadoop的默认集群运行模式:微服务式
   1. standalone(独立式)
   2. 伪分布
   3. 分布式
   4. 微服务式
4. 以下哪种不是Spark的库：Storm
   1. SparkSQL
   2. GraphX
   3. MLlib
   4. Storm
5. tasktracker运行在hdfs的哪个程序上:datanode
   1. namenode
   2. datanode
   3. secondarynodee
   4. jobtracker

## 1.2. 判断题
1. namenode是HDFS集群的主节点，负责维护整个HDFS系统的文件目录树，和各个路径/文件的块信息。对
2. jaccard距离用于度量集合距离，定义是两集合的交集中的元素个数除以并集中的元素个数。对
3. 决策边界指N维空间中用于区分不同类别样本的平面或者曲面。对
4. HBase是基于行的NoSQL。错(列)

## 1.3. 计算题
1. pagerank：初始每张网页的权重相等，写出转移矩阵和一次迭代后的page rank值

```
A: B, C, D  
B: D, E  
C: E  
D: E  
E: A  
```

2. 奇异值分解，奇异值分解如下举着

$$
\begin{bmatrix}
  1 & 2 \\
  2 & 2 \\
  2 & 1 \\
\end{bmatrix}
$$

## 1.4. 简答题
1. 聚类中，计算类簇间的距离时，有哪些可能的计算方向和方法(提示，距离，link，类簇的表示)
2. 举例并描述在社区计算中常见的计算任务(20分)  (列举即可，至少四类)  
3. 简述推荐系统的三大问题，并说说推荐系统评分中的Explict和Implict各有什么样的例子？