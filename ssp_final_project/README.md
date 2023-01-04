## 运行方式 (Linux下指定GPU)
```
CUDA_VISIBLE_DEVICES=0 python interact.py
```
## 模型checkpoint下载链接
https://box.nju.edu.cn/d/7b17194919e4461bad6f/
## 相关库
看`requirements.txt`，torch版本没那么严格（我的torch版本是`1.7.0`），主要是transformers版本得用里面那个不然会报错。
