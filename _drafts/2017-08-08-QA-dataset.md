---
layout: post
title: QA dataset
published: true
date: 2017-08-08 15:32:24.000000000 +09:00
---

==========================分割线==========================
## CNN/Daily Mail
### 特点
1. 缺乏推理



## Who-did-What
## WikiMovie

## MS MACRO
### 数据集描述
1. Bing search
### 特点
1. 基于span
## SearchQA
## Quasa

## SQuAD
### 数据集描述
1. wikipedia
### 特点
1. 基于span的
## WebQA

## TriviaQA
[TriviaQA: A Large Scale Distantly Supervised Challenge Dataset for Reading Comprehension][8]
### 数据集描述
1. 95k Q-A pairs
2. 答案：span
2. 来源：wikipedia and the web(Bing Search)
### 其他
1. 评价方法
###
[dataset&code][9]

## NEWSQA
[NEWSQA: A MACHINE COMPREHENSION DATASET][6]
### 数据集描述
1. 来源：CNN news.
2. 方式：众包
3. 答案：span, 可能不存在在evidence里
4. 119,633 Q-A pairs, 12,744 stories
### 特点
1. 基于span
### 其他
1. 评价方法：EM 和 F1, BLEU 和 CIDEr
###
[dataset][5]
[stat][7]

## RACE
[EMNLP 2017]  [RACE: Large-scale ReAding Comprehension Dataset From Examinations][3]

### 数据集描述
1. 数据集来源中国初中高中英语考试
2. 27,933 passages and near 97,687 questions generated by human experts (English instructors)
3. 就是做了很多年的阅读理解(一个问题，4个候选答案，其中中一个是对的)
3. 包含各种主题
4. 涉及到reasoning, attitude analysis, passage summarization

### 其他数据集问题
1. 候选项以single entity或者text span的形式存在，完全来自context。
2. 问题和答案是自动生成的，存在较大噪音和偏差
3. 主题通常是某一个方面的，覆盖较少

### 特点
1. 量大
2. 质量高
3. 数据源的构造相比wikipedia和news来说更简单
4. 涉及推理对机器理解能力要求高

### 其他
1. 很不错的数据集,希望有很多人去试试，start-of-the-art 43%, human performance 95%.
2. 评价方法：accuracy

### 
[dataset][1]
[code][2]

## 数据分析
基本上都用的[Chen][4]的数据分析方法


<!-- 引用 -->
# 比如[^f1]
# [^f1]: hhh

<!-- 链接 -->
[1]: http://www.cs.cmu.edu/~glai1/data/race/
[2]: https://github.com/qizhex/RACE_AR_baselines
[3]: https://arxiv.org/abs/1704.04683
[4]: https://arxiv.org/abs/1606.02858
[5]: https://datasets.maluuba.com/NewsQA
[6]: https://arxiv.org/abs/1611.09830
[7]: https://datasets.maluuba.com/NewsQA/stats
[8]: https://arxiv.org/abs/1705.03551
[9]: http://nlp.cs.washington.edu/triviaqa/
