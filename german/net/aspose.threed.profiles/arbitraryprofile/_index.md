---
title: ArbitraryProfile
second_title: Aspose.3D für .NET-API-Referenz
description: Mit dieser Klasse können Sie ein 2DProfil direkt aus einer beliebigen Kurve konstruieren.
type: docs
weight: 1510
url: /de/net/aspose.threed.profiles/arbitraryprofile/
---
## ArbitraryProfile class

Mit dieser Klasse können Sie ein 2D-Profil direkt aus einer beliebigen Kurve konstruieren.

```csharp
public class ArbitraryProfile : Profile
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ArbitraryProfile](arbitraryprofile#constructor)() | Konstrukteur von[`ArbitraryProfile`](../arbitraryprofile) |
| [ArbitraryProfile](arbitraryprofile#constructor_1)(Curve) | Konstrukteur von[`ArbitraryProfile`](../arbitraryprofile) mit Anfangskurve. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Curve](../../aspose.threed.profiles/arbitraryprofile/curve) { get; set; } | Die zum Erstellen des Profils verwendete Kurve |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Ruft ab oder legt fest, ob diese Entität während des Exports ausgeschlossen werden soll. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Ruft den Namen ab oder legt ihn fest. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Ruft den ersten übergeordneten Knoten ab oder legt ihn fest. Wenn der erste übergeordnete Knoten festgelegt wird, wird diese Entität von anderen übergeordneten Knoten getrennt. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Ruft alle übergeordneten Knoten ab, eine Entität kann an mehrere übergeordnete Knoten angehängt werden, um Geometrie zu instanziieren |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Ruft die Sammlung aller Eigenschaften ab. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Ruft die Szene ab, zu der dieses Objekt gehört |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Findet die Eigenschaft. Es kann eine dynamische Eigenschaft sein (erstellt von CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert durch ihren Namen) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Ruft den Begrenzungsrahmen des aktuellen Objekts in seinem Objektraum-Koordinatensystem ab. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey)() | Ruft den Schlüssel des Entity-Renderers ab, der im Renderer registriert ist |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Holen Sie sich den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Entfernt die angegebene Eigenschaft identifiziert durch name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Legt den Wert der angegebenen Eigenschaft fest |

### Siehe auch

* class [Profile](../profile)
* namensraum [Aspose.ThreeD.Profiles](../../aspose.threed.profiles)
* Montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
