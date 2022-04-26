---
title: pygbz
description: pygbz文档
published: 1
date: 2022-04-25T10:22:06.682Z
tags: 
editor: markdown
dateCreated: 2022-04-25T02:14:17.460Z
---

# 简介

pygbz项目主要是使用python计算非厄米non-Bloch能带以及广义布里渊区(GBZ).  
主要提供如下几种接口：

1.  非厄米哈密顿量本征态和本征复能谱计算接口
2.  给定精度下开边界非厄米能谱计算以及GBZ 

      -  利用python mpmath 包来计算，计算效率会很低 
      -  可以考虑增加mathkernel选项
     

3. 利用辅助广义布里渊区(AGBZ)方法计算GBZ
	
  	- 解析反解算法
  	- 数值标记曲线解析方法

4. 可以考虑增加构造非厄米体系的易用接口，如图形化界面等 (待定，非核心)

5. 可以考虑增加 non-Bloch 单向输运衰减系数根求解 (待定，可以考虑版本2)