# GitHub零基础实战任务书01

## 一、项目简介

欢迎来到 GitHub 的世界！本任务书专为零基础同学设计，旨在通过“做中学”的方式，带你轻松迈出开源协作的第一步。

在本次“Hello World 挑战”中，你将不再是旁观者，而是真正的参与者。我们将以博主提供的教学项目为起点，从最基础的搜索、收藏开始，一步步完成代码的下载、本地运行、修改，。通过这一系列实战操作，你将亲手解锁 GitHub 的核心技能，为未来的编程与协作学习打下坚实基础。准备好了吗？让我们开始这段奇妙的代码之旅吧！

## 二、学习目标

| 任务 | 内容 |
| --- | --- |
| 任务一 | 搜索博主的教学项目 |
| 任务二 | Star收藏项目 |
| 任务三 | Fork复刻项目 |
| 任务四 | Download下载代码到本地 |
| 任务五 | 用VSCode打开并运行代码 |

完成本次实战任务后，你将能够：

1. **精准搜索**：熟练使用 GitHub 搜索功能，快速找到目标教学项目。
1. **互动与复刻**：掌握 Star（收藏）与 Fork（复刻）操作，理解其在开源社区的意义。
1. **本地运行**：将代码下载到本地，并使用 VSCode 成功运行，验证环境配置。

## 三、课前准备

在开始任务前，请确保你已经准备好以下“装备”：

- **GitHub 账号**：如果还没有，请前往 github.com 免费注册一个。
- **VSCode 编辑器**：前往 code.visualstudio.com  或者 应用商店  下载并安装 Visual Studio Code。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image1.png)
- **Python 环境**：前往 python.org 下载并安装 Python，不知道自己的电脑应该下载哪个型号就去问AI。安装时务必勾选 “Add Python to PATH”
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image2.png)
- **Git 工具**：通常 VSCode 会自带 Git，若未安装，请前往 git-scm.com 下载安装。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image3.png)

不知道自己的电脑应该下载哪个型号就去问AI

![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image4.png)

## 四、任务详情

| 任务 | 内容 |
| --- | --- |
| 任务一 | 搜索博主的教学项目 |
| 任务二 | Star收藏项目 |
| 任务三 | Fork复刻项目 |
| 任务四 | Download下载代码到本地 |
| 任务五 | 用VSCode打开并运行代码 |

### 任务一：搜索项目

- **操作步骤**：
1. 登录 GitHub，点击页面顶部的搜索框。输入提供的项目名称或关键词，例如RiRi-Zinnia/A-beginner-s-guide-to-GitHub
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image5.png)
1. 在搜索结果列表中，点击正确的仓库链接进入
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image6.png)

### 任务二：Star收藏项目

- **任务目标**：收藏该项目，方便日后查找，并向作者表达支持。
- **完成标准**：Star 按钮变为高亮状态，且右上角数字 +1。
- **操作步骤**：
  1. 在项目仓库主页的右上角，找到 “Star” 按钮。
  1. 点击该按钮，按钮文字会变为 “Unstar”，表示收藏成功。
- **小贴士/注意事项**：Star 类似于其他平台的“点赞”或“收藏”，是你参与开源社区的第一步互动。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image7.png)

### 任务三：Fork复刻项目

- **任务目标**：将博主的仓库完整复制一份到你自己的 GitHub 账号下。
- **完成标准**：你的账号下出现了一个同名仓库，且页面显示 “forked from 博主用户名/项目名”。
- **操作步骤**：
  1. 在项目仓库主页右上角，点击 “Fork” 按钮。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image8.png)
  1. 在弹出的对话框中，选择你的个人账号作为 Fork 的目标。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image9.png)
  1. 等待几秒钟，页面会自动跳转到你账号下的新仓库。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image10.png)
- **小贴士/注意事项**：Fork 和 Download 有本质区别，请参考下表：

| 对比项 | Fork | Download ZIP |
| --- | --- | --- |
| 代码存哪 | 保存在你的 GitHub 账号下 | 保存在你的电脑本地 |
| 能在线编辑 | 能 | 不能 |
| 能推送修改回GitHub | 能（推送到你自己的Fork仓库） | 不能 |
| 能同步原作者更新 | 能（通过 Fetch upstream） | 不能 |
| 适合场景 | 长期参与、协作、贡献代码 | 仅查看代码、一次性使用 |

### 任务四：Download下载代码到本地

- **任务目标**：将 Fork 后的代码下载到你的电脑上。
- **完成标准**：本地文件夹中包含项目的源代码文件。
- **操作步骤**：
  1. 在你 Fork 的仓库主页，点击绿色的 “Code” 按钮。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image11.png)
  1. 在下拉菜单中选择 “Download ZIP”。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image12.png)
  1. 下载完成后，将 ZIP 文件解压到你习惯存放代码的文件夹中。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image13.png)
- **小贴士/注意事项**：解压后的文件夹可能包含一层同名目录，建议将内部文件直接移出，保持目录结构整洁。

### 任务五：用VSCode打开项目并运行代码

