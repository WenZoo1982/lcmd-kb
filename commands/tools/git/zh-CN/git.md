+++
summary = "Git 版本控制工具的常用命令速查。"
+++
---

# Git 命令速查

Git 用来记录项目文件的变化、管理分支，并与远程仓库协作。本目录按具体命令拆分文档，可直接查询：

```bash
lcmd git status
lcmd git add
lcmd git commit
lcmd git push
```

## 日常开发

- `add`：把改动放入暂存区
- `commit`：保存一次提交
- `status`：查看当前改动
- `diff`：查看具体差异
- `log`：查看提交历史
- `show`：查看提交详情
- `grep`：搜索仓库文件内容

## 仓库与文件

- `init`：创建本地仓库
- `clone`：下载远程仓库
- `mv`：移动或重命名文件
- `rm`：从版本控制中删除文件
- `archive`：导出指定版本的文件
- `check-ignore`：检查忽略规则
- `ls-files`：列出 Git 跟踪文件

## 分支与提交

- `branch`：管理分支
- `switch`：切换分支
- `merge`：合并分支
- `rebase`：调整提交基点
- `cherry-pick`：移植指定提交
- `tag`：标记版本
- `worktree`：为多个分支创建独立工作目录

## 远程协作

- `remote`：管理远程仓库地址
- `fetch`：获取远程更新
- `pull`：获取并整合远程更新
- `push`：推送本地提交
- `ls-remote`：查看远程分支和标签

## 撤销与恢复

- `restore`：恢复文件或取消暂存
- `reset`：移动分支位置或重置暂存区
- `revert`：用新提交撤销旧提交
- `reflog`：查找引用历史
- `stash`：临时收起未提交改动
- `clean`：删除未跟踪文件（谨慎使用）

## 排查与维护

- `blame`：查看代码行的最后修改者
- `bisect`：二分定位问题提交
- `describe`：生成提交的版本描述
- `fsck`：检查仓库完整性
- `gc`：清理并优化仓库
- `count-objects`：查看对象占用
- `bugreport`：收集 Git 环境信息
- `diagnose`：生成仓库诊断包

## 补丁与其他协作

- `format-patch`：导出补丁
- `am`：应用邮件补丁
- `request-pull`：生成拉取请求摘要
- `bundle`：打包仓库历史
- `submodule`：管理子模块
- `notes`：为提交添加备注
- `shortlog`：按作者汇总提交
- `range-diff`：比较两组提交系列

## 配置与帮助

- `config`：设置 Git 配置
- `help`：查看 Git 帮助
- `difftool`：使用外部工具比较差异
- `mergetool`：使用外部工具解决冲突
- `checkout`：兼容旧教程的分支切换与文件恢复命令

## 内容范围

本知识库优先覆盖有实际使用价值的 Git 命令。参数和示例经过筛选，不追求罗列全部选项。需要完整参数说明时，请查阅 [Git 官方文档](https://git-scm.com/docs)。
