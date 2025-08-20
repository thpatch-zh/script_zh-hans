# script_zh-hans

![Repo Size](https://img.shields.io/github/repo-size/thpatch-zh/script_zh-hans.svg?label=RepoSize&style=flat-square)
[![touhou patch center](https://img.shields.io/badge/Require-thcrap-yellow.svg?style=flat-square)](http://thpatch.net)
[![GitHub issues](https://img.shields.io/github/issues/yanstory/tpZHCNex.svg?label=Issues&style=flat-square)](https://github.com/thpatch-zh/script_zh-hans/issues)

[thcrap食用方法](https://thpatch.rcopky.top/attention/readme.html)

[Touhou Patch Center中文站](https://thpatch.rcopky.top/)

## Language Select / 言語選択

- [简体中文](#thpatch-简体中文-附加补丁包)
- [English](#thpatch-zh-hans-ex-patches)

## thpatch 简体中文 附加补丁包

此仓库包含了thpatch简体中文的附加补丁：

- ```tsa```：上海爱丽丝幻乐团作品附加补丁包，效果类似于```nmlgc/script_latin```。

  - ```tsa``` 包含了部分STG作汉化文本正常显示所需的支持文件，配置简体中文补丁时需同时配置本补丁包。

- ```taso```：黄昏边境作品附加补丁包（常用于心绮楼后的黄昏STG作品），效果*依旧*类似于```nmlgc/script_latin```。

  - ```taso``` 包含了许多黄昏作汉化所需的底层框架优化文件，配置简体中文补丁时需同时配置本补丁包。

- **注：目前已将```taso```与```tsa```加入简体中文分支补丁默认依赖配置，一般情况下无需额外考虑配置的问题，但若您的简体中文补丁出现显示问题，请仍然优先检查这两个补丁有没有正常生效。**


### 特别感谢

- brliron
- nmlgc
- the thpatch team

---
## thpatch zh-hans ex-patches

This repository includes supplement patches for thpatch ``zh-hans`` (***Simplified Chinese***) :

- ```tsa```： Supplement patch for Team Shanghai Alice's game, works similarly to ```nmlgc/script_latin```.

  - Contains foundamental files for Team Shanghai Alice's game localization, Simplified Chinese patches won't work on some of those games without this patch.

- ```taso```: Supplement patch for Tasofro's game (usually used for FTG like HM and later), *also* works similarly to ```nmlgc/script_latin```.

  - Contains foundamental files for Tasofro's game localization, Simplified Chinese patches won't work on Tasofro games without this patch.

- **Note: Both ```taso``` and ```tsa``` are now added as dependencies of ```lang_zh-hans``` patch. In general, there is no need to install them seperately.**


### Special Thanks

- brliron
- nmlgc
- the thpatch team
