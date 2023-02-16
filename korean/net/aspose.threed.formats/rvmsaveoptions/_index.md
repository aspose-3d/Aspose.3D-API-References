---
title: RvmSaveOptions
second_title: .NET API 참조용 Aspose.3D
description: Aveva PDMS RVM 파일에 대한 옵션 저장.
type: docs
weight: 1330
url: /ko/net/aspose.threed.formats/rvmsaveoptions/
---
## RvmSaveOptions class

Aveva PDMS RVM 파일에 대한 옵션 저장.

```csharp
public class RvmSaveOptions : SaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RvmSaveOptions](rvmsaveoptions/#constructor)() | 의 생성자`RvmSaveOptions` |
| [RvmSaveOptions](rvmsaveoptions/#constructor_1)(FileContentType) | 의 생성자`RvmSaveOptions` |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AttributeListFile](../../aspose.threed.formats/rvmsaveoptions/attributelistfile/) { get; set; } | 속성 목록 파일의 파일 이름을 가져오거나 설정합니다. 내보내기는 이 속성이 정의되지 않은 경우 .rvm 파일 이름을 기반으로 이름을 생성합니다. 기본값은 null입니다. |
| [AttributePrefix](../../aspose.threed.formats/rvmsaveoptions/attributeprefix/) { get; set; } | 내보낼 속성의 접두사를 가져오거나 설정합니다. 내보낸 속성에는 접두사가 포함되지 않으며 접두사가 다른 사용자 지정 속성은 내보내지 않습니다. 기본값은 'rvm:'입니다. 예를 들어 속성이 rvm:Refno인 경우 =345, 내보낸 속성은 Refno = 345이고 접두사는 제거됩니다. |
| [Author](../../aspose.threed.formats/rvmsaveoptions/author/) { get; set; } | 작성자 정보, 기본값은 '3d@aspose' |
| [CreationTime](../../aspose.threed.formats/rvmsaveoptions/creationtime/) { get; set; } | 이 파일을 내보낸 타임스탬프, 기본값은 현재 time |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 텍스트 기반 파일의 기본 인코딩을 가져오거나 설정합니다. 기본값은 가져오기/내보내기가 사용할 인코딩을 결정한다는 의미인 null입니다. |
| [ExportAttributes](../../aspose.threed.formats/rvmsaveoptions/exportattributes/) { get; set; } | 속성 목록을 외부 .att 파일로 내보낼지 여부를 가져오거나 설정합니다. 기본값은 false입니다. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 현재 저장/로드 옵션에 지정된 파일 형식을 가져옵니다. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 내보내기/가져오기 장면의 파일 이름입니다. 선택 사항이지만 OBJ의 재질과 같은 외부 자산을 직렬화할 때 유용합니다. |
| [FileNote](../../aspose.threed.formats/rvmsaveoptions/filenote/) { get; set; } | 파일 헤더의 파일 메모. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 사용자가 로드/저장 중에 외부 종속성을 관리하는 방법을 처리할 수 있습니다. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | OBJ와 같은 일부 파일은 외부 파일에 의존하며 조회 경로를 통해 Aspose.3D는 로드할 외부 파일을 찾을 수 있습니다. |

### 또한보십시오

* class [SaveOptions](../saveoptions/)
* 네임스페이스 [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* 집회 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->