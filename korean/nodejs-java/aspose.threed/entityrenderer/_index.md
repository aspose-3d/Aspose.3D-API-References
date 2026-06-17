---
title: "EntityRenderer"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

다양한 종류의 엔터티에 대한 렌더링을 구현하려면 이 클래스를 서브클래스화하십시오.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(key, features) | EntityRenderer의 생성자 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| key | String | EntityRenderer의 키 |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(key) | EntityRenderer의 생성자 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| key | String | EntityRenderer의 키 |

 **Result:**



---


### initialize{#initialize}

| 이름 | 설명 |
| --- | --- |
| initialize(renderer) | EntityRenderer를 초기화합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| rendere | Renderer | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| 이름 | 설명 |
| --- | --- |
| resetSceneCache() | 씬이 변경되었거나 제거되었습니다. 이 경우 씬 수준의 렌더 리소스를 해제해야 합니다. |

 **Result:**



---


### frameBegin{#frameBegin}

| 이름 | 설명 |
| --- | --- |
| frameBegin(renderer, renderQueue) | 프레임 렌더링을 시작합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| renderer | Renderer | 현재 렌더러 |
| renderQueue | IRenderQueue | 렌더 큐 |

 **Result:**



---


### frameEnd{#frameEnd}

| 이름 | 설명 |
| --- | --- |
| frameEnd(renderer, renderQueue) | 프레임 렌더링을 종료합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| renderer | Renderer | 현재 렌더러 |
| renderQueue | IRenderQueue | 렌더 큐 |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| 이름 | 설명 |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | 지정된 노드/엔터티 쌍에 대한 렌더링 명령을 준비합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| renderer | Renderer | 현재 렌더러 인스턴스 |
| queue | IRenderQueue | 렌더 작업을 관리하는 데 사용되는 렌더 큐 |
| node | Node | 현재 노드 |
| entity | Entity | 렌더링이 필요한 엔터티 |

 **Result:**



---


### renderEntity{#renderEntity}

| 이름 | 설명 |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | com.aspose.threed.IRenderQueue에 푸시된 각 렌더 작업은 구체적인 렌더링 작업을 수행하기 위해 해당하는 RenderEntity 호출을 가집니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| renderer | Renderer | 그 렌더러 |
| commandList | ICommandList | 그 commandList는 렌더링 명령을 기록하는 데 사용됩니다 |
| node | Node | 그 동일한 노드가 렌더링될 엔터티의 PrepareRenderQueue에 전달되었습니다 |
| renderableResource | Object | 그 사용자 정의 객체가 PrepareRenderQueue 동안 IRenderQueue에 전달되었습니다 |
| subEntity | 숫자 | 그 서브 엔터티가 IRenderQueue에 전달된 인덱스 |

 **Result:**



---


### dispose{#dispose}

| 이름 | 설명 |
| --- | --- |
| dispose() | 그 엔터티 렌더러가 해제되고 있으며, 공유 리소스를 해제합니다. |

 **Result:**



---



