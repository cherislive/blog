### 操作远程文件

```
git push origin :[branch]  删除远程分支
git rm -r --cached [file]  删除远程文件
```

### git commit 提交规范

```
feat: 新功能
fix: 修复 bug
test: 增加/修改测试用例
chore: 修改工具相关
docs: 修改文档
perf: 提升性能
reflactor: 重构，不影响当前逻辑
style: 修改样式
deps: 升级依赖
```

### PR 相关

```
git remote -v               列出远程仓库 url
git remote add [name] [url] 添加远程仓库 url
git fetch [name]            拉取远程仓库最新代码
git merge [name]/master     合并远程分支最新代码到本地
```