# Subweb Remote Config

这个仓库用于自行维护从以下地址克隆下来的 Subconverter 规则配置：

```text
https://subweb.s3.fr-par.scw.cloud/RemoteConfig/customized/ytoo.ini
```

## 文件位置

```text
RemoteConfig/customized/ytoo.ini
```

上传到 GitHub 后，可以使用 GitHub Raw 地址替换原始配置地址。

## GOOGLEAI 分组

刷新订阅后，可在 Clash 的 `GOOGLEAI` 分组选择 JP、Proxies、HK、SG、TW 或 US，首次加载默认使用 JP。

Gemini、AI Studio、Antigravity、Code Assist、NotebookLM 等产品域名跟随 [MetaCubeX Google DeepMind 清单](https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/classical/google-deepmind.list) 更新。[补充清单](RemoteConfig/customized/GoogleAI.list) 维护登录、模型区域端点、客户端更新和上报域名。两份清单优先于 OpenAI 和通用 Google 规则。

规则按主机名匹配。其他应用使用清单中的 Google 登录、存储、字体或上报主机时，也会走 `GOOGLEAI`。
