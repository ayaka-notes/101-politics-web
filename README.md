# Website

网站基于 [Docusaurus 2](https://docusaurus.io/)改进开发。这是我首次尝试通过git submodule来挂载一个仓库到另外一个仓库。

本仓库为考研政治的笔记。docs挂载了另外一个仓库的笔记markdown文件。开放时间待定。


要更新子模块，首先导入个人的Github令牌，然后执行下面操作

```bash
git submodule update --init --recursive
git submodule update --recursive --remote
git submodule update --recursive
```