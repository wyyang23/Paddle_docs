## [ 仅 paddle 参数更多 ] torch.ByteTensor

### [torch.ByteTensor](https://pytorch.org/docs/stable/tensors.html)

```python
torch.ByteTensor(data)
```

### [paddle.to_tensor](https://www.paddlepaddle.org.cn/documentation/docs/zh/develop/api/paddle/to_tensor_cn.html#to-tensor)

```python
paddle.to_tensor(data, dtype='uint8', place='cpu')
```

Paddle 比 PyTorch 支持更多参数，具体如下：

### 参数映射

| PyTorch | PaddlePaddle | 备注                                                        |
| ------- | ------------ | ----------------------------------------------------------- |
| -       | dtype        | Tensor 的数据类型，Pytorch 无此参数，Paddle 需设置为 'uint8'。   |
| -       | place        | Tensor 的设备，Pytorch 无此参数，Paddle 需设置为 'cpu' 。         |
