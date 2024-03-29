---
title: PlySaveOptions
second_title: .NET API 참조용 Aspose.3D
description: 장면을 PLY 파일로 내보내기 위한 옵션을 저장합니다.
type: docs
weight: 1300
url: /ko/net/aspose.threed.formats/plysaveoptions/
---
## PlySaveOptions class

장면을 PLY 파일로 내보내기 위한 옵션을 저장합니다.

```csharp
public class PlySaveOptions : SaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PlySaveOptions](plysaveoptions/#constructor)() | 의 생성자`PlySaveOptions` |
| [PlySaveOptions](plysaveoptions/#constructor_1)(FileContentType) | 의 생성자`PlySaveOptions` |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ColorComponents](../../aspose.threed.formats/plysaveoptions/colorcomponents/) { get; set; } | 정점 색상의 구성 요소 이름, 기본값은 ("red", "green", "blue") |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 텍스트 기반 파일의 기본 인코딩을 가져오거나 설정합니다. 기본값은 가져오기/내보내기가 사용할 인코딩을 결정한다는 의미인 null입니다. |
| [FaceElement](../../aspose.threed.formats/plysaveoptions/faceelement/) { get; set; } | 얼굴 데이터의 요소 이름, 기본값은 "face" |
| [FaceProperty](../../aspose.threed.formats/plysaveoptions/faceproperty/) { get; set; } | 얼굴 데이터의 속성 이름, 기본값은 "vertex_index" |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 현재 저장/로드 옵션에 지정된 파일 형식을 가져옵니다. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 내보내기/가져오기 장면의 파일 이름입니다. 선택 사항이지만 OBJ의 재질과 같은 외부 자산을 직렬화할 때 유용합니다. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 사용자가 로드/저장 중에 외부 종속성을 관리하는 방법을 처리할 수 있습니다. |
| [FlipCoordinate](../../aspose.threed.formats/plysaveoptions/flipcoordinate/) { get; set; } | 장면을 저장하는 동안 좌표를 뒤집습니다. 기본값은 true 입니다. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | OBJ와 같은 일부 파일은 외부 파일에 의존하며 조회 경로를 통해 Aspose.3D는 로드할 외부 파일을 찾을 수 있습니다. |
| [NormalComponents](../../aspose.threed.formats/plysaveoptions/normalcomponents/) { get; set; } | 일반 데이터의 구성 요소 이름, 기본값은 ("nx", "ny", "nz") |
| [PointCloud](../../aspose.threed.formats/plysaveoptions/pointcloud/) { get; set; } | 장면을 포인트 클라우드로 내보냅니다. 기본값은 false입니다. |
| [PositionComponents](../../aspose.threed.formats/plysaveoptions/positioncomponents/) { get; set; } | 위치 데이터의 구성 요소 이름, 기본값은 ("x", "y", "z") |
| [TextureCoordinateComponents](../../aspose.threed.formats/plysaveoptions/texturecoordinatecomponents/) { get; set; } | 텍스처 좌표 데이터의 구성 요소 이름, 기본값은 ("u", "v") |
| [VertexElement](../../aspose.threed.formats/plysaveoptions/vertexelement/) { get; set; } | 정점 데이터의 요소 이름, 기본값은 "정점" |

### 또한보십시오

* class [SaveOptions](../saveoptions/)
* 네임스페이스 [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* 집회 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
