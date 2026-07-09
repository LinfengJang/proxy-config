## 关于分流规则的使用

> 分流规则是一系列网站，IP 地址等的集合，搭配策略使用可以让对应的网站/服务走对应的代理节点。
>
> Quantumult X 的规则文件中，DOMAIN 需要修改为 HOST，所以需要使用资源解析器。

以微信分流规则为例，首先复制下面的订阅链接。

```
https://raw.githubusercontent.com/LinfengJang/proxy-config/refs/heads/main/rules/weixin.list
```

- **Loon**：配置 —> 规则 —> 规则 —> 右上角 + 按钮 —> 添加订阅 —> 将链接复制到 URL/FileName，然后选择对应的策略 —> 右上角 ✔️按钮
- **Quantumult X**：长按顶部粉色分流规则选项卡 —> 点击右上角 🔗+ 按钮 —> 将订阅链接复制进资源路径 —> 右上角 ✔️按钮
- **Surge**：首页 —> 通用 —> 代理规则 —> 新增 —> 添加规则集 —> 在外部规则集中输入订阅链接，并选择对应策略 —> 右上角 ✔️按钮
- 