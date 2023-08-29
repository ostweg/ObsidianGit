Can accelerate the training of neural networks by 100.

For example [[Tensor]] operations are much faster on a GPU than a CPU

## Specify device

`device = torch.device("cuda") if torch.cuda.is_available() else torch.device("cpu")

## Push Tensor (x) to device

`x = x.to(device)
