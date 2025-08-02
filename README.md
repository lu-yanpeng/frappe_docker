**不要把项目代码上传到这里，这里只保存创建容器需要的文件，应该在容器里clone一个项目进行开发**

## 容器开发

> 基于Docker容器开发和部署frappe的示例，更多内容请到官方项目[查看](https://github.com/frappe/frappe_docker)

容器开发就是把编辑器运行到docker容器里面，这样本地就不用安装环境了，所有的操作都通过编辑器控制容器来实现。

**必要条件**

1. pycharm专业版（vscode更好，不过没试过）
2. 性能良好的电脑，容器开发非常占内存，电脑最好16G以上内存
3. docker和docker compose
4. 本机已安装ssh，并且可以通过ssh clone github上的代码

详细内容请看[创建开发容器](/docs/开发/开发容器.md)
