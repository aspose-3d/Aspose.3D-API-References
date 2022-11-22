---
title: HollowRectangleShape
second_title: Aspose.3D für .NET-API-Referenz
description: IFCkompatible hohle rechteckige Form mit abgerundeten Innen und Außenecken.
type: docs
weight: 1570
url: /de/net/aspose.threed.profiles/hollowrectangleshape/
---
## HollowRectangleShape class

IFC-kompatible hohle rechteckige Form mit abgerundeten Innen- und Außenecken.

```csharp
public class HollowRectangleShape : RectangleShape
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [HollowRectangleShape](hollowrectangleshape)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Ruft ab oder legt fest, ob diese Entität während des Exports ausgeschlossen werden soll. |
| [InnerFilletRadius](../../aspose.threed.profiles/hollowrectangleshape/innerfilletradius) { get; set; } | Der innere Verrundungsradius des inneren Rechtecks. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Ruft den Namen ab oder legt ihn fest. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Ruft den ersten übergeordneten Knoten ab oder legt ihn fest. Wenn der erste übergeordnete Knoten festgelegt wird, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Ruft alle übergeordneten Knoten ab, eine Entität kann an mehrere übergeordnete Knoten angehängt werden, um Geometrie zu instanziieren |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Ruft die Sammlung aller Eigenschaften ab. |
| [RoundingRadius](../../aspose.threed.profiles/rectangleshape/roundingradius) { get; set; } | Ermittelt oder setzt den Radius der Kreisbögen aller vier Ecken, gemessen in Grad. Standardwert ist 0,0 |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Ruft die Szene ab, zu der dieses Objekt gehört |
| [WallThickness](../../aspose.threed.profiles/hollowrectangleshape/wallthickness) { get; set; } | Die Dicke zwischen der Begrenzung des Rechtecks und dem inneren Loch |
| [XDim](../../aspose.threed.profiles/rectangleshape/xdim) { get; set; } | Ermittelt oder setzt die Ausdehnung des Rechtecks in Richtung der x-Achse Der Standardwert ist 2,0 |
| [YDim](../../aspose.threed.profiles/rectangleshape/ydim) { get; set; } | Ermittelt oder setzt die Ausdehnung des Rechtecks in Richtung der y-Achse Der Standardwert ist 2,0 |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Findet die Eigenschaft. Es kann eine dynamische Eigenschaft sein (erstellt von CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Ruft den Begrenzungsrahmen des aktuellen Objekts in seinem Objektraum-Koordinatensystem ab. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey)() | Ruft den Schlüssel des Entity-Renderers ab, der im Renderer registriert ist |
| override [GetExtent](../../aspose.threed.profiles/rectangleshape/getextent)() | Ruft die Ausdehnung in x- und y-Dimension ab. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Holen Sie sich den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Entfernt die angegebene Eigenschaft identifiziert durch name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Legt den Wert der angegebenen Eigenschaft fest |

### Siehe auch

* class [RectangleShape](../rectangleshape)
* namensraum [Aspose.ThreeD.Profiles](../../aspose.threed.profiles)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->