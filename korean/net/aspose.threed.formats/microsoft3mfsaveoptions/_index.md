---
title: "클래스 Microsoft3MFSaveOptions"
second_title: "Aspose.3D for .NET API 참조"
description: "Aspose.ThreeD.Formats.Microsoft3MFSaveOptions class. Microsoft 3MF 파일에 대한 저장 옵션"
type: docs
weight: 1350
url: /ko/net/aspose.threed.formats/microsoft3mfsaveoptions/
---
## Microsoft3MFSaveOptions class

Microsoft 3MF 파일에 대한 저장 옵션.

```csharp
public class Microsoft3MFSaveOptions : SaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Microsoft3MFSaveOptions](microsoft3mfsaveoptions/)() | `Microsoft3MFSaveOptions`를 생성합니다 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BuildAll](../../aspose.threed.formats/microsoft3mfsaveoptions/buildall/) { get; set; } | 씬의 모든 지오메트리를 인쇄 가능하도록 표시합니다. 또는 [`SetBuildable`](../microsoft3mfformat/setbuildable/)을 사용하여 노드를 수동으로 인쇄 가능하도록 표시할 수 있습니다. 기본값은 true입니다. |
| [EnableCompression](../../aspose.threed.formats/microsoft3mfsaveoptions/enablecompression/) { get; set; } | 출력 3mf 파일에 압축을 활성화합니다. 기본값은 true입니다. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 텍스트 기반 파일에 대한 기본 인코딩을 가져오거나 설정합니다. 기본값은 null이며, 이는 가져오기/내보내기 도구가 사용할 인코딩을 결정함을 의미합니다. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 씬에서 사용된 텍스처를 출력 디렉터리로 복사하려고 시도합니다. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 현재 저장/로드 옵션에 지정된 파일 형식을 가져옵니다. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 내보내기/가져오기 장면의 파일 이름입니다. 선택 사항이지만 OBJ의 재질과 같은 외부 자산을 직렬화할 때 유용합니다. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | OBJ와 같은 일부 파일은 외부 파일에 의존하며, 조회 경로를 통해 **Aspose.3D**가 외부 파일을 찾아 로드할 수 있게 합니다. |

### 또 보기

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


