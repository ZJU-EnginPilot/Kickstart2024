# **如何贡献**

非常感谢你对这个项目的关注！:octicons-heart-fill-24:{ .heart }

有两种方式可以为这个项目做贡献：

## 我熟悉 Git 和 GitHub！![](images/tieba/happy.png)

### GitHub 上的操作指南

1. 到[项目网址](https://github.com/ZJU-EnginPilot/Kickstart2024){target=_blank}，点击右上角的 `Fork` 按钮，将项目 Fork 到你的 repo 中。
2. 在你的 repo 中进行修改，修改完成后提交并发起 Pull Request (PR)。
3. 等待管理员审核你的 PR。

### 本地编辑操作指南

你可以在 GitHub 线上编辑器中直接编辑，也可以将项目 clone 到本地进行编辑。

本站点使用 :simple-materialformkdocs: [MkDocs Material](https://squidfunk.github.io/mkdocs-material/){target=_blank} 构建。
官网上的文档非常详细，这里只介绍最简单的本地构建操作[^1]。

1. 克隆 GitHub 项目到本地：

    ```bash
    git clone https://github.com/ZJU-EnginPilot/Kickstart2024.git
    cd Kickstart2024
    ```

2. 安装 Python 依赖（MkDocs 以及 Material 主题）

    ```bash
    pip install -r requirements.txt
    ```

3. 启动本地服务器

    ```bash
    mkdocs serve
    ```

之后即可通过浏览器访问 `localhost:8000` 预览网站。

!!! info "关于站点内容的格式规范"
    - 尽量规范编写 Markdown，避免出现格式错误
    - 英文与中文，数字与中文之间请加入空格
    - 中文内容使用**中文**标点`，`、`。`、`；`、`：`（与理工科文档要求不同）
    - ...（待补充）

    如果你觉得这很麻烦，也没关系，尽管上传，我们发现后会及时进行修改。

## 这也太技术流了！![](images/tieba/bored.png)

这不要紧！欢迎你通过电子邮件联系我们！

- 邮箱：[georgecao@zju.edu.cn](mailto:georgecao@zju.edu.cn)
- 邮件主题请使用如下格式：`【Kickstart2024】+ {出现问题的页面名称，如“生活-校园网”} + {问题/建议简述}`（`{}`和`+`不用写入主题）
- 请留下你的名字或昵称，以方便我们在修改时标注贡献者。
- 无论你的建议被采纳与否，我们都会在邮件中回复你。

## 反映问题

如果你在使用过程中发现了问题，欢迎通过邮件或者 GitHub Issue 反馈给我们！

!!! success ""
    <center>再次感谢你的关注！😉</center>


[^1]: 参考了 [图灵班学习指南 | 贡献指南](https://zju-turing.github.io/TuringCourses/contributing/#_2){target=_blank}