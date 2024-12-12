# QT RSA 加密解密工具

本仓库提供了一套基于QT环境的RSA加密解密实现，包括公钥加密、公钥解密、私钥加密、私钥解密功能。同时，支持分段加密与分段解密，非常适合需要在嵌入式或桌面应用中实现安全通信的开发者。

## 特点

- **多功能性**：全面覆盖RSA加密算法的核心操作。
- **灵活性**：允许用户自定义密钥对和密钥长度，以及修改密钥文件名。
- **易于集成**：既可以通过Visual Studio打开.sln解决方案，也能直接在QT环境中通过.pro文件进行项目构建。
- **调试友好**：若需深入理解内部工作原理，可以将`RSATool.cpp`文件包含至项目，并适当配置OpenSSL动态库进行调试。

## 快速入门

1. **生成密钥对**：建议访问[https://www.bchrt.com/tools/rsa/](https://www.bchrt.com/tools/rsa/)在线生成RSA密钥对。
2. **加密解密工具**：对于快速加密解密操作，推荐站点[https://the-x.cn/cryptography/Rsa.aspx](https://the-x.cn/cryptography/Rsa.aspx)。
3. **项目开发环境**：
   - 使用VS或QT Creator打开项目文件。
   - 动态库方式使用时，确保开发环境已配置好所需的OpenSSL动态库。
   - 若要调试RSATool代码，需手动将相关源文件加入项目，并路径正确指向openssl库。

## 注意事项

- 本仓库提供的示例代码中使用的公钥和私钥是预设的，用户应替换为自己的密钥对以保障安全性。
- 密钥文件的名称、长度及类型可根据实际需求调整，但请同步更新代码中的相应设置。
- 开发过程中，请留意是否已正确处理调试与发行模式下的库文件路径问题。

通过这个工具，您可以便捷地在Qt应用程序中集成RSA加密技术，为数据传输添加一层强大的安全保障。无论是学习密码学还是开发安全软件，此资源都是宝贵的学习和实践材料。

## 下载链接

[QTRSA加密解密工具](https://pan.quark.cn/s/4b8b17bad601)