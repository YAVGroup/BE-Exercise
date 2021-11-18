# 后端练习题

## 任务

你需要：

1. Fork 此仓库至你的账号。
2. 使用 Django，完成如下所述的功能。
3. 在本文件末尾学撰写一份说明文档，叙述接口等信息。
4. 发起 Pull Request。（请在 PR 时写上你的姓名、学号）

### 约定

为了节约大家的时间，请尽量使用默认配置的组件：

1. 使用 Python 3.6+ ,Django 3.2, DRF3.12
2. 使用默认的数据库 (SQLite)、默认的 HTTP 服务器和默认的端口。
3. 不需要使用 template，不需要编写 HTML 文件。所有接口的返回内容为 JSON。具体可以参考Django RestFramework

## 目标功能

### 必须完成的功能

- 登录账户
- 注册账户
- 退出 (log out) 账户
- 显示与修改账户的个人信息

### 可以选做的功能

- 查询当前的年月日信息
- 要求：
  - 只有登录的用户才可以查看
  - 进行用户是否注册的判定
  - 返回日期信息，具体格式自己定义 


### 加分项

这些加分项都是值得提倡的良好的开发习惯，因此我们将它们作为加分项。

- 良好的代码风格（如变量命名）会有额外加分
- 良好的注释和文档会有额外加分
- 良好的 Git 提交记录（每次提交有明确的信息）会有额外加分
- 良好的安全性、鲁棒性和可扩展性会有额外加分
- 良好的单元测试有额外加分

## 其它注意事项和提醒

- 对于以上提到的各项功能，最基础的要求是：用户输入正确的请求时，程序可以给出正确的回复。同时，对于用户发起的错误的请求，程序不会受到灾难性的破坏，不会影响其它用户的正常使用（例如，在注册账户时把已有的账户「覆盖」掉是不容许的）。

  你可以选择将这些功能做得更完善和更安全，具体内容和方式请自行决定，例如检查输入并返回有意义的错误信息等。

- 允许使用任意 PyPI 中的模块，即可以使用 `pip` 命令安装的模块。

- 我们最终的代码会在 Linux 下执行，所以如果你在使用其它操作系统开发，请谨慎使用依赖于特定操作系统的特性。（但这里应该不会出现这种情况）
  
- 推荐参考内容
    - [Django](https://www.djangoproject.com/)
    - [DjangoRestFramework](https://www.django-rest-framework.org/)

## 报告（需要完成）

请把具体的报告内容放在这里
