# 🧸 GlobalMedia

## 前言

![](https://shields.io/badge/-移除重复规则-ff69b4) ![](https://shields.io/badge/-DOMAIN与DOMAIN--SUFFIX合并-green) ![](https://shields.io/badge/-DOMAIN--SUFFIX间合并-critical) ![](https://shields.io/badge/-DOMAIN--SUFFIX与DOMAIN--KEYWORD合并-blue) ![](https://shields.io/badge/-IP--CIDR(6)合并-blueviolet) ![](https://shields.io/badge/-MITM--HOSTNAME合并-brightgreen) 

GlobalMedia规则由《RULE GENERATOR 规则生成器》自动生成。

分流规则是互联网公共服务的域名和IP地址汇总，所有数据均收集自互联网公开信息，不代表我们支持或使用这些服务。

请通过【中华人民共和国 People's Republic of China】合法的互联网出入口信道访问规则中的地址，并确保在使用过程中符合相关法律法规。

## 规则统计

最后更新时间：2023-11-29 02:13:35

各类型规则统计：
| 类型 | 数量(条)  | 
| ---- | ----  |
| DOMAIN | 29  | 
| DOMAIN-KEYWORD | 25  | 
| DOMAIN-SUFFIX | 1253  | 
| IP-CIDR | 918  | 
| IP-CIDR6 | 6  | 
| PROCESS-NAME | 13  | 
| TOTAL | 2244  | 


## Clash 

#### 使用说明
- GlobalMedia.yaml，请使用 behavior: "classical"。
- GlobalMedia_Classical.yaml，请使用 behavior: "classical"。
- GlobalMedia_Domain.yaml，请使用 behavior: "domain"。

#### 配置建议
- GlobalMedia_Domain.yaml 单独使用。
- GlobalMedia_Classical.yaml 单独使用。
- GlobalMedia.yaml、GlobalMedia_Domain.yaml 共同使用。

#### 规则链接
**MASTER分支 (每日更新)**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/GlobalMedia/GlobalMedia.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/GlobalMedia/GlobalMedia_Classical.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/GlobalMedia/GlobalMedia_Domain_For_Clash.txt

**MASTER分支 CDN (每日更新)**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/GlobalMedia/GlobalMedia.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/GlobalMedia/GlobalMedia_Classical.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Clash/GlobalMedia/GlobalMedia_Domain_For_Clash.txt

**MASTER分支 GHProxy (每日更新)**

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/GlobalMedia/GlobalMedia.yaml

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/GlobalMedia/GlobalMedia_Classical.yaml

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/GlobalMedia/GlobalMedia_Domain_For_Clash.txt

**RELEASE分支 (不定时更新)**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/GlobalMedia/GlobalMedia.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/GlobalMedia/GlobalMedia_Classical.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/GlobalMedia/GlobalMedia_Domain_For_Clash.txt

**RELEASE分支CDN (不定时更新)**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Clash/GlobalMedia/GlobalMedia.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Clash/GlobalMedia/GlobalMedia_Classical.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Clash/GlobalMedia/GlobalMedia_Domain_For_Clash.txt

**RELEASE分支 GHProxy (不定时更新)**

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/GlobalMedia/GlobalMedia.yaml

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/GlobalMedia/GlobalMedia_Classical.yaml

https://ghproxy.com/https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/GlobalMedia/GlobalMedia_Domain_For_Clash.txt

## 子规则/排除规则

当前分流规则，已包含以下子规则，除非特殊需求否则不建议重复引用：
| 子规则  |  | 
| ---- | ----  |
| YouTube | YouTubeMusic  | 


当前分流规则，已排除以下规则：
| 排除规则  | 
| ----  |
| OpenAI  | 

## 数据来源

《GlobalMedia》的数据来自以下链接，如与本项目的《GlobalMedia》规则混合使用，可能会造成规则大量重复。

- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/YouTube.list
- https://raw.githubusercontent.com/GeQ1an/Rules/master/QuantumultX/Filter/Optional/YouTube.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/Global-Services/YouTube.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Music/YouTube-Music.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Ruleset/YouTubeMusic.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyMedia.list
- https://raw.githubusercontent.com/GeQ1an/Rules/master/QuantumultX/Filter/GMedia.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Media/ForeignMedia.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Streaming.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/StreamingMedia/Video/YouTube.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Providers/Ruleset/YouTube.yaml
- https://raw.githubusercontent.com/zqzess/rule_for_quantumultX/master/QuantumultX/rules/GMedia.list
- https://rules.kr328.app/youtube.yaml
- https://rules.kr328.app/youtube@cn.yaml
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/Providers/Ruleset/YouTubeMusic.yaml
- https://ruleset.isagood.day/stream.conf
- https://ruleset.isagood.day/youtube.conf
- https://ruleset.isagood.day/youtube_all.conf
- https://ruleset.isagood.day/youtube_music.conf


感谢以上规则作者的辛勤付出（排名不分先后）。

## 最后

### 感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) [@vhdj](https://github.com/vhdj)

提供规则数据源及改进建议。

### 其他

请不要对外宣传本项目。