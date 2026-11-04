---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Aspose.3D for .NET API 참조"
description: "FileSystem 메서드. 더미 파일 시스템을 생성하고 읽기/쓰기 작업은 더미 작업입니다."
type: docs
weight: 10
url: /ko/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

더미 파일 시스템을 생성하고, 읽기/쓰기 작업은 더미 작업입니다.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### 반환 값

더미 파일 시스템

## 예제

다음 코드는 파일을 메모리로 내보내는 방법과 모든 종속 파일 생성을 무시하는 방법을 보여줍니다.

```csharp
//재질을 사용하여 장면을 생성합니다
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//저장 옵션을 생성하고 파일 시스템을 지정하여 종속 파일이 메모리에 기록되도록 합니다
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//obj의 재질 파일 이름은 obj의 파일 이름과 연결되어 있으므로 명시적인 이름이 필요합니다.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### 또 보기

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


