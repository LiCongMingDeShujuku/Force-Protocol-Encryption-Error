![CLEVER DATA GIT REPO](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/0-clever-data-github.png "李聪明的数据库")

# 强制协议加密错误
#### Force Protocol Encryption Error
**发布-日期: 2006年5月20日 (评论)**

## Contents

- [中文](#中文)
- [English](#English)
- [Build Info](#Build-Info)
- [Author](#Author)
- [License](#License) 


## 中文
我常会惊讶于一个人不管做多长时间的sql administraiton，依然会对它的奇怪和不寻常大感意外。某天我在启动我的机器时收到此错误信息。很明显我无法连接到我在企业管理器中注册的任何SQL Server。这种情况会让人很抓狂，因为我们不知道是什么原因造成的问题。查看更多有关安全等的“微软证书”的文档：more] [Microsoft][ODBC SQL Server Driver][Shared Memory]Encryption not supported on SQL Server [Microsoft][ODBC SQL Server Driver][Shared Memory]ConnectionOpen (PreLoginHandshake())

这里有一个快速的解决方案。只需：开始 - >运行 - >键入：cliconfg.execheck以查看是否“强制协议加密”被启用，它不应该启用。如果未启用，你应该能够再次连接到 所有的SQL服务器。简直太疯狂了。顺便说一句，此选项默认情况下应该被禁用。 然而，我发现它可能会在安装后被启用。 可能是由于你的工作站或服务器的某些其他协作安装配置设置。 希望对你有用。


## English
i get amazed some times with how long one can be doing sql administraiton, and yet still get blindsided by the strange and unusual. i get this error message one day just starting up my machine. apparently i can’t connect to any of the SQL Servers i have registered in enterprise manager. the situation will drive you nuts cause you don’t know what ‘changed’ to create such a problem. never mind looking over documents about ‘microsoft certificates’ about security and so forth…[more] [Microsoft][ODBC SQL Server Driver][Shared Memory]Encryption not supported on SQL Server [Microsoft][ODBC SQL Server Driver][Shared Memory]ConnectionOpen (PreLoginHandshake())

here’s a quick solution.just go to: start -> run -> type in: cliconfg.execheck to see if this is enabled: “Force protocol encryption”it should NOT be enabled.once this is unchecked you should be able to connect to all your sql servers again. this issue is just plain crazy. thats it. by the way this option should be disabled by default. however; i’ve noticed that it ‘might’ be enabled after installation. possibly due to some other cooperative install config setting for your workstation, or servers. hope this is useful.


[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

- **李聪明的数据库 Lee's Clever Data**
- **Mike的数据库宝典 Mikes Database Collection**
- **李聪明的数据库** "Lee Songming"

[![Gist](https://img.shields.io/badge/Gist-李聪明的数据库-<COLOR>.svg)](https://gist.github.com/congmingshuju)
[![Twitter](https://img.shields.io/badge/Twitter-mike的数据库宝典-<COLOR>.svg)](https://twitter.com/mikesdatawork?lang=en)
[![Wordpress](https://img.shields.io/badge/Wordpress-mike的数据库宝典-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)

---
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Lee Songming](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/1-clever-data-github.png "李聪明的数据库")

