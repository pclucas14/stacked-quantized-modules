# modular-vqvae
Stacking Quantization blocks for efficient lifelong online compression

## arguments usage
 - specific block parameters are separated by `---layer_i` flag
 - specific block parameters are specified AFTER regular args
 e.g. 
 
```
python main.py --batch_size 32 --dataset miniimagenet --num_blocks 2 ---layer_1 --enc_height 64 ---layer_2 --enc_height 32
```
