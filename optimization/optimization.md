# 最优化理论与方法

## 1.Introduction

* 约束最优化$x\in X\subseteq R^n$

* example

### 1.1线性规划

目标函数和约束条件均是线性的

### 1.2非线性规划

目标函数或者约束条件不是线性的

* 结构
  * 动态优化：涉及时间
  * 随机优化
  * 多目标最优化。多个目标函数，往往这些目标函数相互冲突
  * 博弈论。多方参加，不能够确定对方决策

### 1.3要求

* understand optimization concepts and methods
* implement method in software

## 2.最优条件

### 凸集

集合X是凸集当且仅当X中的任意两个点x1,x2的线性组合还在该集合中

直观上：任意两点的连线还在该集合中