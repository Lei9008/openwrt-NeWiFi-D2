**English** | [中文](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)

A template for building OpenWrt with GitHub Actions

使用GitHub Actions构建OpenWrt的模板

## Usage 使用方法

- Click the [Use this template](https://github.com/P3TERX/Actions-OpenWrt/generate) button to create a new repository.
- 点击[使用此模板](https://github.com/P3TERX/Actions-OpenWrt/generate)按钮创建一个新的仓库.
  
- Generate `.config` files using [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) source code. ( You can change it through environment variables in the workflow file. )
- 使用[Lean's OpenWrt](https://github.com/coolsnowwolf/lede)源代码生成`.config`文件。（您可以通过工作流文件中的环境变量对其进行更改。)
  
- Push `.config` file to the GitHub repository.
- 将`.config`文件推送到GitHub存储库.
  
- Select `Build OpenWrt` on the Actions page.
- 在“操作”页面上选择“构建OpenWrt”.
  
- Click the `Run workflow` button.
- 单击“运行工作流”按钮。
  
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.
- 构建完成后，单击Actions页面右上角的Artifacts按钮下载二进制文件.
  
## Tips 提示

- It may take a long time to create a `.config` file and build the OpenWrt firmware. Thus, before create repository to build your own firmware, you may check out if others have already built it which meet your needs by simply [search `Actions-Openwrt` in GitHub](https://github.com/search?q=Actions-openwrt).
- Add some meta info of your built firmware (such as firmware architecture and installed packages) to your repository introduction, this will save others' time.
- 创建一个`.config`文件并编译OpenWrt固件可能需要很长时间。因此，在创建存储库来编译自己的固件之前，您可以通过简单的[在Github里搜索 `Actions-Openwrt`](https://github.com/search?q=Actions-openwrt)。来查询其他人是否已经编译了满足您需求的存储库。
- 在你的存储库介绍中添加一些你构建的固件的元信息（比如固件体系结构和安装的软件包），这样可以节省其他人的时间。

## Credits 致谢

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [ActionsRML/delete-workflow-runs](https://github.com/ActionsRML/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)

## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)
