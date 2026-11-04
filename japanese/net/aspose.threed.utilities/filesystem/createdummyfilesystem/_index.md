---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Aspose.3D for .NET API リファレンス"
description: "FileSystem メソッド。ダミーのファイルシステムを作成し、読み書き操作はダミー操作です"
type: docs
weight: 10
url: /ja/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

ダミーのファイルシステムを作成し、読み書き操作はダミー操作です。

```csharp
public static FileSystem CreateDummyFileSystem()
```

### 戻り値

ダミーのファイルシステム

## 例

以下のコードは、ファイルをメモリにエクスポートし、すべての依存ファイル生成を無視する方法を示しています。

```csharp
//マテリアルでシーンを作成する
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//保存オプションを作成し、ファイルシステムを指定すると、依存ファイルがメモリに書き込まれます
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//obj のマテリアルファイル名は obj のファイル名に関連付けられているため、明示的な名前が必要です。
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### 関連項目

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


