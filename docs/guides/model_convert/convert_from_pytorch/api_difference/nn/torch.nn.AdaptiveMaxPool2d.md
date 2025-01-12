## torch.nn.AdaptiveMaxPool2d
### [torch.nn.AdaptiveMaxPool2d](https://pytorch.org/docs/1.13/generated/torch.nn.AdaptiveMaxPool2d.html?highlight=adaptivemaxpool2d#torch.nn.AdaptiveMaxPool2d)

```python
class torch.nn.AdaptiveMaxPool2d(output_size,
                                 return_indices=False)
```

### [paddle.nn.AdaptiveMaxPool2D](https://www.paddlepaddle.org.cn/documentation/docs/zh/api/paddle/nn/AdaptiveMaxPool2D_cn.html#adaptivemaxpool2d)

```python
 classpaddle.nn.AdaptiveMaxPool2D(output_size,
                                  return_mask=False,
                                  name=None)
```

两者功能一致且参数用法一致，仅参数名不同，具体如下：
### 参数差异
| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| return_indices| return_mask  | 如果设置为 True，则会与输出一起返回最大值的索引，默认为 False。 |
