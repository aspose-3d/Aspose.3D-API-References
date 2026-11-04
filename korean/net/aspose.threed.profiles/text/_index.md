---
title: "클래스 Text"
second_title: "Aspose.3D for .NET API 참조"
description: "Aspose.ThreeD.Profiles.Text 클래스. 텍스트 프로파일 이 프로파일은 글꼴과 텍스트를 사용하여 윤곽을 설명합니다"
type: docs
weight: 1820
url: /ko/net/aspose.threed.profiles/text/
---
## Text class

텍스트 프로파일, 이 프로파일은 글꼴과 텍스트를 사용하여 윤곽을 설명합니다.

```csharp
public class Text : Profile
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Text](text/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Content](../../aspose.threed.profiles/text/content/) { get; set; } | 텍스트 내용 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | 내보내기 시 이 엔터티를 제외할지 여부를 가져오거나 설정합니다. |
| [Font](../../aspose.threed.profiles/text/font/) { get; set; } | 텍스트의 글꼴. |
| [FontSize](../../aspose.threed.profiles/text/fontsize/) { get; set; } | 글꼴 크기 비율. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 이름을 가져오거나 설정합니다. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 첫 번째 부모 노드를 가져오거나 설정합니다. 첫 번째 부모 노드를 설정하면 이 엔터티는 다른 부모 노드와 분리됩니다. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | 모든 부모 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 부모 노드에 연결될 수 있습니다. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 모든 속성의 컬렉션을 가져옵니다. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | 이 객체가 속한 씬을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 속성을 찾습니다. 이는 동적 속성(CreateDynamicProperty/SetProperty로 생성) 또는 네이티브 속성(이름으로 식별)일 수 있습니다. |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | 렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 지정된 속성의 값을 가져옵니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 동적 속성을 제거합니다. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 이름으로 식별된 지정된 속성을 제거합니다. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 지정된 속성의 값을 설정합니다 |

## 예제

다음 코드는 지정된 글꼴 파일을 사용하여 텍스트에서 3D 메시를 만드는 방법을 보여줍니다.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### 또 보기

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


