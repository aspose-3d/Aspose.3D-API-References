---
title: "Classe JtLoadOptions"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Classe Aspose.ThreeD.Formats.JtLoadOptions. Opzioni di caricamento per Siemens JT"
type: docs
weight: 1310
url: /it/net/aspose.threed.formats/jtloadoptions/
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
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Ottiene o imposta la codifica predefinita per i file basati su testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Ottiene il formato file specificato nell'opzione Salva/Carica corrente. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Il nome file della scena esportata/importata. È opzionale, ma utile quando si serializzano risorse esterne come i materiali OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Consente all'utente di gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [LoadPMI](../../aspose.threed.formats/jtloadoptions/loadpmi/) { get; set; } | Carica le informazioni PMI dal file JT se possibile, i dati saranno salvati come proprietà "PMI" di [`AssetInfo`](../../aspose.threed/scene/assetinfo/). Il valore predefinito è false. |
| [LoadProperties](../../aspose.threed.formats/jtloadoptions/loadproperties/) { get; set; } | Carica le proprietà dalla tabella delle proprietà di JT come proprietà Aspose.3D. Il valore predefinito è false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentiranno ad Aspose.3D di cercare i file esterni da caricare. |

### Vedi anche

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


