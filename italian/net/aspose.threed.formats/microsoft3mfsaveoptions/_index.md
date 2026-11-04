---
title: "Classe Microsoft3MFSaveOptions"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Classe Aspose.ThreeD.Formats.Microsoft3MFSaveOptions. Opzioni di salvataggio per file Microsoft 3MF"
type: docs
weight: 1350
url: /it/net/aspose.threed.formats/microsoft3mfsaveoptions/
---
## Microsoft3MFSaveOptions class

Opzioni di salvataggio per file Microsoft 3MF.

```csharp
public class Microsoft3MFSaveOptions : SaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Microsoft3MFSaveOptions](microsoft3mfsaveoptions/)() | Crea un `Microsoft3MFSaveOptions` |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BuildAll](../../aspose.threed.formats/microsoft3mfsaveoptions/buildall/) { get; set; } | Contrassegna tutte le geometrie nella scena come stampabili. Oppure puoi contrassegnare manualmente il nodo come stampabile tramite [`SetBuildable`](../microsoft3mfformat/setbuildable/) Il valore predefinito è true |
| [EnableCompression](../../aspose.threed.formats/microsoft3mfsaveoptions/enablecompression/) { get; set; } | Abilita la compressione sul file 3mf di output. Il valore predefinito è true |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Ottiene o imposta la codifica predefinita per i file basati su testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Prova a copiare le texture utilizzate nella scena nella directory di output. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Ottiene il formato file specificato nell'opzione Salva/Carica corrente. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Il nome file della scena esportata/importata. È opzionale, ma utile quando si serializzano risorse esterne come i materiali OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Consente all'utente di gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentiranno ad Aspose.3D di cercare i file esterni da caricare. |

### Vedi anche

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


