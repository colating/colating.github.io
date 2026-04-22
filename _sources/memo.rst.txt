Pydata 笔记
===========

## User Guide

https://pydata-sphinx-theme.readthedocs.io/en/stable/user_guide/index.html

#### View Source link

https://pydata-sphinx-theme.readthedocs.io/en/stable/user_guide/source-buttons.html

By default, this theme adds a button link to view the source of a page (i.e., the underlying reStructuredText or MyST Markdown for the page). To disable it, use the following configuration:

html_show_sourcelink = False

html_theme_options = {
    "use_edit_page_button": True,
}

#### Theme variables and CSS

https://pydata-sphinx-theme.readthedocs.io/en/stable/user_guide/styling.html
html_static_path = ['_static']

html_css_files = [
    'css/custom.css',
]

#### AI@ sphinx pydata them 禁止自动显示‘文档’两个字

Sphinx PyData Them 禁止自动显示‘文档’两个字
要禁止自动显示“文档”两个字，用户需要在 conf.py 文件中使用 html_theme_options 变量进行配置。这个变量是一个包含 key: val 对的字典，用户可以通过各种方式配置它们。具体步骤如下：

    打开 conf.py 文件。
    在文件中添加或修改 html_theme_options 变量。
    将 theme:'PyData Sphinx' 替换为 theme:'PyData Sphinx, disable_docstring'。
    保存文件并重新构建 Sphinx 文档。
    通过以上步骤，用户可以有效地禁用“文档”两个字的自动显示，从而实现文档主题的个性化定制。
    1
