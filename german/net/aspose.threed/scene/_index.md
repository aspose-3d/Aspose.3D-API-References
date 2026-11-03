---
title: "Klasse Scene"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Scene Klasse. Eine Szene ist ein Top‑Level‑Objekt, das die Knoten, Geometrien, Materialien, Texturen, Animationen, Posen, Unterszenen usw. enthält. Eine Szene kann Unterszenen haben und dient als Mehrdokumenten‑Unterstützung in Dateien wie collada/blender/fbx. Auf die Knotenhierarchie kann über RootNode zugegriffen werden; Library wird verwendet, um einen Verweis auf nicht angehängte Objekte während der Serialisierung (wie Metadaten oder benutzerdefinierte Objekte) zu behalten, sodass sie als Bibliothek genutzt werden kann."
type: docs
weight: 2500
url: /de/net/aspose.threed/scene/
---
## Scene class

Eine Szene ist ein Top‑Level‑Objekt, das die Knoten, Geometrien, Materialien, Texturen, Animationen, Posen, Unterszenen usw. enthält. Eine Szene kann Unterszenen haben und dient als Mehrdokumenten‑Unterstützung in Dateien wie collada/blender/fbx. Auf die Knotenhierarchie kann über [`RootNode`](./rootnode/)[`Library`](./library/) zugegriffen werden; sie wird verwendet, um einen Verweis auf nicht angehängte Objekte während der Serialisierung (wie Metadaten oder benutzerdefinierte Objekte) zu behalten, sodass sie als Bibliothek genutzt werden kann.

