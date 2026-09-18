# neutral-online DLL 分发仓库

通道：neutral-online；版本：2026.09.18.1800；业务 DLL：99。授权：现有在线授权，Enforce。

本次提供同通道完整安装包用于客户安装。 FullDllRuntime ZIP 提供运行依赖；FullDllSDK ZIP 提供 DLL、配套 LIB 和必要接口头文件，仍为开发接口候选。Git 拉取和 GitHub 自动生成的 Source code ZIP 只包含说明及清单，不能直接运行程序。

便携运行 FullDllRuntime 前须安装匹配的 Microsoft Visual C++ x64 运行库。客户实际使用推荐同通道完整安装包；运行 ZIP 不含现场数据库、算法 INI 和机器人控制程序。

模块必须与同批清单和接口版本配套，不能任意跨版本混装。SDK 头文件可能含 C++ 模板、内联定义和 Qt 生成接口；不含应用 .cpp 实现、PDB、私钥、现场配置或授权缓存。使用匹配的 MSVC v143 x64 Release /MD、Qt 6.7.3 和第三方依赖。重编模块后需重新生成并验证完整清单。

品牌单机版须插入已授权密码狗，使用独立安装包，不接入联网 OTA。在线版须完成在线许可。未执行真实机器人运动验收。
