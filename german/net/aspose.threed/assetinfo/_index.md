---
title: "Klasse AssetInfo"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.AssetInfo Klasse. Informationen zum Asset. Asset-Informationen können an einer Scene angehängt werden. Eine untergeordnete Scene kann ihr eigenes AssetInfo haben, um die Definition des Elternteils zu überschreiben."
type: docs
weight: 130
url: /de/net/aspose.threed/assetinfo/
---
## AssetInfo class

Information zum Asset. Asset-Informationen können an einer [`Scene`](../scene/) angehängt werden. Eine untergeordnete [`Scene`](../scene/) kann ihr eigenes `AssetInfo` haben, um die Definition des Elternteils zu überschreiben.

```csharp
public class AssetInfo : A3DObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [AssetInfo](assetinfo/#constructor)() | Initialisiert eine neue Instanz der `AssetInfo` Klasse. |
| [AssetInfo](assetinfo/#constructor_1)(string) | Initialisiert eine neue Instanz der `AssetInfo` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Ambient](../../aspose.threed/assetinfo/ambient/) { get; set; } | Liest oder setzt die Standard-Ambientfarbe dieses Assets |
| [ApplicationName](../../aspose.threed/assetinfo/applicationname/) { get; set; } | Liest oder setzt die Anwendung, die dieses Asset erstellt hat |
| [ApplicationVendor](../../aspose.threed/assetinfo/applicationvendor/) { get; set; } | Liest oder setzt den Namen des Anwendungsanbieters |
| [ApplicationVersion](../../aspose.threed/assetinfo/applicationversion/) { get; set; } | Liest oder setzt die Version der Anwendung, die dieses Asset erstellt hat. |
| [Author](../../aspose.threed/assetinfo/author/) { get; set; } | Liest oder setzt den Autor dieses Assets |
| [AxisSystem](../../aspose.threed/assetinfo/axissystem/) { get; set; } | Liest oder setzt das Koordinatensystem/Up-Vektor/Front-Vektor der Asset-Informationen. |
| [Comment](../../aspose.threed/assetinfo/comment/) { get; set; } | Liest oder setzt den Kommentar dieses Assets. |
| [CoordinateSystem](../../aspose.threed/assetinfo/coordinatesystem/) { get; set; } | Liest oder setzt das in diesem Asset verwendete Koordinatensystem. |
| [Copyright](../../aspose.threed/assetinfo/copyright/) { get; set; } | Liest oder setzt das Urheberrecht des Dokuments |
| [CreationTime](../../aspose.threed/assetinfo/creationtime/) { get; set; } | Liest oder setzt die Erstellungszeit dieses Assets |
| [FrontVector](../../aspose.threed/assetinfo/frontvector/) { get; set; } | Liest oder setzt den Front-Vektor, der in diesem Asset verwendet wird. |
| [Keywords](../../aspose.threed/assetinfo/keywords/) { get; set; } | Liest oder setzt die Schlüsselwörter dieses Assets |
| [ModificationTime](../../aspose.threed/assetinfo/modificationtime/) { get; set; } | Liest oder setzt die Änderungszeit dieses Assets |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Revision](../../aspose.threed/assetinfo/revision/) { get; set; } | Liest oder setzt die Revisionsnummer dieses Assets, normalerweise in Versionskontrollsystemen verwendet. |
| [Subject](../../aspose.threed/assetinfo/subject/) { get; set; } | Liest oder setzt das Thema dieses Assets |
| [Title](../../aspose.threed/assetinfo/title/) { get; set; } | Liest oder setzt den Titel dieses Assets |
| [UnitName](../../aspose.threed/assetinfo/unitname/) { get; set; } | Liest oder setzt die Längeneinheit, die in diesem Asset verwendet wird. z. B. cm/m/km/Zoll/Fuß |
| [UnitScaleFactor](../../aspose.threed/assetinfo/unitscalefactor/) { get; set; } | Liest oder setzt den Skalierungsfaktor zum realen Meter. |
| [UpVector](../../aspose.threed/assetinfo/upvector/) { get; set; } | Liest oder setzt den Aufwärtsvektor, der in diesem Asset verwendet wird. |
| [Url](../../aspose.threed/assetinfo/url/) { get; set; } | Liest oder setzt die URL dieses Assets. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

## Beispiele

Der folgende Code zeigt, wie man Asset-Informationen aus einer fbx-Datei liest:

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The file is created at {scene.AssetInfo.CreationTime} by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion} ");
```

### Siehe auch

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


