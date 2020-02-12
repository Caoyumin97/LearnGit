# Learn Git & Github

## 基本概念

1. Repositories
2. Star
3. Fork
4. Pull request：对fork的项目提出修改请求
5. Watch
6. Issue



## 仓库操作

* create repo
* edit repo (an update of the project)
* pull request：创建项目代码branch，合并前的新版本



## Git使用

### Git工作区域

* Github：远程repo
* Git repo：最终确定版本保存
* 暂存区：暂存修改文件，最后统一提交至repo
* 工作区（working dir）：原始编辑

```python
'''Git命令'''
git status # 查看文件位置及状态
git add # 添加文件至暂存区
git commit -m "description" # 提交文件至repo
rm -rf # 删除工作区文件
git rm # 删除repo中文件
git push # 本地repo同步到远程repo
git clone repo_address # 复制远程repo到本地
```

