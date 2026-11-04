---
title: "FileSystem.CreateZipFileSystem"
second_title: "Aspose.3D for .NET API リファレンス"
description: "FileSystem メソッド。指定された zip ファイルまたは zip ストリームへの読み取り専用アクセスを提供するファイルシステムを作成します。ファイルシステムは開閉操作の後に破棄されます。"
type: docs
weight: 40
url: /ja/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

指定された zip ファイルまたは zip ストリームへの読み取り専用アクセスを提供するファイルシステムを作成します。ファイルシステムは開閉操作の後に破棄されます。

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | zip ファイルにアクセスするためのストリーム |
| baseDir | 文字列 | zip ファイル内のベースディレクトリ。 |

### 戻り値

zip ファイルシステム

### 例外

| 例外 | 条件 |
| --- | --- |
| IOException | ストリームの読み取りに失敗したときにスローされます。 |

## 備考

これは読み取り専用ファイルシステムです。そのため書き込み操作はサポートされていません。

## 例

次のコードは、ファイルをインポートし、zip アーカイブファイル内の依存ファイルを提供する方法を示しています。

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//ロードオプションのインスタンスを作成し、zip ファイルシステムを指定します。
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//ファイルをロードします
var scene = Scene.FromFile(inputFile, opt);
```

### 関連項目

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

指定された zip ファイルまたは zip ストリームへの読み取り専用アクセスを提供するファイルシステムです。ファイルシステムは開閉操作の後に破棄されます。

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | ZIP ファイルへのファイル名。 |

### 戻り値

zip ファイルシステム

### 例外

| 例外 | 条件 |
| --- | --- |
| IOException | ストリームの読み取りに失敗したときにスローされます。 |

## 例

次のコードは、ファイルをインポートし、zip アーカイブファイル内の依存ファイルを提供する方法を示しています。

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//ロードオプションのインスタンスを作成し、zip ファイルシステムを指定します。
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//ファイルをロードします
var scene = Scene.FromFile(inputFile, opt);
```

### 関連項目

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


