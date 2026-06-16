---
title: "ICommandList"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يقوم بترميز تسلسل من الأوامر التي سيتم إرسالها إلى وحدة معالجة الرسومات للتصوير."
type: docs
weight: 240
url: /ar/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

يقوم بترميز تسلسل من الأوامر التي سيتم إرسالها إلى وحدة معالجة الرسومات للتصوير.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | ربط مجموعة الوصف بالمخطط الحالي |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | ربط مخزن الفهارس للعرض |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | ربط نسخة خط الأنابيب للعرض |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | ربط مخزن الرؤوس للعرض |
| [draw()](#draw--) | رسم بدون مخزن فهارس |
| [draw(int start, int count)](#draw-int-int-) | رسم بدون مخزن فهارس |
| [drawIndex()](#drawIndex--) | إصدار رسم مفهرس إلى قائمة الأوامر |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | إصدار رسم مفهرس إلى قائمة الأوامر |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | دفع الثابت إلى خط الأنابيب |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | دفع الثابت إلى خط الأنابيب |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


ربط مجموعة الوصف بالمخطط الحالي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


ربط مخزن الفهارس للعرض

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


ربط نسخة خط الأنابيب للعرض

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


ربط مخزن الرؤوس للعرض

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


رسم بدون مخزن فهارس

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


رسم بدون مخزن فهارس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بدء | int |  |
| عدد | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


إصدار رسم مفهرس إلى قائمة الأوامر

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


إصدار رسم مفهرس إلى قائمة الأوامر

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بدء | int | المؤشر الأول للرسم |
| عدد | int | عدد المؤشرات للرسم |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


دفع الثابت إلى خط الأنابيب

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stage | int | أي مرحلة من المظلل ستستهلك البيانات الثابتة |
| بيانات | byte[] | البيانات التي سيتم إرسالها إلى المظلل |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


دفع الثابت إلى خط الأنابيب

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stage | int | أي مرحلة من المظلل ستستهلك البيانات الثابتة |
| بيانات | byte[] | البيانات التي سيتم إرسالها إلى المظلل |
| الحجم | int | البايتات للكتابة إلى خط الأنابيب |

