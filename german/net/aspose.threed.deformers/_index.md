---
title: "Aspose.ThreeD.Deformers"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Alle Deformer‑Klassen sind in diesem Namensraum definiert"
type: docs
weight: 30
url: /de/net/aspose.threed.deformers/
---
Alle Deformer‑Klassen sind in diesem Namensraum definiert

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Bone](./bone/) | Ein Knochen definiert die Teilmenge der Steuerpunkte der Geometrie und legt das Blendgewicht für jeden Steuerpunkt fest. Das [`Bone`](../aspose.threed.deformers/bone/)‑Objekt kann nicht direkt verwendet werden; eine [`SkinDeformer`](../aspose.threed.deformers/skindeformer/)‑Instanz wird verwendet, um die Geometrie zu deformieren, und [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) enthält einen Satz von Knochen, wobei jeder Knochen mit einem Knoten verknüpft ist. HINWEIS: Ein Steuerpunkt einer Geometrie kann an mehr als einem Knochen gebunden sein. |
| [Deformer](./deformer/) | Basisklasse für [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) und [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) |
| [MorphTargetChannel](./morphtargetchannel/) | Ein MorphTargetChannel wird von [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) verwendet, um die Zielgeometrien zu organisieren. Einige Dateiformate wie FBX unterstützen mehrere Kanäle parallel. |
| [MorphTargetDeformer](./morphtargetdeformer/) | MorphTargetDeformer bietet per-Vertex-Animation. MorphTargetDeformer organisiert alle Ziele über [`MorphTargetChannel`](../aspose.threed.deformers/morphtargetchannel/), wobei jeder Kanal mehrere Ziele organisieren kann. Eine gängige Anwendung des Morph‑Target‑Deformers ist das Anwenden von Gesichtsausdrücken auf einen Charakter. Weitere Details finden Sie unter https://en.wikipedia.org/wiki/Morph_target_animation |
| [SkinDeformer](./skindeformer/) | Ein SkinDeformer enthält mehrere Knochen, wobei jeder Knochen einen Teil der Geometrie anhand der Gewichte der Steuerpunkte mischt. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [BoneLinkMode](./bonelinkmode/) | Der Verknüpfungsmodus eines Knochens bezieht sich auf die Art und Weise, wie ein Knochen mit seinem übergeordneten Knochen innerhalb einer hierarchischen Struktur verbunden oder verknüpft ist. |


