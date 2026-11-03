---
title: "Aspose.ThreeD.Animation"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Der Animations-Namespace von Aspose.3D, in dem alle animationsbezogenen Klassen definiert sind"
type: docs
weight: 20
url: /de/net/aspose.threed.animation/
---
Der Animations‑Namensraum von Aspose.3D, alle animationsbezogenen Klassen sind in diesem Namensraum definiert

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [AnimationChannel](./animationchannel/) | Ein Kanal ordnet das Komponentenfeld einer Eigenschaft einer Menge von Keyframe‑Sequenzen zu |
| [AnimationClip](./animationclip/) | Der Animationsclip ist eine Sammlung von Animationen. Die Szene kann einen oder mehrere Animationsclips enthalten. |
| [AnimationNode](./animationnode/) | Aspose.3D unterstützt eine Animationshierarchie, jede Animation kann aus mehreren Animationen und der Keyframe‑Definition einer Animation zusammengesetzt werden. [`AnimationNode`](../aspose.threed.animation/animationnode/) definiert die Transformation eines Eigenschaftswerts über die Zeit, zum Beispiel kann ein Animationsknoten verwendet werden, um die Transformation eines Knotens oder andere numerische Eigenschaften eines [`A3DObject`](../aspose.threed/a3dobject/) zu steuern. |
| [BindPoint](./bindpoint/) | Ein [`BindPoint`](../aspose.threed.animation/bindpoint/) wird normalerweise auf einer Eigenschaft eines Objekts erstellt; einige Eigenschaftstypen enthalten mehrere Komponentenfelder (wie ein Vector3‑Feld). [`BindPoint`](../aspose.threed.animation/bindpoint/) erzeugt für jedes Komponentenfeld einen Kanal und verbindet das Feld über die Kanäle mit einer oder mehreren Keyframe‑Sequenz‑Instanz(en). |
| [Extrapolation](./extrapolation/) | Extrapolation definiert, wie vorzugehen ist, wenn ein abgetasteter Wert außerhalb des durch den ersten und letzten Keyframe definierten Bereichs liegt. |
| [KeyFrame](./keyframe/) | Ein Keyframe wird hauptsächlich durch eine Zeit und einen Wert definiert; bei einigen Interpolationstypen werden Tangente/Spannung/Bias/Kontinuität ebenfalls zur Berechnung des endgültigen abgetasteten Wertes verwendet. Abgetastete Werte an einer Zeitposition ohne Keyframe werden durch die Keyframes zwischen dem vorherigen und dem nächsten Keyframe interpoliert. Werte vor/nach dem ersten/letzten Keyframe werden von der Klasse [`Extrapolation`](../aspose.threed.animation/extrapolation/) berechnet. |
| [KeyframeSequence](./keyframesequence/) | Die Sequenz von Keyframes beschreibt die Transformation eines abgetasteten Wertes über die Zeit. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [ExtrapolationType](./extrapolationtype/) | Extrapolationstyp. |
| [Interpolation](./interpolation/) | Der Interpolationstyp des Keyframes. |
| [StepMode](./stepmode/) | Interpolations‑Schrittmodus. |
| [WeightedMode](./weightedmode/) | Gewichteter Modus. |


