# md_padding_pyscript

一个 Python 脚本，目的是解决我在使用 [md-padding](https://github.com/harttle/md-padding) 对 markdown 中英文混排时的一些问题。

`md-padding` 已经解决了我在写博客中遇到的绝大部分的排版问题，十分推荐。

1. 对 `YAML` 块中的 date 格式进行修复
2. 对行内数学公式前后添加空格
3. 修改行内数学公式中含有的 `*` 符号用 $\times$ 代替（因为会和 `md-padding` 冲突）

4. 本 `README.md` 使用该脚本生成

## 食用方法

1. 先安装[md-padding](https://github.com/harttle/md-padding)
2. 使用`python3 lint.py -a dir_path` 更新该目录下所有的文件
3. 使用`python3 lint.py -s dir_path` 更新该目录下最新的文件
4. 使用`python3 lint.py file_path` 更新该文件

