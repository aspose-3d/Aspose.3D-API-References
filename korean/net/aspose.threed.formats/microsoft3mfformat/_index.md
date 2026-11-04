---
title: "클래스 Microsoft3MFFormat"
second_title: "Aspose.3D for .NET API 참조"
description: "**Aspose.ThreeD.Formats.Microsoft3MFFormat** 클래스. 3MF 관련 유틸리티와 함께 Microsoft 3MF용 파일 형식 인스턴스"
type: docs
weight: 1340
url: /ko/net/aspose.threed.formats/microsoft3mfformat/
---
## Microsoft3MFFormat class

3MF 관련 유틸리티와 함께 Microsoft 3MF용 파일 형식 인스턴스.

```csharp
public class Microsoft3MFFormat : FileFormat
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | 현재 파일 형식으로 장면 내보내기를 **Aspose.3D**가 지원하는지 확인합니다. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | 현재 파일 형식에서 장면 가져오기를 **Aspose.3D**가 지원하는지 확인합니다. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | 파일 형식 콘텐츠 유형을 가져옵니다 |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | 이 유형의 확장자 이름을 가져옵니다. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | 이 유형의 확장자 이름들을 가져옵니다. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | 파일 형식 유형을 가져옵니다 |
| [Version](../../aspose.threed/fileformat/version/) { get; } | 파일 형식 버전을 가져옵니다 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | 이 파일 형식에 대한 기본 로드 옵션을 생성합니다 |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | 이 파일 형식에 대한 기본 저장 옵션을 생성합니다 |
| [GetObjectType](../../aspose.threed.formats/microsoft3mfformat/getobjecttype/)(Node) | 지정된 노드의 모델 유형을 가져옵니다. |
| [GetTransformForBuild](../../aspose.threed.formats/microsoft3mfformat/gettransformforbuild/)(Node) | 빌드에 사용되는 노드의 변환 행렬을 가져옵니다. |
| [IsBuildable](../../aspose.threed.formats/microsoft3mfformat/isbuildable/)(Node) | 이 노드가 빌드로 표시되었는지 확인합니다. |
| [SetBuildable](../../aspose.threed.formats/microsoft3mfformat/setbuildable/)(Node, bool, Matrix4?) |  |
| [SetObjectType](../../aspose.threed.formats/microsoft3mfformat/setobjecttype/)(Node, string) | 지정된 노드의 모델 유형을 설정합니다. 가능한 값: model, surface, solid, support, other |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | 형식을 문자열로 변환 |

### 또 보기

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


