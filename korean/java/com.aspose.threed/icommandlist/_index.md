---
title: ICommandList
second_title: Aspose.3D for Java API 레퍼런스
description: GPU에 전달되어 렌더링될 명령 시퀀스를 인코딩합니다.
type: docs
weight: 240
url: /ko/java/com.aspose.threed/icommandlist/
---
```
public interface ICommandList
```

GPU에 전달되어 렌더링될 명령 시퀀스를 인코딩합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [bindDescriptorSet(IDescriptorSet descriptorSet)](#bindDescriptorSet-com.aspose.threed.IDescriptorSet-) | 디스크립터 세트를 현재 파이프라인에 바인드합니다. |
| [bindIndexBuffer(IIndexBuffer indexBuffer)](#bindIndexBuffer-com.aspose.threed.IIndexBuffer-) | 렌더링을 위해 인덱스 버퍼를 바인드합니다 |
| [bindPipeline(IPipeline pipeline)](#bindPipeline-com.aspose.threed.IPipeline-) | 렌더링을 위해 파이프라인 인스턴스를 바인드합니다 |
| [bindVertexBuffer(IVertexBuffer vertexBuffer)](#bindVertexBuffer-com.aspose.threed.IVertexBuffer-) | 렌더링을 위해 버텍스 버퍼를 바인드합니다 |
| [draw()](#draw--) | 인덱스 버퍼 없이 그리기 |
| [draw(int start, int count)](#draw-int-int-) | 인덱스 버퍼 없이 그리기 |
| [drawIndex()](#drawIndex--) | 명령 목록에 인덱스 드로우를 발행합니다 |
| [drawIndex(int start, int count)](#drawIndex-int-int-) | 명령 목록에 인덱스 드로우를 발행합니다 |
| [pushConstants(int stage, byte[] data)](#pushConstants-int-byte---) | 상수를 파이프라인에 푸시합니다 |
| [pushConstants(int stage, byte[] data, int size)](#pushConstants-int-byte---int-) | 상수를 파이프라인에 푸시합니다 |
### bindDescriptorSet(IDescriptorSet descriptorSet) {#bindDescriptorSet-com.aspose.threed.IDescriptorSet-}
```
public abstract void bindDescriptorSet(IDescriptorSet descriptorSet)
```


디스크립터 세트를 현재 파이프라인에 바인드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| descriptorSet | [IDescriptorSet](../../com.aspose.threed/idescriptorset) |  |

### bindIndexBuffer(IIndexBuffer indexBuffer) {#bindIndexBuffer-com.aspose.threed.IIndexBuffer-}
```
public abstract void bindIndexBuffer(IIndexBuffer indexBuffer)
```


렌더링을 위해 인덱스 버퍼를 바인드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| indexBuffer | [IIndexBuffer](../../com.aspose.threed/iindexbuffer) |  |

### bindPipeline(IPipeline pipeline) {#bindPipeline-com.aspose.threed.IPipeline-}
```
public abstract void bindPipeline(IPipeline pipeline)
```


렌더링을 위해 파이프라인 인스턴스를 바인드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) |  |

### bindVertexBuffer(IVertexBuffer vertexBuffer) {#bindVertexBuffer-com.aspose.threed.IVertexBuffer-}
```
public abstract void bindVertexBuffer(IVertexBuffer vertexBuffer)
```


렌더링을 위해 버텍스 버퍼를 바인드합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vertexBuffer | [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) |  |

### draw() {#draw--}
```
public abstract void draw()
```


인덱스 버퍼 없이 그리기

### draw(int start, int count) {#draw-int-int-}
```
public abstract void draw(int start, int count)
```


인덱스 버퍼 없이 그리기

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 시작 | int |  |
| 갯수 | int |  |

### drawIndex() {#drawIndex--}
```
public abstract void drawIndex()
```


명령 목록에 인덱스 드로우를 발행합니다

### drawIndex(int start, int count) {#drawIndex-int-int-}
```
public abstract void drawIndex(int start, int count)
```


명령 목록에 인덱스 드로우를 발행합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 시작 | int | 그릴 첫 번째 인덱스 |
| 갯수 | int | 그릴 인덱스의 개수 |

### pushConstants(int stage, byte[] data) {#pushConstants-int-byte---}
```
public abstract void pushConstants(int stage, byte[] data)
```


상수를 파이프라인에 푸시합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 단계 | int | 어떤 셰이더 단계가 상수 데이터를 사용할지 |
| 데이터 | byte[] | 셰이더에 전송될 데이터 |

### pushConstants(int stage, byte[] data, int size) {#pushConstants-int-byte---int-}
```
public abstract void pushConstants(int stage, byte[] data, int size)
```


상수를 파이프라인에 푸시합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 단계 | int | 어떤 셰이더 단계가 상수 데이터를 사용할지 |
| 데이터 | byte[] | 셰이더에 전송될 데이터 |
| 크기 | int | 파이프라인에 쓸 바이트 수 |

