{% set is_open_source = cookiecutter.open_source_license != 'Not open source' -%}
{% set project_github_link = cookiecutter.project_slug | replace("_", "-") -%}
# {{ cookiecutter.project_name }}

{% if is_open_source %}
[![PyPI version](https://badge.fury.io/py/{{ project_github_link }}.svg)](https://badge.fury.io/py/{{ project_github_link }})
![versions](https://img.shields.io/pypi/pyversions/{{ project_github_link }}.svg)
[![GitHub license](https://img.shields.io/github/license/mgancita/{{ project_github_link }}.svg)](https://github.com/mgancita/{{ project_github_link }}/blob/main/LICENSE)
{% endif %}
{% if cookiecutter.use_black %}
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
{% endif %}

{{ cookiecutter.project_short_description }}

{% if is_open_source %}
- 开源许可: {{ cookiecutter.open_source_license }}
- 文档: https://{{ cookiecutter.github_username }}.github.io/{{ project_github_link }}.
{% endif %}

## 特征

* TODO

## 制作


该包使用 [Cookiecutter](https://github.com/audreyr/cookiecutter) 和 [`llango/cookiecutter-mkdoc-shapackage`](https://github.com/llango/cookiecutter-mkdoc-shapackage/) 项目模版创建。
