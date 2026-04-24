---
title: DescriptorSetUpdater
second_title: Aspose.3D for Java API 레퍼런스
description: 이 클래스는 체인 작업에서  를 업데이트하도록 허용합니다.
type: docs
weight: 42
url: /ko/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

이 클래스는 체인 작업에서 [IDescriptorSet](../../com.aspose.threed/idescriptorset) 를 업데이트하도록 허용합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | 전체 버퍼를 현재 디스크립터에 바인드합니다 |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | 버퍼를 현재 디스크립터 세트에 바인드합니다 |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | 텍스처 유닛을 현재 디스크립터 세트에 바인드합니다 |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | 버퍼를 지정된 바인딩 위치에서 현재 디스크립터 세트에 바인드합니다. |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | 버퍼를 지정된 바인딩 위치에서 현재 디스크립터 세트에 바인드합니다. |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | 텍스처 유닛을 현재 디스크립터 세트에 바인드합니다 |
| [close()](#close--) | 업데이터를 해제하고 변경 사항을 하드웨어 장치에 커밋합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### bind(IBuffer buffer) {#bind-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(IBuffer buffer)
```


전체 버퍼를 현재 디스크립터에 바인드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


버퍼를 현재 디스크립터 세트에 바인드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | 바인드할 버퍼 |
| 오프셋 | int | 바인드할 버퍼의 오프셋 |
| 크기 | int | 바인드할 버퍼의 크기 |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


텍스처 유닛을 현재 디스크립터 세트에 바인드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | 바인드할 텍스처 유닛 |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


버퍼를 지정된 바인딩 위치에서 현재 디스크립터 세트에 바인드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 바인딩 | int | 바인딩 위치 |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | 바인드할 전체 버퍼 |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


버퍼를 지정된 바인딩 위치에서 현재 디스크립터 세트에 바인드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 바인딩 | int | 바인딩 위치 |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | 바인드할 버퍼 |
| 오프셋 | int | 바인드할 버퍼의 오프셋 |
| 크기 | int | 바인드할 버퍼의 크기 |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


텍스처 유닛을 현재 디스크립터 세트에 바인드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 바인딩 | int | 바인딩 위치 |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | 바인드할 텍스처 유닛 |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


업데이터를 해제하고 변경 사항을 하드웨어 장치에 커밋합니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

