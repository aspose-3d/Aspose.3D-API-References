---
title: "FileSystem.CreateZipFileSystem"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Metodo FileSystem. Crea un file system per fornire l'accesso in sola lettura a un file zip o a uno stream zip specificato. Il file system verrà eliminato dopo l'operazione di apertura/salvataggio"
type: docs
weight: 40
url: /it/net/aspose.threed.utilities/filesystem/createzipfilesystem/
---
## CreateZipFileSystem(Stream, string) {#createzipfilesystem}

Crea un file system per fornire l'accesso in sola lettura a un file zip o a uno stream zip specificato. Il file system verrà eliminato dopo l'operazione di apertura/salvataggio.

```csharp
public static FileSystem CreateZipFileSystem(Stream stream, string baseDir = "/")
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream per accedere al file zip |
| baseDir | String | La directory di base all'interno del file zip. |

### Valore di ritorno

Un file system zip

### Eccezioni

| eccezione | condizione |
| --- | --- |
| IOException | Generata quando non è possibile leggere dallo stream. |

## Osservazioni

Questo è un file system di sola lettura, quindi le operazioni di scrittura non sono supportate.

## Esempi

Il codice seguente mostra come importare un file e fornire i file dipendenti in un archivio zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//crea un'istanza di opzioni di caricamento e specifica un file system zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//carica il file
var scene = Scene.FromFile(inputFile, opt);
```

### Vedi anche

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)

---

## CreateZipFileSystem(string) {#createzipfilesystem_1}

File system da fornire per l'accesso in sola lettura al file zip o stream zip specificato. Il file system verrà eliminato dopo l'operazione di apertura/salvataggio.

```csharp
public static FileSystem CreateZipFileSystem(string fileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Nome del file zip. |

### Valore di ritorno

Un file system zip

### Eccezioni

| eccezione | condizione |
| --- | --- |
| IOException | Generata quando non è possibile leggere dallo stream. |

## Esempi

Il codice seguente mostra come importare un file e fornire i file dipendenti in un archivio zip.

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//crea un'istanza di opzioni di caricamento e specifica un file system zip
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateZipFileSystem("textures.zip");
//carica il file
var scene = Scene.FromFile(inputFile, opt);
```

### Vedi anche

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


