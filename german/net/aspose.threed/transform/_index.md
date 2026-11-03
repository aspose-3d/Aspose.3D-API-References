---
title: "Klasse Transform"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Transform Klasse. Eine Transformation enthält Informationen, die den Zugriff auf Objekte für Übersetzung/Skalierung/Rotation oder Transformationsmatrix mit minimalem Aufwand ermöglichen. Dies wird für lokale Transformationen verwendet."
type: docs
weight: 2650
url: /de/net/aspose.threed/transform/
---
## Transform class

Eine Transform enthält Informationen, die den Zugriff auf die Übersetzung/Skalierung/Rotation des Objekts oder die Transformationsmatrix mit minimalem Aufwand ermöglichen. Dies wird von der lokalen Transform verwendet.

```csharp
public class Transform : A3DObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [EulerAngles](../../aspose.threed/transform/eulerangles/) { get; set; } | Liest oder setzt die Rotation, die in Euler-Winkeln dargestellt wird, gemessen in Grad |
| [GeometricRotation](../../aspose.threed/transform/geometricrotation/) { get; set; } | Liest oder setzt die geometrische Euler-Rotation (gemessen in Grad). Geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen. |
| [GeometricScaling](../../aspose.threed/transform/geometricscaling/) { get; set; } | Liest oder setzt die geometrische Skalierung. Geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen. |
| [GeometricTranslation](../../aspose.threed/transform/geometrictranslation/) { get; set; } | Liest oder setzt die geometrische Translation. Geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [PostRotation](../../aspose.threed/transform/postrotation/) { get; set; } | Liest oder setzt die Nachrotation, dargestellt in Grad |
| [PreRotation](../../aspose.threed/transform/prerotation/) { get; set; } | Liest oder setzt die Vorrotation, dargestellt in Grad |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Rotation](../../aspose.threed/transform/rotation/) { get; set; } | Liest oder setzt die Rotation, dargestellt im Quaternion. |
| [RotationOffset](../../aspose.threed/transform/rotationoffset/) { get; set; } | Liest oder setzt den Rotationsoffset |
| [RotationPivot](../../aspose.threed/transform/rotationpivot/) { get; set; } | Liest oder setzt den Rotationsdrehpunkt |
| [Scaling](../../aspose.threed/transform/scaling/) { get; set; } | Liest oder setzt die Skalierung |
| [ScalingOffset](../../aspose.threed/transform/scalingoffset/) { get; set; } | Liest oder setzt den Skalierungsversatz |
| [ScalingPivot](../../aspose.threed/transform/scalingpivot/) { get; set; } | Liest oder setzt den Skalierungsdrehpunkt |
| [TransformMatrix](../../aspose.threed/transform/transformmatrix/) { get; set; } | Liest oder setzt die Transformationsmatrix. |
| [Translation](../../aspose.threed/transform/translation/) { get; set; } | Liest oder setzt die Translation |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetEulerAngles](../../aspose.threed/transform/seteulerangles/)(double, double, double) | Setzt die Euler‑Winkel in Grad der aktuellen Transformation. |
| [SetGeometricRotation](../../aspose.threed/transform/setgeometricrotation/)(double, double, double) | Setzt die geometrische Euler‑Rotation (gemessen in Grad). Geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen. |
| [SetGeometricScaling](../../aspose.threed/transform/setgeometricscaling/)(double, double, double) | Setzt die geometrische Skalierung. Geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen. |
| [SetGeometricTranslation](../../aspose.threed/transform/setgeometrictranslation/)(double, double, double) | Setzt die geometrische Translation. Geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen. |
| [SetPostRotation](../../aspose.threed/transform/setpostrotation/)(double, double, double) | Setzt die Nachrotation, dargestellt in Grad |
| [SetPreRotation](../../aspose.threed/transform/setprerotation/)(double, double, double) | Setzt die Vorrotation, dargestellt in Grad |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| [SetRotation](../../aspose.threed/transform/setrotation/)(double, double, double, double) | Setzt die Rotation (als Quaternion‑Komponenten) der aktuellen Transformation. |
| [SetScale](../../aspose.threed/transform/setscale/)(double, double, double) | Setzt die Skalierung der aktuellen Transformation. |
| [SetTranslation](../../aspose.threed/transform/settranslation/)(double, double, double) | Setzt die Translation der aktuellen Transformation. |

## Beispiele

Der folgende Code zeigt, wie man die Transformation des Knotens ändert:

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//Platziere die Box bei (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### Siehe auch

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


