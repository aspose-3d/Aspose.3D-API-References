---
title: Renderer
second_title: .NET API 참조용 Aspose.3D
description: 렌더러에 대한 컨텍스트입니다.
type: docs
weight: 2100
url: /ko/net/aspose.threed.render/renderer/
---
## Renderer class

렌더러에 대한 컨텍스트입니다.

```csharp
public abstract class Renderer : IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AssetDirectories](../../aspose.threed.render/renderer/assetdirectories/) { get; } | 외부 자산을 저장한 디렉토리 |
| [EnableShadows](../../aspose.threed.render/renderer/enableshadows/) { get; set; } | 그림자 활성화 여부를 가져오거나 설정합니다. |
| [FallbackEntityRenderer](../../aspose.threed.render/renderer/fallbackentityrenderer/) { get; set; } | 엔터티에 특수 렌더러가 정의되어 있지 않은 경우 폴백 엔터티 렌더러를 가져오거나 설정합니다. |
| virtual [Frustum](../../aspose.threed.render/renderer/frustum/) { get; set; } | 보기 행렬을 제공하는 데 사용되는 절두체를 가져오거나 설정합니다. |
| virtual [Material](../../aspose.threed.render/renderer/material/) { get; set; } | 셰이더에서 사용되는 재료 정보를 제공하는 데 사용되는 재료를 가져오거나 설정합니다. |
| [Node](../../aspose.threed.render/renderer/node/) { get; set; } | 가져오거나 설정합니다.[`Node`](./node/) 월드 변환 매트릭스를 제공하는 데 사용되는 인스턴스. |
| [PostProcessings](../../aspose.threed.render/renderer/postprocessings/) { get; } | 활성 사후 처리 chain |
| [PresetShaders](../../aspose.threed.render/renderer/presetshaders/) { get; set; } | 사전 설정 셰이더 set 를 가져오거나 설정합니다. |
| abstract [RenderFactory](../../aspose.threed.render/renderer/renderfactory/) { get; } | 렌더링 관련 개체를 빌드하기 위한 팩터리를 가져옵니다. |
| [RenderStage](../../aspose.threed.render/renderer/renderstage/) { get; } | 현재 렌더링 단계를 가져옵니다. |
| [RenderTarget](../../aspose.threed.render/renderer/rendertarget/) { get; } | 다음 렌더링 작업이 수행될 렌더링 대상을 지정합니다. |
| [Shader](../../aspose.threed.render/renderer/shader/) { get; set; } | 지오메트리를 렌더링하는 데 사용되는 셰이더 인스턴스를 가져오거나 설정합니다. |
| [ShaderSet](../../aspose.threed.render/renderer/shaderset/) { get; set; } | scene 를 렌더링하는 데 사용된 셰이더 세트를 가져오거나 설정합니다. |
| [Variables](../../aspose.threed.render/renderer/variables/) { get; } | rendering 에 사용되는 내부 변수에 대한 액세스 |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [CreateRenderer](../../aspose.threed.render/renderer/createrenderer/)() | 새로 만들기`Renderer`기본 프로필 사용. |
| virtual [ClearCache](../../aspose.threed.render/renderer/clearcache/)() | 수동으로 캐시를 지웁니다. Aspose.3D는 재료/형상과 같은 일부 개체를 렌더링 파이프라인과 호환되는 내부 유형으로 캐시합니다. 장면에 주요 변경 사항이 있을 때 수동으로 호출해야 합니다. |
| [Dispose](../../aspose.threed.render/renderer/dispose/)() | 폐기`Renderer` 및 모든 관련 리소스 |
| abstract [Execute](../../aspose.threed.render/renderer/execute/)(PostProcessing, IRenderTarget) | 지정된 렌더링 대상 에서 사후 처리를 실행합니다. |
| [GetPostProcessing](../../aspose.threed.render/renderer/getpostprocessing/)(string) | 렌더러에서 지원하는 내장 포스트 프로세서를 가져옵니다. |
| virtual [RegisterEntityRenderer](../../aspose.threed.render/renderer/registerentityrenderer/)(EntityRenderer) | 지정된 entity 에 대한 엔티티 렌더러를 등록합니다. |
| virtual [Render](../../aspose.threed.render/renderer/render/)(IRenderTarget) | 지정된 target 를 렌더링합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.ThreeD.Render](../../aspose.threed.render/)
* 집회 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
