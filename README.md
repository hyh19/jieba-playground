# jieba-playground

<https://github.com/fxsjy/jieba>

```bash
# 安装 Python 3.7.x 版本
# [paddlepaddle-tiny 不見，有其他替代方案嗎？](https://github.com/fxsjy/jieba/issues/865)
pyenv install 3.7.10 -v

# 设置项目目录使用的 Python 版本
pyenv local 3.7.10

# 验证设置结果
python --version

# 安装依赖库管理工具
pip install pipenv

# 创建指定 Python 版本的虚拟环境
pipenv --python 3.7.10

# 安装依赖库
pipenv install jieba

# 启动虚拟环境
pipenv shell

# 运行示例代码
pipenv example.py

# 退出虚拟环境
exit
```
