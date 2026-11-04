---
title: "FileSystem.CreateZipFileSystem"
second_title: "Aspose.3D for .NET API 참조"
description: "FileSystem 메서드. 지정된 zip 파일 또는 zip 스트림에 대한 읽기 전용 액세스를 제공하는 파일 시스템을 생성합니다. 파일 시스템은 열기/저장 작업 후에 해제됩니다."
type: docs
weight: 40
url: /ko/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

지정된 zip 파일 또는 zip 스트림에 대한 읽기 전용 액세스를 제공하는 파일 시스템을 생성합니다. 파일 시스템은 열기/저장 작업 후에 해제됩니다.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | zip 파일에 접근하기 위한 스트림 |
| baseDir | String | zip 파일 내부의 기본 디렉터리. |

### 반환 값

zip 파일 시스템

### 예외

| 예외 | 조건 |
| --- | --- |
| IOException | 스트림을 읽지 못했을 때 발생합니다. |

## 비고

이것은 읽기 전용 파일 시스템이므로 쓰기 작업을 지원하지 않습니다.

## 예제

다음 코드는 파일을 가져오고 zip 아카이브 파일에서 종속 파일을 제공하는 방법을 보여줍니다.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//로드 옵션 인스턴스를 생성하고 zip 파일 시스템을 지정합니다.
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//파일을 로드합니다.
var scene = Scene.FromFile(inputFile, opt);
```

### 또 보기

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

지정된 zip 파일 또는 zip 스트림에 대한 읽기 전용 액세스를 제공하는 파일 시스템입니다. 파일 시스템은 열기/저장 작업 후에 해제됩니다.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | String | ZIP 파일에 대한 파일 이름. |

### 반환 값

zip 파일 시스템

### 예외

| 예외 | 조건 |
| --- | --- |
| IOException | 스트림을 읽지 못했을 때 발생합니다. |

## 예제

다음 코드는 파일을 가져오고 zip 아카이브 파일에서 종속 파일을 제공하는 방법을 보여줍니다.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//로드 옵션 인스턴스를 생성하고 zip 파일 시스템을 지정합니다.
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//파일을 로드합니다.
var scene = Scene.FromFile(inputFile, opt);
```

### 또 보기

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


