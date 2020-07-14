---
description: 调整Nethermind节点配置的属性列表
---

# 配置

有两种方法可以配置Nethermind节点。一种方法是简单地更改要运行的网络配置的 `.cfg` 文件中的配置属性。每个具有默认设置的 `.cfg` 文件都附加在Nethermind软件包中，可以在`configs` 文件夹中找到。

另一种方法是通过将标志传递给`Nethermind.Runner`或`Nethermind.Launcher`来设置每个配置属性。例如：

```text
./Nethermind.Runner --config ropsten --JsonRpc.Enabled true --Init.ProcessingEnabled false
```

{% hint style="warning" %}
传递标志时，每个属性都需要以其各自的[**Module**](./)为前缀，然后是**属性名称**及**其值**，例如`--Init.IsMining true`
{% endhint %}

{% hint style="info" %}

{% endhint %}

{% hint style="info" %}

{% endhint %}
