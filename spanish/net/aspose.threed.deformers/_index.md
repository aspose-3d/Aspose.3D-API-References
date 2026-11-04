---
title: "Aspose.ThreeD.Deformers"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Todas las clases de deformadores se definen en este espacio de nombres"
type: docs
weight: 30
url: /es/net/aspose.threed.deformers/
---
Todas las clases de deformadores se definen en este espacio de nombres

## Clases

| Clase | Descripción |
| --- | --- |
| [Bone](./bone/) | Un hueso define el subconjunto del punto de control de la geometría y establece el peso de mezcla para cada punto de control. El objeto [`Bone`](../aspose.threed.deformers/bone/) no puede usarse directamente, se utiliza una instancia de [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) para deformar la geometría, y [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) incluye un conjunto de huesos, cada hueso vinculado a un nodo. NOTA: Un punto de control de una geometría puede estar vinculado a más de un hueso. |
| [Deformer](./deformer/) | Clase base para [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) y [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) |
| [MorphTargetChannel](./morphtargetchannel/) | Un MorphTargetChannel es utilizado por [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) para organizar las geometrías objetivo. Algunos formatos de archivo como FBX admiten múltiples canales en paralelo. |
| [MorphTargetDeformer](./morphtargetdeformer/) | MorphTargetDeformer proporciona animación por vértice. MorphTargetDeformer organiza todos los objetivos a través de [`MorphTargetChannel`](../aspose.threed.deformers/morphtargetchannel/), cada canal puede organizar múltiples objetivos. Un uso común del deformer de objetivo de morph es aplicar expresiones faciales a un personaje. Se pueden encontrar más detalles en https://en.wikipedia.org/wiki/Morph_target_animation |
| [SkinDeformer](./skindeformer/) | Un deformer de piel contiene varios huesos para trabajar, cada hueso mezcla una parte de la geometría mediante los pesos de los puntos de control. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [BoneLinkMode](./bonelinkmode/) | El modo de enlace de un hueso se refiere a la forma en que un hueso está conectado o enlazado a su hueso padre dentro de una estructura jerárquica. |


