---
title: "FontFile.FromFile"
second_title: "Aspose.3D for .NET API 참조"
description: "FontFile 메서드. 파일 이름에서 FontFile을 로드"
type: docs
weight: 10
url: /ko/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

파일 이름에서 FontFile 로드

```csharp
public static FontFile FromFile(string fileName)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | String | 폰트 파일 경로 |

### 반환 값

FontFile 인스턴스

### 예외

| 예외 | 조건 |
| --- | --- |
| IOException | 파일에서 읽기에 실패했을 때 발생합니다. |

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

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


