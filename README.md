# FuGfConfig

## 特别声明

本项目中所有内容只供学习和研究使用，不得将本项目中任何内容用于违反任何国家/地区/组织等的法律法规或相关规定的其他用途。

## 支持

本项目对 Quan X、Loon 提供完全支持

对小火箭提供能用的支持（仅仅是能用

## 使用方法

### Quan X

优先级从高到低：

```
CustomAdRules
AdRules
CustomRules
AppleRules
GFWRules
TelegramRules
BasicRules
```

### Loon

优先级从高到低：

```
CustomNoAdProxy
CustomNoAdDirect
CustomAdRules
FuckRogueSoftware
CustomProxy
TelegramRules
AppleRules
GFWRules
CustomDirect
```

```
https://raw.githubusercontent.com/dunLan0/FuGfConfig/main/ConfigFile/Loon/CustomNoAdProxy.conf, policy=PROXY, tag=CustomNoAdProxy, enabled=true

https://raw.githubusercontent.com/dunLan0/FuGfConfig/main/ConfigFile/Loon/CustomNoAdDirect.conf, policy=DIRECT, tag=CustomNoAdDirect, enabled=true

https://raw.githubusercontent.com/dunLan0/FuGfConfig/main/ConfigFile/Loon/CustomAdRules.conf, policy=Advertising, tag=CustomAd, enabled=true

https://raw.githubusercontent.com/dunLan0/FuGfConfig/main/ConfigFile/Loon/CustomProxy.conf, policy=PROXY, tag=CustomProxy, enabled=true

https://raw.githubusercontent.com/dunLan0/FuGfConfig/main/ConfigFile/Loon/TelegramRules.conf, policy=PROXY, tag=TelegramRules, enabled=true

https://raw.githubusercontent.com/dunLan0/FuGfConfig/main/ConfigFile/Loon/AppleRules.conf, policy=Apple, tag=Apple, enabled=true

https://raw.githubusercontent.com/dunLan0/FuGfConfig/main/ConfigFile/Loon/GFWRules.conf, policy=PROXY, tag=FuckGFW, enabled=true

https://raw.githubusercontent.com/dunLan0/FuGfConfig/main/ConfigFile/Loon/CustomDirect.conf, policy=DIRECT, tag=CustomDirect, enabled=true

```

### 对于 FuckRogueSoftware 规则的说明

此规则极其激进，仅保证软件最低程度功能的正常使用，使用需谨慎（目前仅支持 Loon

```

https://raw.githubusercontent.com/dunLan0/FuGfConfig/main/ConfigFile/Loon/FuckRogueSoftware.conf, policy=Advertising, tag=FuckRogueSoftware, enabled=true

```

## 感谢

本项目的数据大部分来自一下项目，在此对他们表示感谢（以下排名不分先后

[Shadowrocket-ADBlock-Rules](https://github.com/h2y/Shadowrocket-ADBlock-Rules)

[neohosts](https://github.com/neoFelhz/neohosts)

[gfwlist](https://github.com/gfwlist/gfwlist)

[SS-Rule-Snippet](https://github.com/Hackl0us/SS-Rule-Snippet#%E5%85%B3%E4%BA%8E%E9%A1%B9%E7%9B%AE)

[ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)
