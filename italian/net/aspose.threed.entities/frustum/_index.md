---
title: Frustum
second_title: Riferimento API Aspose.3D per .NET
description: La classe base diCamera./camera eLight./light
type: docs
weight: 350
url: /it/net/aspose.threed.entities/frustum/
---
## Frustum class

La classe base di[`Camera`](../camera) e[`Light`](../light)

```csharp
public abstract class Frustum : Entity, IOrientable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect) { get; set; } | Ottiene o imposta le proporzioni del frustum |
| [Direction](../../aspose.threed.entities/frustum/direction) { get; set; } | Ottiene o imposta la direzione in cui sta guardando la telecamera. Le modifiche a questa proprietà influiranno anche sul[`LookAt`](./lookat) e[`Target`](./target) . |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Ottiene o imposta se escludere questa entità durante l'esportazione. |
| [FarPlane](../../aspose.threed.entities/frustum/farplane) { get; set; } | Ottiene o imposta la distanza del piano lontano del tronco. |
| [LookAt](../../aspose.threed.entities/frustum/lookat) { get; set; } | Ottiene o imposta la posizione interessata che sta guardando la telecamera. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Ottiene o imposta il nome. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane) { get; set; } | Ottiene o imposta la distanza del piano vicino del tronco. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight) { get; set; } | Ottiene o imposta l'altezza quando frustum nella proiezione ortografica. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Ottiene o imposta il primo nodo padre, se è impostato il primo nodo padre, questa entità verrà scollegata dagli altri nodi padre. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Ottiene tutti i nodi principali, un'entità può essere collegata a più nodi principali per l'istanza geometrica |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Ottiene la raccolta di tutte le proprietà. |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode) { get; set; } | Ottiene o imposta la modalità di orientamento del tronco Questa proprietà funziona solo quando il[`Target`](./target) è null. Se il valore èFixedTarget , la direzione è sempre calcolata dalla struttura[`LookAt`](./lookat) Altrimenti il[`LookAt`](./lookat)è sempre calcolato dal[`Direction`](./direction) |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Ottiene la scena a cui appartiene questo oggetto |
| [Target](../../aspose.threed.entities/frustum/target) { get; set; } | Ottiene o imposta il target che la telecamera sta guardando. Se l'utente supporta questa proprietà, dovrebbe essere prima di[`LookAt`](./lookat) proprietà. |
| [Up](../../aspose.threed.entities/frustum/up) { get; set; } | Ottiene o imposta la direzione verso l'alto della telecamera |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Trova la proprietà. Può essere una proprietà dinamica (creata da CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata dal nome) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Ottiene il riquadro di delimitazione dell'entità corrente nel suo sistema di coordinate dello spazio oggetti. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey)() | Ottiene la chiave del renderer di entità registrato nel renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Ottieni il valore della proprietà specificata |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Rimuove una proprietà dinamica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Rimuove la proprietà specificata identificata da nome |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Imposta il valore della proprietà specificata |

### Guarda anche

* class [Entity](../../aspose.threed/entity)
* interface [IOrientable](../iorientable)
* spazio dei nomi [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* assemblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
