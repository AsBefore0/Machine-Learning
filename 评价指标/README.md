#### Recall召回率

是指对于特定类别 $i$

TP 是正确预测为类别 $i$ 的样本数

FN是实际为类别 $i$ 但被错误预测为其他类别的样本数

$$
Recall = \frac{TP}{TP + FN}
$$

#### Precision精确率

是指对于特定类别 $i$

FP是实际为其他类别，但被错误预测为类别 $i$ 的样本数

$$
Precision = \frac{TP}{TP + FP}
$$

#### F1-Score

F1分数是精确率和召回率的调和平均，综合了这两者的表现。

适用于处理类别不平衡的情况。

$$
F1Score = 2 \times \frac{Precision \times Recall}{Precision + Recall}
$$
