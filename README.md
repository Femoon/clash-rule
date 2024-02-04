# clash-rules
# rule providers example
```
rule-providers:
  mydirect:
    type: http
    behavior: classical
    url: "https://cdn.jsdelivr.net/gh/Femoon/clash-rule/mydirect.yaml"
    path: ./ruleset/mydirect.yaml
    interval: 86400
  myproxy:
    type: http
    behavior: classical
    url: "https://cdn.jsdelivr.net/gh/Femoon/clash-rule/myproxy.yaml"
    path: ./ruleset/myproxy.yaml
    interval: 86400
  emby:
    type: http
    behavior: classical
    url: "https://cdn.jsdelivr.net/gh/Femoon/clash-rule/emby.yaml"
    path: ./ruleset/emby.yaml
    interval: 86400
  steam:
    type: http
    behavior: classical
    url: "https://cdn.jsdelivr.net/gh/Femoon/clash-rule/steam.yaml"
    path: ./ruleset/steam.yaml
    interval: 86400
rules:
  - RULE-SET,mydirect,DIRECT
  - RULE-SET,myproxy,🚀 节点选择
  - RULE-SET,steam,DIRECT
  - RULE-SET,emby,🚀 节点选择
```
