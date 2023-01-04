## 运行方式
```
python interact.py
```
## 模型checkpoint下载链接
https://box.nju.edu.cn/d/7b17194919e4461bad6f/
下载好放到目录下，最终结构为
```
ssp_final_project/
  ul_model_best/
    model_epoch8/
      config.json
      pytorch_model.bin
```
## 相关库
看`requirements.txt`，torch版本没那么严格（我的torch版本是`1.7.0`），主要是transformers版本得用里面那个不然会报错。
