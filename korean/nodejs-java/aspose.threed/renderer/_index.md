---
title: "Renderer"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/renderer/
---
## Renderer class

렌더러에 대한 컨텍스트.  @hideconstructor


## 메서드

### getShaderSet{#getShaderSet}

| 이름 | 설명 |
| --- | --- |
| getShaderSet() | 씬을 렌더링하는 데 사용되는 셰이더 세트를 가져오거나 설정합니다. |

 **Result:**



---


### setShaderSet{#setShaderSet}

| 이름 | 설명 |
| --- | --- |
| setShaderSet(value) | 씬을 렌더링하는 데 사용되는 셰이더 세트를 가져오거나 설정합니다. |

 **Result:**



---


### getVariables{#getVariables}

| 이름 | 설명 |
| --- | --- |
| getVariables() | 렌더링에 사용되는 내부 변수에 접근합니다. |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| 이름 | 설명 |
| --- | --- |
| getPresetShaders() | 프리셋 셰이더 세트를 가져오거나 설정합니다. 속성값은 PresetShaders 정수 상수입니다. |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| 이름 | 설명 |
| --- | --- |
| setPresetShaders(value) | 프리셋 셰이더 세트를 가져오거나 설정합니다. 속성값은 PresetShaders 정수 상수입니다. |

 **Result:**



---


### getRenderFactory{#getRenderFactory}

| 이름 | 설명 |
| --- | --- |
| getRenderFactory() | 렌더링 관련 객체를 생성하는 팩토리를 가져옵니다. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| 이름 | 설명 |
| --- | --- |
| getAssetDirectories() | 외부 자산을 저장하는 디렉터리 |

 **Result:**



---


### getPostProcessings{#getPostProcessings}

| 이름 | 설명 |
| --- | --- |
| getPostProcessings() | 활성화된 후처리 체인 |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| 이름 | 설명 |
| --- | --- |
| getEnableShadows() | 그림자를 활성화할지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| 이름 | 설명 |
| --- | --- |
| setEnableShadows(value) | 그림자를 활성화할지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### getRenderTarget{#getRenderTarget}

| 이름 | 설명 |
| --- | --- |
| getRenderTarget() | 다음 렌더링 작업이 수행될 렌더 대상을 지정합니다. |

 **Result:**



---


### getNode{#getNode}

| 이름 | 설명 |
| --- | --- |
| getNode() | 월드 변환 행렬을 제공하는 데 사용되는 Node 인스턴스를 가져오거나 설정합니다. |

 **Result:**



---


### setNode{#setNode}

| 이름 | 설명 |
| --- | --- |
| setNode(value) | 월드 변환 행렬을 제공하는 데 사용되는 Node 인스턴스를 가져오거나 설정합니다. |

 **Result:**



---


### getFrustum{#getFrustum}

| 이름 | 설명 |
| --- | --- |
| getFrustum() | 뷰 행렬을 제공하는 데 사용되는 프러스텀을 가져오거나 설정합니다. |

 **Result:**



---


### setFrustum{#setFrustum}

| 이름 | 설명 |
| --- | --- |
| setFrustum(value) | 뷰 행렬을 제공하는 데 사용되는 프러스텀을 가져오거나 설정합니다. |

 **Result:**



---


### getRenderStage{#getRenderStage}

| 이름 | 설명 |
| --- | --- |
| getRenderStage() | 현재 렌더 단계를 가져옵니다. 이 속성의 값은 RenderStage 정수 상수입니다. |

 **Result:**



---


### getMaterial{#getMaterial}

| 이름 | 설명 |
| --- | --- |
| getMaterial() | 셰이더에서 사용되는 재질 정보를 제공하는 데 사용되는 재질을 가져오거나 설정합니다. |

 **Result:**



---


### setMaterial{#setMaterial}

| 이름 | 설명 |
| --- | --- |
| setMaterial(value) | 셰이더에서 사용되는 재질 정보를 제공하는 데 사용되는 재질을 가져오거나 설정합니다. |

 **Result:**



---


### getShader{#getShader}

| 이름 | 설명 |
| --- | --- |
| getShader() | 지오메트리를 렌더링하는 데 사용되는 셰이더 인스턴스를 가져오거나 설정합니다. |

 **Result:**



---


### setShader{#setShader}

| 이름 | 설명 |
| --- | --- |
| setShader(value) | 지오메트리를 렌더링하는 데 사용되는 셰이더 인스턴스를 가져오거나 설정합니다. |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| 이름 | 설명 |
| --- | --- |
| getFallbackEntityRenderer() | 엔티티에 특수 렌더러가 정의되지 않은 경우 대체 엔티티 렌더러를 가져오거나 설정합니다. |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| 이름 | 설명 |
| --- | --- |
| setFallbackEntityRenderer(value) | 엔티티에 특수 렌더러가 정의되지 않은 경우 대체 엔티티 렌더러를 가져오거나 설정합니다. |

 **Result:**



---


### clearCache{#clearCache}

| 이름 | 설명 |
| --- | --- |
| clearCache() | 캐시를 수동으로 지웁니다. Aspose.3D는 재질/지오메트리와 같은 일부 객체를 렌더 파이프라인과 호환되는 내부 타입에 캐시합니다. 씬에 큰 변경이 있을 때 수동으로 호출해야 합니다. |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| 이름 | 설명 |
| --- | --- |
| getPostProcessing(name) | 렌더러에서 지원하는 내장 포스트 프로세서를 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| nam | String | null |

 **Result:**
후처리


---


### execute{#execute}

| 이름 | 설명 |
| --- | --- |
| execute(postProcessing, result) | 지정된 렌더 대상에서 포스트 프로세싱을 실행합니다. |

 **Result:**
후처리


---


### createRenderer{#createRenderer}

| 이름 | 설명 |
| --- | --- |
| createRenderer() | 기본 프로필로 새로운 Renderer를 생성합니다. |

 **Result:**
Renderer


---


### registerEntityRenderer{#registerEntityRenderer}

| 이름 | 설명 |
| --- | --- |
| registerEntityRenderer(renderer) | 지정된 엔터티에 대한 엔터티 렌더러를 등록합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| rendere | EntityRenderer | null |

 **Result:**
Renderer


---


### render{#render}

| 이름 | 설명 |
| --- | --- |
| render(renderTarget) | 지정된 대상을 렌더링합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
Renderer


---



