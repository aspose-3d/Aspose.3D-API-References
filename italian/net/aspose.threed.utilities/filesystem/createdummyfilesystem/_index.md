---
title: "FileSystem.CreateDummyFileSystem"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Metodo FileSystem. Crea un file system fittizio; le operazioni di lettura/scrittura sono operazioni fittizie"
type: docs
weight: 10
url: /it/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

Crea un file system fittizio, le operazioni di lettura/scrittura sono operazioni fittizie.

```csharp
public static FileSystem CreateDummyFileSystem()
```

### Valore di ritorno

Un file system fittizio

## Esempi

Il codice seguente mostra come esportare un file in memoria e ignorare tutta la generazione di file dipendenti.

```csharp
//crea una scena con materiale
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//crea un'opzione di salvataggio e specifica il file system, così il file dipendente verrà scritto in memoria
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//Il nome del file materiale dell'obj è associato al nome del file dell'obj, quindi è necessario un nome esplicito.
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### Vedi anche

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


