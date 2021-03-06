---
title: Metered
second_title: Aspose.3D for .NET API 参考
description: 提供设置计量键的方法
type: docs
weight: 1450
url: /zh/net/aspose.threed/metered/
---
## Metered class

提供设置计量键的方法。

```csharp
public class Metered
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Metered](metered)() | 初始化此类的新实例。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [SetMeteredKey](../../aspose.threed/metered/setmeteredkey)(string, string) | 设置计量的公钥和私钥。 如果你购买的是计量许可证，在启动应用程序时，应该调用这个API，正常情况下，这样就足够了。但是，如果总是无法上传消费数据，超过24小时，License会被设置为评估状态，为避免这种情况，您应该定期检查License状态，如果是评估状态，再次调用该API。 |
| static [GetConsumptionCredit](../../aspose.threed/metered/getconsumptioncredit)() | 获取消费信用 |
| static [GetConsumptionQuantity](../../aspose.threed/metered/getconsumptionquantity)() | 获取消费文件大小 |

### 例子

在本例中，将尝试设置计量公钥和私钥

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

组件 jar 文件:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 也可以看看

* 命名空间 [Aspose.ThreeD](../../aspose.threed)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
