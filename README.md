# Cookiecutter Mkdoc ShaPackage

用于Python打包的[Cookiecutter](https://github.com/cookiecutter/cookiecutter)模板。 由 Poetry、GitHub 操作和 MkDocs 提供支持。 

## 特征 
该模板具有以下特点：
  - [`pytest`](https://github.com/pytest-dev/pytest):  单元和覆盖测试 
  - [`flake8`](https://github.com/PyCQA/flake8) 和 [`pylint`](https://github.com/PyCQA/pylint):  Python 风格检查 
  - [`black`](https://github.com/psf/black): 自动格式化代码 
  - [`mypy`](https://github.com/python/mypy): 类型检查 
  - [`Poetry`](https://github.com/python-poetry/poetry): 依赖管理和包装 
  - [`GitHub Actions`](https://github.com/features/actions): 自动 CI 检查、自动发布到 PyPi 和自动版本碰撞（不再需要 Travis） 
  - [`shadocs`](https://github.com/llango/shadocs): 自动发布文档到它自己的网页 

## 快速开始 
如果您还没有安装最新的 Cookiecutter，请安装它（这需要 `Cookiecutter 1.4.0` 或更高）：

`$ pip install -U cookiecutter>=1.4.0`

生成一个 Python 包项目：

`$ cookiecutter https://github.com/llango/cookiecutter-mkdoc-shapackage.git`
