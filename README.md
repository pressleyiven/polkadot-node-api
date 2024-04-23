---

# Polkadot API 服务器使用指南

Polkadot API 服务器是对 [polkadot-js/api](https://polkadot.js.org/api/) 的封装，旨在简化使用任何编程语言查询 Polkadot 节点数据的过程。此外，API 服务器还实现了一些自定义调用，例如可以直接查询某个验证节点在任何区块高度被削减的代币数量。

此API服务器专为 [PANIC](https://github.com/SimplyVC/panic_polkadot) 监控 Polkadot 节点而构建。因此，并非所有来自 polkadot-js/api 的功能都包含在 API 服务器中。如果您希望在 API 服务器中实现 [RPC 文档](https://polkadot.js.org/docs/substrate/rpc) 或 [查询文档](https://polkadot.js.org/docs/substrate/storage) 中指定的任何端点，请[提交问题](https://github.com/SimplyVC/polkadot_api_server/issues)，我们将考虑在未来的版本中添加。如果您想尝试自己添加，还可以查看我们的[贡献指南](CONTRIBUTING.md)。

## 设计与功能

想要了解更多关于 API 服务器的设计和功能集，请[点击这里](doc/DESIGN_AND_FEATURES.md)查看详细信息。

## 准备好查询了吗？

如果您准备在您的 Polkadot 节点上尝试使用 API 服务器，请按照[这个指南](doc/INSTALL_AND_RUN.md)设置并运行 API 服务器。

## 开始使用

1. **安装和配置**：按照提供的安装指南进行安装和配置，确保所有的依赖项都已正确安装。
   
2. **运行服务器**：运行 API 服务器后，它将开始监听来自 Polkadot 网络的查询请求。

3. **发送查询**：使用您选择的编程语言通过封装好的 API 端点发送查询，以获取所需的链上数据。

4. **处理数据**：API 服务器将查询结果返回给您的应用程序，您可以根据需要处理和使用这些数据。

5. **定制和扩展**：根据您的具体需求，参与到我们的项目中来，通过提交问题或贡献代码来帮助改进 API 服务器。

祝您使用愉快，有效地从 Polkadot 网络获取信息！
