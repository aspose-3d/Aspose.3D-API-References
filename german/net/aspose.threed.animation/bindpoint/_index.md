---
title: "Klasse BindPoint"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Animation.BindPoint Klasse. Ein BindPoint wird normalerweise auf einer Property eines Objekts erstellt; einige Property-Typen enthalten mehrere Komponentenfelder, wie ein Vector3-Feld. BindPoint erzeugt für jedes Komponentenfeld einen Kanal und verbindet das Feld über die Kanäle mit einer oder mehreren Schlüsselbildsequenz-Instanzen."
type: docs
weight: 50
url: /de/net/aspose.threed.animation/bindpoint/
---
## BindPoint class

Ein `BindPoint` wird normalerweise auf einer Property eines Objekts erstellt, einige Property-Typen enthalten mehrere Komponentenfelder (wie ein Vector3-Feld), `BindPoint` erzeugt für jedes Komponentenfeld einen Kanal und verbindet das Feld über die Kanäle mit einer oder mehreren Schlüsselbildsequenz-Instanz(en).

```csharp
public class BindPoint : A3DObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BindPoint](bindpoint/)(Scene, Property) | Initialisiert eine neue Instanz der `BindPoint` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ChannelsCount](../../aspose.threed.animation/bindpoint/channelscount/) { get; } | Ermittelt die Gesamtzahl der Property-Kanäle, die in dieser Animationskurvenzuordnung definiert sind. |
| [Item](../../aspose.threed.animation/bindpoint/item/) { get; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Property](../../aspose.threed.animation/bindpoint/property/) { get; } | Ermittelt die mit dem CurveMapping verbundene Property. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel)(string, object) | Fügt die angegebene Kanal-Property hinzu. |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_1)(string, Type, object) | Fügt die angegebene Kanal-Property hinzu. |
| [AddChannel&lt;T&gt;](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_2)(string, T) |  |
| [BindKeyframeSequence](../../aspose.threed.animation/bindpoint/bindkeyframesequence/)(string, KeyframeSequence) | Bindet die Schlüsselbildsequenz an den angegebenen Kanal. |
| [CreateKeyframeSequence](../../aspose.threed.animation/bindpoint/createkeyframesequence/)(string) | Erstellt eine neue Kurve und verbindet sie mit dem ersten Kanal der Kurvenzuordnung. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetChannel](../../aspose.threed.animation/bindpoint/getchannel/)(string) | Ermittelt den Kanal nach dem angegebenen Namen. |
| [GetKeyframeSequence](../../aspose.threed.animation/bindpoint/getkeyframesequence/)(string) | Ruft die erste Keyframe‑Sequenz im angegebenen Kanal ab |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [ResetChannels](../../aspose.threed.animation/bindpoint/resetchannels/)() | Leert die Eigenschaftskanäle dieser Animationskurvenzuordnung. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| override [ToString](../../aspose.threed.animation/bindpoint/tostring/)() | Formatiert das Objekt zu einer Zeichenkette. |

### Siehe auch

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


