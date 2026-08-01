# 📖 Git 学习与实战笔记

这里记录了在实际使用 Git 过程中遇到的高频命令和特殊配置技巧。

---

## 1. 远程仓库管理

### 修改远程仓库地址 (切换至 SSH)
在使用 Git 的过程中，为了实现免密提交代码，通常需要将远程仓库的连接方式从传统的 HTTPS 更改为 SSH。

**执行命令：**
```bash
git remote set-url origin git@github.com:ZAWYB/PDF.git

**命令解析：**
* `remote`: 针对远程仓库的操作。
* `set-url`: 更改已存在的远程仓库地址。
* `origin`: 默认的远程仓库别名（通常你的云端仓库都叫这个名字）。
* `git@github.com...`: 你的全新 SSH 格式仓库地址。