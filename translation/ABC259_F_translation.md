## 题意

给定一棵含有 $n$ 个点的树，边有边权。  

现要你选出一个边集，满足每个点相连的被选择的边不超过 $d_i$ 条，问选的边集的边权和最大值。

## 数据范围

- $2 \leq n \leq 3 \times 10^5$

- $1 \leq u_i,v_i \leq n$

- $-10^9 \leq w_i leq 10^9$

- $d_i$ 是一个不超过点 $i$ 的度数的非负整数。

- 所有数都是整数。

## 输入格式

第一行一个整数 $n$ 表示节点数。

第二行 $n$ 个整数 $d_1 \dots d_n$ 含义如题意中所示。

接下来 $n-1$ 行每行 $3$ 个整数 $u_i,v_i,w_i$ 表示第 $i$ 条边连接 $u_i$ 和 $v_i$，边权为 $w_i$ 。 

## 输出格式

一行一个整数表示答案。

## 样例

### 样例输入1

```
7
1 2 1 0 2 1 1
1 2 8
2 3 9
2 4 10
2 5 -3
5 6 8
5 7 3
```

### 样例输出1

```
28
```

### 样例解释1

选择编号为 $1,2,5,6$ 的边。

### 样例输入2

```
20
0 2 0 1 2 1 0 0 3 0 1 1 1 1 0 0 3 0 1 2
4 9 583
4 6 -431
5 9 325
17 6 131
17 2 -520
2 16 696
5 7 662
17 15 845
7 8 307
13 7 849
9 19 242
20 6 909
7 11 -775
17 18 557
14 20 95
18 10 646
4 3 -168
1 3 -917
11 12 30

```

### 样例输出2

```
2184
```
