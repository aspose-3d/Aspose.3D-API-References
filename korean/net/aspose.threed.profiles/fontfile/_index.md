---
title: "클래스 FontFile"
second_title: "Aspose.3D for .NET API 참조"
description: "Aspose.ThreeD.Profiles.FontFile 클래스. 글꼴 파일은 글리프 정의를 포함하며 텍스트 프로파일을 만드는 데 사용됩니다"
type: docs
weight: 1720
url: /ko/net/aspose.threed.profiles/fontfile/
---
## FontFile class

글꼴 파일은 글리프 정의를 포함하고, 이는 텍스트 프로파일을 만드는 데 사용됩니다.

```csharp
public abstract class FontFile : A3DObject
```

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 이름을 가져오거나 설정합니다. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 모든 속성의 컬렉션을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | 파일 이름에서 FontFile 로드 |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | 바이트에서 FontFile 파싱 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 속성을 찾습니다. 이는 동적 속성(CreateDynamicProperty/SetProperty로 생성) 또는 네이티브 속성(이름으로 식별)일 수 있습니다. |
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

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


