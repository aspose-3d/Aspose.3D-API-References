---
title: "ImageRenderOptions"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/imagerenderoptions/
---
## ImageRenderOptions class

Scene.render(com.aspose.threed.Camera, java.lang.String, com.aspose.threed.Vector2, java.lang.String, com.aspose.threed.ImageRenderOptions) 및 Scene.render(com.aspose.threed.Camera, com.aspose.threed.TextureData, com.aspose.threed.ImageRenderOptions)의 옵션


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | ImageRenderOptions 인스턴스를 초기화합니다. |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| 이름 | 설명 |
| --- | --- |
| getBackgroundColor() | 렌더 결과의 배경 색상입니다. |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| 이름 | 설명 |
| --- | --- |
| setBackgroundColor(value) | 렌더 결과의 배경 색상입니다. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| 이름 | 설명 |
| --- | --- |
| getAssetDirectories() | 외부 자산(예: 텍스처)을 저장하는 디렉터리 |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| 이름 | 설명 |
| --- | --- |
| getEnableShadows() | 그림자를 렌더링할지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| 이름 | 설명 |
| --- | --- |
| setEnableShadows(value) | 그림자를 렌더링할지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### getName{#getName}

| 이름 | 설명 |
| --- | --- |
| getName() | 이름을 가져오거나 설정합니다. 이름. |

 **Result:**



---


### setName{#setName}

| 이름 | 설명 |
| --- | --- |
| setName(value) | 이름을 가져오거나 설정합니다. 이름. |

 **Result:**



---


### getProperties{#getProperties}

| 이름 | 설명 |
| --- | --- |
| getProperties() | 모든 속성의 컬렉션을 가져옵니다. |

 **Result:**



---


### removeProperty{#removeProperty}

| 이름 | 설명 |
| --- | --- |
| removeProperty(property) | 동적 속성을 제거합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | 속성 | 제거할 속성은 무엇입니까 |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| 이름 | 설명 |
| --- | --- |
| removeProperty(property) | 이름으로 식별된 지정된 속성을 제거합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| 이름 | 설명 |
| --- | --- |
| getProperty(property) | 지정된 속성의 값을 가져옵니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | String | 속성 이름 |

 **Result:**
Object


---


### setProperty{#setProperty}

| 이름 | 설명 |
| --- | --- |
| setProperty(property, value) | 지정된 속성의 값을 설정합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | String | 속성 이름 |
| value | Object | 속성의 값 |

 **Result:**
Object


---


### findProperty{#findProperty}

| 이름 | 설명 |
| --- | --- |
| findProperty(propertyName) | 속성을 찾습니다. 동적 속성 (Created by CreateDynamicProperty/SetProperty) 또는 네이티브 속성(Identified by its name) 일 수 있습니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| propertyName | String | 속성 이름. |

 **Result:**
속성


---



