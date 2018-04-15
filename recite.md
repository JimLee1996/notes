## 卷积核的计算

- output_size = (input_size - filter_size + 2 * padding) / stride + 1


## python生成matrix

```python
mat = [[0] * cols for i in range(rows)]
```


## 生成模型和判别模型

- 生成模型(generative model)，p(y,x)，模板匹配,，混合高斯模型、朴素贝叶斯法和隐形马尔科夫模型等
- 判别模型(discriminative model)，p(y|x)，分类回归，SVM、LR等
