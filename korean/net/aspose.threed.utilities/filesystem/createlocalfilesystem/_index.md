---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Aspose.3D for .NET API 참조"
description: "FileSystem 메서드. 로컬 디렉터리만 접근하도록 새로운 FileSystem을 초기화합니다. 이 FileSystem 인스턴스에서의 모든 파일 읽기/쓰기는 지정된 디렉터리로 매핑됩니다."
type: docs
weight: 20
url: /ko/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

새로운 [`FileSystem`](../)을 초기화합니다. 로컬 디렉터리만 접근합니다. 이 FileSystem 인스턴스에서의 모든 파일 읽기/쓰기는 지정된 디렉터리로 매핑됩니다.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 디렉터리 | String | 물리 파일 시스템에 있는 디렉터리를 가상 루트 디렉터리로 사용합니다. |

### 반환 값

로컬 파일 접근을 제공하는 파일 시스템의 새 인스턴스

### 예외

| 예외 | 조건 |
| --- | --- |
| FileNotFoundException | 디렉터리를 찾을 수 없을 때 발생합니다. |

## 예제

다음 코드는 파일을 가져오고 지정된 디렉터리에서 종속 파일을 제공하는 방법을 보여줍니다.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//로드 옵션 인스턴스를 생성하고 로컬 파일 시스템을 지정합니다.
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//파일을 로드합니다.
var scene = Scene.FromFile(inputFile, opt);
```

### 또 보기

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


