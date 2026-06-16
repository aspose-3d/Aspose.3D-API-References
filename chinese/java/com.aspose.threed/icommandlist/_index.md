---
title: "ICommandList"
second_title: "Aspose.3D for Java API 参考"
description: "对将发送到 GPU 进行渲染的命令序列进行编码。"
type: docs
weight: 240
url: /zh/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

对将发送到 GPU 进行渲染的命令序列进行编码。
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | 将描述符集绑定到当前管线 |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | 绑定用于渲染的索引缓冲区 |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | 绑定用于渲染的管线实例 |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | 绑定用于渲染的顶点缓冲区 |
| [draw()](#draw--) | 在没有索引缓冲区的情况下绘制 |
| [draw(int start, int count)](#draw-int-int-) | 在没有索引缓冲区的情况下绘制 |
| [drawIndex()](#drawIndex--) | 在命令列表中发出索引绘制 |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | 在命令列表中发出索引绘制 |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | 将常量推送到管线 |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | 将常量推送到管线 |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


将描述符集绑定到当前管线

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


绑定用于渲染的索引缓冲区

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


绑定用于渲染的管线实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


绑定用于渲染的顶点缓冲区

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


在没有索引缓冲区的情况下绘制

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


在没有索引缓冲区的情况下绘制

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 开始 | int |  |
| 计数 | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


在命令列表中发出索引绘制

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


在命令列表中发出索引绘制

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 开始 | int | 要绘制的第一个索引 |
| 计数 | int | 要绘制的索引计数 |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


将常量推送到管线

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 阶段 | int | 哪个着色器阶段将使用常量数据 |
| 数据 | byte[] | 将发送到着色器的数据 |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


将常量推送到管线

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 阶段 | int | 哪个着色器阶段将使用常量数据 |
| 数据 | byte[] | 将发送到着色器的数据 |
| 大小 | int | 写入管线的字节数 |

