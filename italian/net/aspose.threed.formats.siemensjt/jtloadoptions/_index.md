---
title: "Classe JtLoadOptions"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Classe Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions. Opzioni di caricamento per Siemens JT"
type: docs
weight: 1380
url: /it/net/aspose.threed.formats.siemensjt/jtloadoptions/
---
## JtLoadOptions class

Opzioni di caricamento per Siemens JT

```csharp
public class JtLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Ottiene o imposta la codifica predefinita per i file basati su testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare. (Ereditato da [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Ottiene il formato file specificato nell'opzione Salva/Carica corrente. (Ereditato da [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ. (Ereditato da [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Consente all'utente di gestire come amministrare le dipendenze esterne durante il caricamento/salvataggio. (Ereditato da [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | Carica le informazioni PMI dal file JT se possibile, i dati saranno salvati come proprietà "PMI" di [`AssetInfo`](../../aspose.threed/scene/assetinfo/). Il valore predefinito è false. |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | Carica le proprietà dalla tabella delle proprietà di JT come proprietà Aspose.3D. Il valore predefinito è false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentiranno ad Aspose.3D di cercare i file esterni da caricare. (Ereditato da [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |

### Vedi anche

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)


