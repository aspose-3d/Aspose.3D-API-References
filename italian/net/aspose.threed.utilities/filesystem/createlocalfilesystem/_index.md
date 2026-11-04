---
title: "FileSystem.CreateLocalFileSystem"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Metodo FileSystem. Inizializza un nuovo FileSystem che accede solo alla directory locale. Tutte le operazioni di lettura/scrittura dei file su questa istanza di FileSystem saranno mappate alla directory specificata"
type: docs
weight: 20
url: /it/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

Inizializza un nuovo [`FileSystem`](../) che accede solo alla directory locale. Tutte le letture/scritture dei file su questa istanza di FileSystem saranno mappate alla directory specificata.

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| directory | String | La directory nel tuo file system fisico come directory radice virtuale. |

### Valore di ritorno

Una nuova istanza del file system per fornire l'accesso ai file locali

### Eccezioni

| eccezione | condizione |
| --- | --- |
| FileNotFoundException | Generata quando la directory non può essere trovata. |

## Esempi

Il codice seguente mostra come importare un file e fornire i file dipendenti in una directory specificata

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//crea un'istanza di opzioni di caricamento e specifica un file system locale
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//carica il file
var scene = Scene.FromFile(inputFile, opt);
```

### Vedi anche

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)


