---
title: "JtLoadOptions 클래스"
second_title: "Aspose.3D for .NET API 참조"
description: "Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions 클래스. Siemens JT 로드 옵션"
type: docs
weight: 1380
url: /ko/net/aspose.threed.formats.siemensjt/jtloadoptions/
---
## JtLoadOptions class

Siemens JT 로드 옵션

```csharp
public class JtLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 텍스트 기반 파일의 기본 인코딩을 가져오거나 설정합니다. 기본값은 null이며, 이는 가져오기/내보내기 도구가 사용할 인코딩을 결정함을 의미합니다. ([`IOConfig`](../../aspose.threed.formats/ioconfig/)에서 상속됨.) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 현재 저장/로드 옵션에 지정된 파일 형식을 가져옵니다. ([`IOConfig`](../../aspose.threed.formats/ioconfig/)에서 상속됨.) |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 내보내기/가져오기 씬의 파일 이름입니다. 선택 사항이지만 OBJ의 재질과 같은 외부 자산을 직렬화할 때 유용합니다. ([`IOConfig`](../../aspose.threed.formats/ioconfig/)에서 상속됨.) |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 로드/저장 중 외부 종속성을 관리하는 방법을 사용자가 처리하도록 허용합니다. ([`IOConfig`](../../aspose.threed.formats/ioconfig/)에서 상속됨.) |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | 가능한 경우 JT 파일에서 PMI 정보를 로드합니다. 데이터는 [`AssetInfo`](../../aspose.threed/scene/assetinfo/)의 "PMI" 속성으로 저장됩니다. 기본값은 false입니다. |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | JT의 속성 테이블에서 Aspose.3D 속성으로 로드합니다. 기본값은 false입니다. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | OBJ와 같이 외부 파일에 의존하는 일부 파일은 검색 경로를 통해 Aspose.3D가 외부 파일을 찾아 로드할 수 있게 합니다. ([`IOConfig`](../../aspose.threed.formats/ioconfig/)에서 상속됨.) |

### 또 보기

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)


