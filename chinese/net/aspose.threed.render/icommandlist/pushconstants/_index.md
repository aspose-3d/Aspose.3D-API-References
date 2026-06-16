---
title: "ICommandList.PushConstants"
second_title: "Aspose.3D for .NET API 参考"
description: "ICommandList 方法。将常量推送到管线"
type: docs
weight: 70
url: /zh/net/aspose.threed.render/icommandlist/pushconstants/
---
## PushConstants(ShaderStage, byte[]) {#pushconstants}

将常量推送到管线

```csharp
public void PushConstants(ShaderStage stage, byte[] data)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stage | ShaderStage | 哪个着色器阶段将消耗常量数据 |
| 数据 | Byte[] | 将发送到着色器的数据 |

### 另请参见

* enum [ShaderStage](../../shaderstage/)
* interface [ICommandList](../)
* namespace [Aspose.ThreeD.Render](../../icommandlist/)
* assembly [Aspose.3D](../../../)

---

## PushConstants(ShaderStage, byte[], int) {#pushconstants_1}

将常量推送到管线

```csharp
public void PushConstants(ShaderStage stage, byte[] data, int size)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stage | ShaderStage | 哪个着色器阶段将消耗常量数据 |
| 数据 | Byte[] | 将发送到着色器的数据 |
| 尺寸 | Int32 | 写入管线的字节 |

### 另请参见

* enum [ShaderStage](../../shaderstage/)
* interface [ICommandList](../)
* namespace [Aspose.ThreeD.Render](../../icommandlist/)
* assembly [Aspose.3D](../../../)


