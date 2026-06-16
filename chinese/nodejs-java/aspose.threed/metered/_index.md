---
title: "计量的"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/metered/
---
## Metered class

提供设置计量密钥的方法。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化此类的一个新实例。 |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| 名称 | 描述 |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | 设置计量的公钥和私钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这就足够了。然而，如果始终无法上传使用数据且超过 24 小时，许可证将被设置为评估状态。为避免这种情况，您应定期检查许可证状态，如果处于评估状态，请再次调用此 API。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| publicKey | 字符串 | 公钥 |
| privateKey | 字符串 | 私钥 |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| 名称 | 描述 |
| --- | --- |
| getConsumptionQuantity() | 获取消耗文件大小 |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| 名称 | 描述 |
| --- | --- |
| getConsumptionCredit() | 获取消耗额度 |

 **Result:**
BigDecimal


---



