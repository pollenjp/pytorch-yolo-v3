

`detect.py`にモデルを保存するコードを記述しCPUだけの環境下でrunする。

```
    #===========================================================================
    # save model param
    torch.save(model.state_dict(), "./weights.pth")
    #===========================================================================
```

`terminal`

```
 % CUDA_VISIBLE_DEVICES= python3 detect.py --images imgs/dog.jpg --det det
```
