# gitgs.hello
Git Hello World

参考 [hello world](https://guides.github.com/activities/hello-world/)

练习内容
- 创建和使用存储库
- 启动和管理新分支
- 对文件进行更改，并将它们推送到 GitHub 作为提交
- 打开并合并拉取请求

### Step 1. Create a Repository

创建新存储库 `gitgs.hello` (登录 github 通过 web 界面创建)

```bash
# 建立本地库
git clone git@github.com:wangwg2/gitgs.hello.git wangwg2.hello
```

### Step 2. Create a Branch

创建新分支 `readme-edits`

```bash
# 创建 readme-edits 分支
git checkout -b readme-edits
```

### Step 3. Make and commit changes

修改 README.md 并提交修改
```bash
git add .
git commit -m 'finished README'
git push origin readme-edits
```

### Step 4. Open a Pull Request

拉取请求是 GitHub 上协作的核心。当您打开拉取请求时，您会提出您的更改，并要求某人审核并提取您的贡献，并将其合并到其分支中。拉取请求显示两个分支中内容的差异或差异。更改、添加和减法以绿色和红色显示。

一旦进行提交，就可以打开拉取请求并开始讨论，甚至在代码完成之前。

通过在拉取请求消息中使用 GitHub `@mention` 系统，您可以请求特定人员或团队的反馈，无论他们是在大厅之外还是 10 个时区之外。

您甚至可以在自己的存储库中打开拉取请求，并自行合并它们。在处理大型项目之前，它是学习 GitHub 流的好方法。

### Step 5. Merge your Pull Request

在最后一步中，是时候将更改整合在一起了 — 将 `readme-edits` 分支合并到 `master` 分支中。

单击合并拉取请求按钮，将更改合并到 `master` 中。

继续删除分支，因为它的更改已合并，使用"删除分支"按钮。