- **操作步骤**：
  1. 打开 VSCode，点击菜单栏 File → Open Folder，选择刚才解压的项目文件夹。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image14.png)
  1. 在左侧资源管理器中找到源代码文件（如 hello.py）。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image15.png)
  1. 右键点击文件，选择 “Run Python File in Terminal”（或在终端中输入 python hello.py）。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image16.png)
  1. 观察底部终端的输出结果。
   ![截图](https://fastly.jsdelivr.net/gh/RiRi-Zinnia/A-beginner-s-guide-to-GitHub@main/images/image17.png)
- **小贴士/注意事项**：如果提示找不到 Python，请检查是否在安装时勾选了 “Add Python to PATH”，或重启 VSCode。
### 任务六：使用 VSCode 源代码管理面板修改代码并 push 到个人 GitHub（核心）

- **任务目标**：在本地修改代码，并通过 VSCode 把修改推送回你自己 Fork 的仓库。
- **完成标准**：刷新你 Fork 仓库的 GitHub 网页，能看到刚才这次 commit 与改动后的文件内容。

#### VSCode 源代码管理面板操作步骤（无需安装任何插件）

**步骤 1：打开源代码管理面板**

在 VSCode 左侧边栏，点击"源代码管理"图标（图标形状为分叉的树丫，位于"资源管理器"图标下方）。也可以使用快捷键 Ctrl+Shift+G 直接打开。

**步骤 2：修改代码并保存**

在编辑器中打开任意文件进行修改（例如在 hello.py 末尾添加一行 `print("Hello GitHub!")`），修改后按 Ctrl+S 保存。保存后，源代码管理面板的"更改"列表中会自动显示该文件，文件名右侧会出现一个字母"U"（表示未暂存）。

**步骤 3：暂存更改（Stage Changes）**

把鼠标移到文件名上，文件名右侧会出现一个"+"号，点击该"+"号，文件会从"更改"列表移动到上方的"暂存的更改"列表，字母"U"变为字母"A"（表示已暂存）。如果要暂存所有更改，可点击"更改"列表右侧的"+"号（全部暂存）。

**步骤 4：填写提交说明并提交（Commit）**

在面板顶部的文本框中输入提交说明（例如"update hello"），然后按 Ctrl+Enter 提交，或点击文本框右侧的"提交"按钮（勾选图标）。提交后，"暂存的更改"列表会清空，面板底部状态栏会显示当前分支名称和"↓0 ↑1"（表示有 1 个提交待推送）。

**步骤 5：推送到 GitHub（Push）**

点击面板顶部的"同步更改"按钮（圆形箭头图标），或点击底部状态栏的"↑1"字样。首次推送时，VSCode 会弹出提示"是否登录 GitHub?"，点击"登录"按钮，浏览器会自动打开 GitHub 授权页面。在浏览器中点击"Authorize"授权，返回 VSCode 即可完成推送。

**步骤 6：验证推送结果**

推送成功后，打开浏览器访问你 Fork 的 GitHub 仓库页面，刷新页面即可看到刚才的提交记录和修改后的文件内容。

#### 备选方案：终端命令行（与图形界面等效）

```powershell
git add .                     # 暂存所有改动
git commit -m "update hello"  # 提交一次快照
git push -u origin main       # 首次 push，-u 绑定上游分支
# 之后每次只需 git add . / commit / git push
```

- **小贴士**：Fork 场景下，若你 clone 的是原仓库地址，origin 指向的是别人的仓库，push 会报 403/404。需先把 origin 改成你自己的 Fork 地址：`git remote set-url origin https://github.com/<你的用户名>/<仓库名>.git`

### 任务七：创建自己的仓库并上传代码

- **任务目标**：从零新建一个 GitHub 仓库，并把本地已有代码上传上去。
- **完成标准**：GitHub 网页上你新建的空仓库里，出现了本地上传的全部文件与一次提交记录。

**操作步骤：**

1. GitHub 右上角 "+" → New repository，填写仓库名，保持仓库为空（不要勾选初始化 README），点 Create repository。

2. 在本地代码文件夹打开终端，依次执行：

```powershell
git init                       # 在本地初始化 Git 仓库
git add .                      # 暂存所有文件
git commit -m "first commit"   # 首次提交
git remote add origin https://github.com/<你的用户名>/<仓库名>.git
git push -u origin main        # 推送（若本地是 master，把 main 换成 master）
```

- **小贴士**：若 push 报 "src refspec main does not match"，多半是本地默认分支叫 master，用 `git branch -M main` 改名后再 push。

---

## 五、恭喜你已经成功实现github的基础用法啦，后续教学你将学到：修改代码并提交到个人GitHub、创建自己的仓库并上传代码、创建代码的分支并Commit和Push，关注主播不迷路，只为做真正零基础小白的教学！


## 六、附录

### 附录A：核心概念速查表

| 概念 | 一句话解释 | 怎么用 |
| --- | --- | --- |
| Repository | 代码仓库，存放项目所有文件和历史记录 | 创建或 Fork 一个仓库来开始项目 |
| Star | 收藏/点赞，表示对项目的认可 | 点击仓库页面的 Star 按钮 |
| Fork | 复刻，将他人仓库完整复制到自己账号下 | 点击 Fork 按钮，获得独立副本 |
| Clone | 克隆，将远程仓库下载到本地（含完整历史） | 使用 git clone <url> 命令 |
| Commit | 提交，保存一次修改的快照 | 修改代码后执行 git commit |
| Push | 推送，将本地提交上传到远程仓库 | 执行 git push 同步到 GitHub |
| Pull | 拉取，从远程仓库获取最新代码到本地 | 执行 git pull 保持同步 |
| Branch | 分支，用于并行开发而不影响主线 | 使用 git branch 创建新分支 |
| README.md | 项目说明文档，介绍项目用途和使用方法 | 在仓库根目录创建并编写 |

### 附录B：Fork vs Download ZIP 对比表

| 对比项 | Fork | Download ZIP |
| --- | --- | --- |
| 代码存哪 | 保存在你的 GitHub 账号下 | 保存在你的电脑本地 |
| 能在线编辑 | 能 | 不能 |
| 能推送修改回GitHub | 能（推送到你自己的Fork仓库） | 不能 |
| 能同步原作者更新 | 能（通过 Fetch upstream） | 不能 |
| 适合场景 | 长期参与、协作、贡献代码 | 仅查看代码、一次性使用 |
