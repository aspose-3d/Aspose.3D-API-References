---
title: EntityRenderer
second_title: Aspose.3D for Java API 레퍼런스
description: 다양한 종류의 엔터티에 대한 렌더링을 구현하려면 이를 서브클래스화하십시오.
type: docs
weight: 53
url: /ko/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

다양한 종류의 엔터티에 대한 렌더링을 구현하려면 이를 서브클래스화하십시오.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | [EntityRenderer](../../com.aspose.threed/entityrenderer)의 생성자 |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | [EntityRenderer](../../com.aspose.threed/entityrenderer)의 생성자 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [dispose()](#dispose--) | 엔터티 렌더러가 해제되고 있으며, 공유 리소스를 해제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | 프레임 렌더링을 시작합니다 |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | 프레임 렌더링을 종료합니다 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | 엔터티 렌더러를 초기화합니다 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | 지정된 노드/엔터티 쌍에 대한 렌더링 명령을 준비합니다. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | [IRenderQueue](../../com.aspose.threed/irenderqueue)에 푸시된 각 렌더 작업은 구체적인 렌더링 작업을 수행하기 위해 해당하는 RenderEntity 호출을 가집니다. |
| [resetSceneCache()](#resetSceneCache--) | 씬이 변경되었거나 제거되었습니다. 이 경우 씬 수준의 렌더 리소스를 해제해야 합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


[EntityRenderer](../../com.aspose.threed/entityrenderer)의 생성자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 엔티티 렌더러의 키 |
| 기능 | 바이트 | 엔티티 렌더러의 추가 기능 |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


[EntityRenderer](../../com.aspose.threed/entityrenderer)의 생성자

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 엔티티 렌더러의 키 |

### dispose() {#dispose--}
```
public void dispose()
```


엔터티 렌더러가 해제되고 있으며, 공유 리소스를 해제합니다.

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
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


프레임 렌더링을 시작합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 현재 렌더러 |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | 렌더 큐 |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


프레임 렌더링을 종료합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 현재 렌더러 |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | 렌더 큐 |

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
### initialize(Renderer renderer) {#initialize-com.aspose.threed.Renderer-}
```
public void initialize(Renderer renderer)
```


엔터티 렌더러를 초기화합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity) {#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-}
```
public void prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)
```


지정된 노드/엔터티 쌍에 대한 렌더링 명령을 준비합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 현재 렌더러 인스턴스 |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | 렌더 작업을 관리하는 데 사용되는 렌더 큐 |
| node | [Node](../../com.aspose.threed/node) | 현재 노드 |
| entity | [Entity](../../com.aspose.threed/entity) | 렌더링이 필요한 엔티티 |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


[IRenderQueue](../../com.aspose.threed/irenderqueue)에 푸시된 각 렌더 작업은 구체적인 렌더링 작업을 수행하기 위해 해당하는 RenderEntity 호출을 가집니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | 렌더러 |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | 렌더링 명령을 기록하는 데 사용되는 commandList |
| node | [Node](../../com.aspose.threed/node) | 렌더링될 엔티티의 PrepareRenderQueue에 전달된 동일한 노드 |
| renderableResource | java.lang.Object | PrepareRenderQueue 중 IRenderQueue에 전달된 사용자 정의 객체 |
| subEntity | int | IRenderQueue에 전달된 하위 엔티티의 인덱스 |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


씬이 변경되었거나 제거되었습니다. 이 경우 씬 수준의 렌더 리소스를 해제해야 합니다.

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

