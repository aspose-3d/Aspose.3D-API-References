---
title: "Aspose.ThreeD"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Der Basis‑Namensraum von Aspose.3D"
type: docs
weight: 10
url: /de/net/aspose.threed/
---
Der Basis‑Namensraum von Aspose.3D

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [A3DObject](./a3dobject/) | Die Basisklasse aller Aspose.ThreeD-Objekte, alle Unterklassen unterstützen dynamische Eigenschaften. |
| [AssetInfo](./assetinfo/) | Informationen zum Asset. Asset-Informationen können an ein [`Scene`](../aspose.threed/scene/) angehängt werden. Ein untergeordnetes [`Scene`](../aspose.threed/scene/) kann sein eigenes [`AssetInfo`](../aspose.threed/assetinfo/) besitzen, um die Definition des Elternteils zu überschreiben. |
| [AxisSystem](./axissystem/) | Das Achsensystem ist eine Kombination aus Koordinatensystem, Aufwärtsvektor und Frontvektor. |
| [BonePose](./bonepose/) | Das [`BonePose`](../aspose.threed/bonepose/) enthält die Transformationsmatrix für einen Knochenknoten |
| [CustomObject](./customobject/) | Metadaten oder benutzerdefinierte Objekte, die in 3D-Dateien verwendet werden, werden von dieser Klasse verwaltet. Alle benutzerdefinierten Eigenschaften werden als dynamische Eigenschaften gespeichert. |
| [Entity](./entity/) | Die Basisklasse aller Entitäten. Eine Entität stellt ein konkretes Objekt dar, das unter einem Knoten wie [`Light`](../aspose.threed.entities/light/)/[`Geometry`](../aspose.threed.entities/geometry/) angehängt ist. |
| [ExportException](./exportexception/) | Ausnahmen, wenn Aspose.3D die Szene nicht in eine Datei exportieren konnte |
| [FileFormat](./fileformat/) | Dateiformatdefinition |
| [FileFormatType](./fileformattype/) | Dateiformattyp |
| [GlobalTransform](./globaltransform/) | Globale Transformation ist ähnlich wie [`Transform`](../aspose.threed/transform/), ist jedoch unveränderlich, da sie die endgültig ausgewertete Transformation darstellt. Ein rechtshändiges Koordinatensystem wird bei der Auswertung der globalen Transformation verwendet. |
| [Group](./group/) | Eine [`Group`](../aspose.threed/group/) stellt die logischen Beziehungen von [`Node`](../aspose.threed/node/) dar. |
| [ImageRenderOptions](./imagerenderoptions/) | Optionen für [`Render`](../aspose.threed/scene/render/) und [`Render`](../aspose.threed/scene/render/) |
| [ImportException](./importexception/) | Ausnahme, wenn Aspose.3D die angegebene Quelle nicht öffnen konnte |
| [License](./license/) | Stellt Methoden bereit, um die Komponente zu lizenzieren. |
| [Metered](./metered/) | Stellt Methoden bereit, um den gemessenen Schlüssel zu setzen. |
| [Node](./node/) | Stellt ein Element im Szenengraphen dar. Ein Szenengraph ist ein Baum von Node-Objekten. Die Baumverwaltungsdienste sind in dieser Klasse enthalten. Hinweis: Das Aspose.3D SDK prüft nicht die Gültigkeit des konstruierten Szenengraphen. Es liegt in der Verantwortung des Aufrufers sicherzustellen, dass keine zyklischen Graphen in einer Node-Hierarchie erzeugt werden. Neben der Baumverwaltung definiert diese Klasse alle Eigenschaften, die erforderlich sind, um die Position des Objekts in der Szene zu beschreiben. Diese Informationen umfassen die grundlegenden Eigenschaften Translation, Rotation und Skalierung sowie erweiterte Optionen für Drehpunkte, Grenzen und IK-Gelenkattribute wie Steifigkeit und Dämpfung. Beim ersten Erstellen ist das Node-Objekt „leer“ (d. h.: es ist ein Objekt ohne grafische Darstellung, das nur Positionsinformationen enthält). In diesem Zustand kann es verwendet werden, um Eltern im Node-Baum darzustellen, aber nicht viel mehr. Die übliche Verwendung dieser Objekttypen besteht darin, ihnen eine Entität hinzuzufügen, die den Node spezialisieren wird (siehe „Entity“). Die Entität ist ein eigenständiges Objekt und ist mit dem Node verbunden. Das bedeutet auch, dass dieselbe Entität zwischen mehreren Nodes geteilt werden kann. Kamera, Licht, Mesh usw. sind alle Entitäten und sie leiten sich alle von der Basisklasse Entity ab. |
| [NodeVisitor](./nodevisitor/) | Ein Callback, um die gesamte Node-Hierarchie zu durchlaufen. |
| [Pose](./pose/) | Die Pose wird verwendet, um die Transformationsmatrix zu speichern, wenn die Geometrie geskinnt ist. Die Pose ist ein Satz von [`BonePose`](../aspose.threed/bonepose/); jedes [`BonePose`](../aspose.threed/bonepose/) speichert die konkreten Transformationsinformationen des Knochen-Nodes. |
| [Property](./property/) | Klasse zum Halten benutzerdefinierter Eigenschaften. |
| [PropertyCollection](./propertycollection/) | Die Sammlung von Eigenschaften |
| [Scene](./scene/) | Eine Szene ist ein Top‑Level‑Objekt, das die Nodes, Geometrien, Materialien, Texturen, Animationen, Posen, Unterszenen usw. enthält. Eine Szene kann Unterszenen haben und dient als Mehrdokumenten‑Unterstützung in Dateien wie collada/blender/fbx. Auf die Node-Hierarchie kann über [`RootNode`](../aspose.threed/scene/rootnode/) zugegriffen werden. [`Library`](../aspose.threed/scene/library/) wird verwendet, um während der Serialisierung einen Verweis auf nicht angehängte Objekte (wie Metadaten oder benutzerdefinierte Objekte) zu behalten, sodass es als Bibliothek genutzt werden kann. |
| [SceneObject](./sceneobject/) | Die Basisklasse der Objekte, die innerhalb einer Szene gespeichert werden. |
| [Transform](./transform/) | Eine Transform enthält Informationen, die den Zugriff auf die Übersetzung/Skalierung/Rotation des Objekts oder die Transformationsmatrix mit minimalem Aufwand ermöglichen. Dies wird von der lokalen Transform verwendet. |
| [TrialException](./trialexception/) | Dies wird in Scene.Open/Scene.Save ausgelöst, wenn keine Lizenzen angewendet wurden. Sie können diese Ausnahme deaktivieren, indem Sie SuppressTrialException auf true setzen. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [INamedObject](./inamedobject/) | Objekt, das einen Namen hat |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [Axis](./axis/) | Die Koordinatenachse. |
| [CoordinateSystem](./coordinatesystem/) | Das linkshändige oder rechtshändige Koordinatensystem. |
| [FileContentType](./filecontenttype/) | Datei‑Inhaltstyp |
| [PoseType](./posetype/) | Posentyp. |
| [PropertyFlags](./propertyflags/) | Eigenschafts‑Flags |


