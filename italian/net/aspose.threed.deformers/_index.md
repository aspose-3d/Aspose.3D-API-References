---
title: Aspose.ThreeD.Deformers
second_title: Riferimento API Aspose.3D per .NET
description: Tutte le classi di deformatori sono definite in questo spazio dei nomi
type: docs
weight: 30
url: /it/net/aspose.threed.deformers/
---
Tutte le classi di deformatori sono definite in questo spazio dei nomi

## Classi

| Classe | Descrizione |
| --- | --- |
| [Bone](./bone) | Un osso definisce il sottoinsieme del punto di controllo della geometria e lo spessore di raccordo definito per ciascun punto di controllo. Il[`Bone`](../aspose.threed.deformers/bone) l'oggetto non può essere utilizzato direttamente, a[`SkinDeformer`](../aspose.threed.deformers/skindeformer) istanza viene utilizzata per deformare la geometria e[`SkinDeformer`](../aspose.threed.deformers/skindeformer)viene fornito con un set di ossa, ogni osso collegato a un nodo. NOTA: un punto di controllo di una geometria può essere limitato a più di un osso. |
| [Deformer](./deformer) | Classe base per[`SkinDeformer`](../aspose.threed.deformers/skindeformer) e[`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer) |
| [MorphTargetChannel](./morphtargetchannel) | Un MorphTargetChannel è utilizzato da[`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer) per organizzare le geometrie di destinazione. Alcuni formati di file come FBX supportano più canali in parallelo. |
| [MorphTargetDeformer](./morphtargetdeformer) | MorphTargetDeformer fornisce un'animazione per ogni vertice. MorphTargetDeformer organizza tutti i target tramite[`MorphTargetChannel`](../aspose.threed.deformers/morphtargetchannel) , ogni canale può organizzare più target. Un uso comune del morph target deformer è applicare l'espressione facciale a un personaggio. Maggiori dettagli possono essere trovati su https://en.wikipedia.org/wiki/Morph_target_animation |
| [SkinDeformer](./skindeformer) | Un deformatore della pelle contiene più ossa da lavorare, ogni osso fonde una parte della geometria in base ai pesi del punto di controllo. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
