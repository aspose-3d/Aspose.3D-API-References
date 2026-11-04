---
title: "Enum BoneLinkMode"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Enum Aspose.ThreeD.Deformers.BoneLinkMode. Una modalità di collegamento delle ossa si riferisce al modo in cui un osso è connesso o collegato al suo osso genitore all'interno di una struttura gerarchica"
type: docs
weight: 200
url: /it/net/aspose.threed.deformers/bonelinkmode/
---
## BoneLinkMode enumeration

La modalità di collegamento di un osso si riferisce al modo in cui un osso è connesso o collegato al suo osso genitore all'interno di una struttura gerarchica.

```csharp
public enum BoneLinkMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Normalize | `0` | In questa modalità, le trasformazioni delle ossa figlie sono normalizzate rispetto alle trasformazioni dell'osso genitore. |
| Additive | `1` | La modalità additiva calcola le trasformazioni delle ossa figlie aggiungendo le loro trasformazioni locali a quelle delle ossa genitore. |
| TotalOne | `2` | Total One garantisce che le trasformazioni combinate delle ossa genitore e figlia producano una trasformazione combinata che si scala a una lunghezza complessiva di un'unità. |

### Vedi anche

* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