```csharp
public class Scene : SceneObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Scene](scene/#constructor)() | Initialisiert eine neue Instanz der `Scene` Klasse. |
| [Scene](scene/#constructor_1)(Entity) | Initialisiert eine neue Instanz der `Scene` Klasse mit einer Entität, die an einen neuen Knoten angehängt ist. |
| [Scene](scene/#constructor_2)(Scene, string) | Initialisiert eine neue Instanz der `Scene` Klasse als Unterszene. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AnimationClips](../../aspose.threed/scene/animationclips/) { get; } | Gibt alle in der Szene definierten [`AnimationClip`](../../aspose.threed.animation/animationclip/) zurück. |
| [AssetInfo](../../aspose.threed/scene/assetinfo/) { get; set; } | Liest oder setzt die Top‑Level‑Asset-Informationen. |
| [CurrentAnimationClip](../../aspose.threed/scene/currentanimationclip/) { get; set; } | Liest oder setzt das aktive [`AnimationClip`](../../aspose.threed.animation/animationclip/). |
| [Library](../../aspose.threed/scene/library/) { get; } | Objekte, die nicht direkt in der Szenenhierarchie verwendet werden, können in der Library definiert werden. Dies ist nützlich, wenn Sie Unterszenen verwenden und wiederverwendbare Komponenten unter Unterszenen ablegen. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Poses](../../aspose.threed/scene/poses/) { get; } | Gibt alle in dieser Szene verwendeten [`Pose`](../pose/) zurück. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [RootNode](../../aspose.threed/scene/rootnode/) { get; } | Gibt den Root‑Knoten der Szene zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [SubScenes](../../aspose.threed/scene/subscenes/) { get; } | Gibt alle Unterszenen zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile)(string) | Öffnet die Szene vom angegebenen Pfad. |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_3)(string, CancellationToken) | Öffnet die Szene vom angegebenen Pfad. |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_1)(string, FileFormat, CancellationToken) | Öffnet die Szene vom angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_2)(string, LoadOptions, CancellationToken) | Öffnet die Szene vom angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_2)(Stream, CancellationToken) | Öffnet die Szene aus dem angegebenen Stream. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream)(Stream, FileFormat, CancellationToken) | Öffnet die Szene aus dem angegebenen Stream unter Verwendung des angegebenen Dateiformats. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_1)(Stream, LoadOptions, CancellationToken) | Öffnet die Szene aus dem angegebenen Stream unter Verwendung der angegebenen IO-Konfiguration. |
| [Clear](../../aspose.threed/scene/clear/)() | Löscht den Szeneninhalt und stellt die Standardeinstellungen wieder her. |
| [CreateAnimationClip](../../aspose.threed/scene/createanimationclip/)(string) | Eine Kurzschreibweise, um das [`AnimationClip`](../../aspose.threed.animation/animationclip/) zu erstellen und zu registrieren. Das erste [`AnimationClip`](../../aspose.threed.animation/animationclip/) wird dem [`CurrentAnimationClip`](./currentanimationclip/) zugewiesen. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetAnimationClip](../../aspose.threed/scene/getanimationclip/)(string) | Liefert ein benanntes [`AnimationClip`](../../aspose.threed.animation/animationclip/) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [Open](../../aspose.threed/scene/open/#open)(Stream) | Öffnet die Szene aus dem angegebenen Stream. |
| [Open](../../aspose.threed/scene/open/#open_4)(string) | Öffnet die Szene vom angegebenen Pfad. |
| [Open](../../aspose.threed/scene/open/#open_3)(Stream, CancellationToken) | Öffnet die Szene aus dem angegebenen Stream. |
| [Open](../../aspose.threed/scene/open/#open_8)(string, CancellationToken) | Öffnet die Szene vom angegebenen Pfad. |
| [Open](../../aspose.threed/scene/open/#open_6)(string, LoadOptions) | Öffnet die Szene vom angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |
| [Open](../../aspose.threed/scene/open/#open_1)(Stream, FileFormat, CancellationToken) | Öffnet die Szene aus dem angegebenen Stream unter Verwendung des angegebenen Dateiformats. |
| [Open](../../aspose.threed/scene/open/#open_2)(Stream, LoadOptions, CancellationToken) | Öffnet die Szene aus dem angegebenen Stream unter Verwendung der angegebenen IO-Konfiguration. |
| [Open](../../aspose.threed/scene/open/#open_5)(string, FileFormat, CancellationToken) | Öffnet die Szene vom angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |
| [Open](../../aspose.threed/scene/open/#open_7)(string, LoadOptions, CancellationToken) | Öffnet die Szene vom angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [Render](../../aspose.threed/scene/render/#render_2)(Camera, string) | Rendert die Szene aus der Sicht der angegebenen Kamera in eine externe Datei. Die Standardausgabegröße beträgt 1024x768 und das Ausgabeformat ist png. |
| [Render](../../aspose.threed/scene/render/#render)(Camera, TextureData) | Rendert die Szene aus der Sicht der angegebenen Kamera in ein Bitmap. |
| [Render](../../aspose.threed/scene/render/#render_1)(Camera, TextureData, ImageRenderOptions) | Rendert die Szene aus der Sicht der angegebenen Kamera in ein Bitmap. |
| [Render](../../aspose.threed/scene/render/#render_3)(Camera, string, Vector2, string) | Rendert die Szene aus der Sicht der angegebenen Kamera in eine externe Datei. |
| [Render](../../aspose.threed/scene/render/#render_4)(Camera, string, Vector2, string, ImageRenderOptions) | Rendert die Szene aus der Sicht der angegebenen Kamera in eine externe Datei. |
| [Save](../../aspose.threed/scene/save/#save_4)(string) | Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |
| [Save](../../aspose.threed/scene/save/#save)(Stream, FileFormat) | Speichert die Szene in einen Stream unter Verwendung des angegebenen Dateiformats. |
| [Save](../../aspose.threed/scene/save/#save_2)(Stream, SaveOptions) | Speichert die Szene in einen Stream unter Verwendung des angegebenen Dateiformats. |
| [Save](../../aspose.threed/scene/save/#save_5)(string, FileFormat) | Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |
| [Save](../../aspose.threed/scene/save/#save_7)(string, SaveOptions) | Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |
| [Save](../../aspose.threed/scene/save/#save_1)(Stream, FileFormat, CancellationToken) | Speichert die Szene in einen Stream unter Verwendung des angegebenen Dateiformats. |
| [Save](../../aspose.threed/scene/save/#save_3)(Stream, SaveOptions, CancellationToken) | Speichert die Szene in einen Stream unter Verwendung des angegebenen Dateiformats. |
| [Save](../../aspose.threed/scene/save/#save_6)(string, FileFormat, CancellationToken) | Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |
| [Save](../../aspose.threed/scene/save/#save_8)(string, SaveOptions, CancellationToken) | Speichert die Szene am angegebenen Pfad unter Verwendung des angegebenen Dateiformats. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [Version](../../aspose.threed/scene/version/) | Liefert die aktuelle Versionsnummer |

### Siehe auch

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


