---
title: "Text.Font"
second_title: "Aspose.3D for .NET API 참조"
description: "Text 속성. 텍스트의 글꼴"
type: docs
weight: 30
url: /ko/net/aspose.threed.profiles/text/font/
---
## Text.Font property

텍스트의 글꼴.

```csharp
public FontFile Font { get; set; }
```

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

* class [FontFile](../../fontfile/)
* class [Text](../)
* namespace [Aspose.ThreeD.Profiles](../../text/)
* assembly [Aspose.3D](../../../)


