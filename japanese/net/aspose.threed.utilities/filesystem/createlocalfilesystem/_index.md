---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Aspose.3D for .NET API リファレンス"
description: "FileSystem メソッド。ローカルディレクトリのみアクセスできる新しい FileSystem を初期化します。この FileSystem インスタンス上のすべてのファイルの読み書きは、指定されたディレクトリにマッピングされます"
type: docs
weight: 20
url: /ja/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

ローカルディレクトリのみアクセスできる新しい [`FileSystem`](../) を初期化します。この FileSystem インスタンス上のすべてのファイルの読み書きは、指定されたディレクトリにマッピングされます。

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ディレクトリ | 文字列 | 仮想ルートディレクトリとして、物理ファイルシステム上のディレクトリを使用します。 |

### 戻り値

ローカルファイルアクセスを提供する新しいファイルシステムインスタンス

### 例外

| 例外 | 条件 |
| --- | --- |
| FileNotFoundException | ディレクトリが見つからない場合にスローされます。 |

## 例

次のコードは、ファイルをインポートし、指定されたディレクトリ内の依存ファイルを提供する方法を示しています。

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//ロードオプションのインスタンスを作成し、ローカルファイルシステムを指定します。
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//ファイルをロードします
var scene = Scene.FromFile(inputFile, opt);
```

### 関連項目

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


