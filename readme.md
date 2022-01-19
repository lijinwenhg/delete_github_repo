# github 账户中没用的仓库太多，用网站自带的删除仓库的办法，太麻烦。此仓库解决用户此问题，一键删除 github 仓库。

+ 生成github api的 token: https://github.com/settings/tokens/new  勾选 delete_repo 选项。
+ 接口api: https://docs.github.com/en/rest/reference/repos#delete-a-repository
+ 接口使用方法： https://github.com/octokit/core.js#readme

+ 待添加功能： 一次性删除多个仓库。