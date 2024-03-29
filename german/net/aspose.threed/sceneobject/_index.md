---
title: SceneObject
second_title: Aspose.3D für .NET-API-Referenz
description: Die Stammklasse von Objekten die in einer Szene gespeichert werden.
type: docs
weight: 2260
url: /de/net/aspose.threed/sceneobject/
---
## SceneObject class

Die Stammklasse von Objekten, die in einer Szene gespeichert werden.

```csharp
public abstract class SceneObject : A3DObject
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SceneObject](sceneobject#constructor)() | Initialisiert ein SceneObject. |
| [SceneObject](sceneobject#constructor_1)(string) | Initialisiert ein Szenenobjekt mit einem Standardnamen |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Ruft den Namen ab oder legt ihn fest. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Ruft die Sammlung aller Eigenschaften ab. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Ruft die Szene ab, zu der dieses Objekt gehört |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Findet die Eigenschaft. Es kann eine dynamische Eigenschaft sein (erstellt von CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Holen Sie sich den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Entfernt die angegebene Eigenschaft identifiziert durch name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Legt den Wert der angegebenen Eigenschaft fest |

### Siehe auch

* class [A3DObject](../a3dobject)
* namensraum [Aspose.ThreeD](../../aspose.threed)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
