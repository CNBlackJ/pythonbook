# 理解TensorFlow的基本用法

## 例1: 生成三维数据，用一个平面拟合
见：lesson_01_01.py

```
# output（因为是随机数，每次结果都不一样）
# step sess.run(W) sess.run(b)
0 [[ 0.57031691 -0.41185194]] [ 0.75471532]
20 [[ 0.09686384  0.06381502]] [ 0.37076062]
40 [[ 0.08508073  0.16787253]] [ 0.32402116]
60 [[ 0.09337451  0.19088542]] [ 0.30805147]
80 [[ 0.09759621  0.1971551 ]] [ 0.30268663]
100 [[ 0.09917615  0.19907565]] [ 0.30089507]
120 [[ 0.09972294  0.19969504]] [ 0.30029801]
140 [[ 0.09990744  0.19989881]] [ 0.30009922]
160 [[ 0.09996913  0.19996636]] [ 0.30003303]
180 [[ 0.09998973  0.19998881]] [ 0.30001098]
200 [[ 0.09999657  0.19999626]] [ 0.30000368]
```


## 例2: 矩阵相乘
- 可以到[网易公开课学习线性代数](http://open.163.com/special/opencourse/daishu.html)

见：lesson_01_02.py

```
# ouput(一个3x2的矩阵)
[[  4.   7.]
 [ 14.  25.]
 [ 22.  39.]]
```

## 例3：计算x - a
见：lesson_01_03.py

```
# output（矩阵相减）
[-2. -1.]
```


## 例4: 计数器
见：lesson_01_04.pt

```
# output
0
1
2
3
4
5
```
