## 文字生成
自用，用于生成深度学习的识别模型
## 安装
依赖安装:
```
pip3 install -r requirements.txt
```


## 简单实用
运行 `python3 main.py` 
label文件产生目录为 `output/default/`.

## 使用
1. `python3 main.py --help` 查看实用姿势

2. 配置文件在 `configs/default.yaml` 。


3. 运行 `python main.py` .

## check 模式
中文经常有一些无法支持的文字，会生成如下的图片:

![bad_example1](./imgs/bad_example1.jpg)


自己配置 `--chars_file` 比较麻烦.可以直接运行 `python main.py --strict` 

## 工具
可以使用`check_font.py` 脚本去检查字体支持哪些字符 `--chars_file`:
```bash
python3 tools/check_font.py
```

