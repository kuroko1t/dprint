# dprint

debug print for numpy array, torch tensor.

# INSTALL

```
git clone github.com/kuroko1t/dprint
cd dprint
python setup.py install
```

# USAGE

```python3
import torch                                                                                                                                                            from dprint import dprint                                                                                                                                                                                                                                                                                                                       dprint('torch_tensor', torch.tensor([[1., -1.], [1., -1.]]))        
```

result
```
examples/example.py:4 torch_tensor (torch.Size([2, 2]), torch.float32) 
```

# LICENSE

MIT