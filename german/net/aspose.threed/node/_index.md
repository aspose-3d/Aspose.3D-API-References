---
title: "Klasse Node"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Node-Klasse. Stellt ein Element im Szenengraphen dar. Ein Szenengraph ist ein Baum von Node-Objekten. Die Baumverwaltungsdienste sind in dieser Klasse enthalten. Hinweis: Das Aspose.3D SDK prüft nicht die Gültigkeit des konstruierten Szenengraphen. Es liegt in der Verantwortung des Aufrufers sicherzustellen, dass keine zyklischen Graphen in einer Node-Hierarchie erzeugt werden. Neben der Baumverwaltung definiert diese Klasse alle Eigenschaften, die zur Beschreibung der Position des Objekts in der Szene erforderlich sind. Diese Informationen umfassen die grundlegenden Eigenschaften Translation, Rotation und Skalierung sowie erweiterte Optionen für Drehpunkte, Grenzen und IK-Gelenkattribute wie Steifigkeit und Dämpfung. Beim ersten Erstellen ist das Node-Objekt leer, d. h. es ist ein Objekt ohne grafische Darstellung, das nur Positionsinformationen enthält. In diesem Zustand kann es verwendet werden, um Eltern im Node-Baum zu repräsentieren, aber nicht viel mehr. Die übliche Verwendung dieser Objekttypen besteht darin, ihnen eine Entität hinzuzufügen, die den Node spezialisieren wird, siehe die Entity. Die Entity ist ein eigenständiges Objekt und ist mit dem Node verbunden. Das bedeutet auch, dass dieselbe Entity unter mehreren Nodes geteilt werden kann. Kamera, Licht, Mesh usw. sind alles Entitäten und sie alle leiten sich von der Basisklasse Entity ab."
type: docs
weight: 1630
url: /de/net/aspose.threed/node/
---
## Node class

Stellt ein Element im Szenengraphen dar. Ein Szenengraph ist ein Baum von Node-Objekten. Die Baumverwaltungsdienste sind in dieser Klasse enthalten. Hinweis: Das Aspose.3D SDK prüft nicht die Gültigkeit des konstruierten Szenengraphen. Es liegt in der Verantwortung des Aufrufers sicherzustellen, dass keine zyklischen Graphen in einer Node-Hierarchie erzeugt werden. Neben der Baumverwaltung definiert diese Klasse alle Eigenschaften, die erforderlich sind, um die Position des Objekts in der Szene zu beschreiben. Diese Informationen umfassen die grundlegenden Eigenschaften Translation, Rotation und Skalierung sowie erweiterte Optionen für Drehpunkte, Grenzen und IK-Gelenkattribute wie Steifigkeit und Dämpfung. Beim ersten Erstellen ist das Node-Objekt „leer“ (d. h.: es ist ein Objekt ohne grafische Darstellung, das nur Positionsinformationen enthält). In diesem Zustand kann es verwendet werden, um Eltern im Node-Baum darzustellen, aber nicht viel mehr. Die übliche Verwendung dieser Objekttypen besteht darin, ihnen eine Entität hinzuzufügen, die den Node spezialisieren wird (siehe „Entity“). Die Entität ist ein eigenständiges Objekt und ist mit dem Node verbunden. Das bedeutet auch, dass dieselbe Entität zwischen mehreren Nodes geteilt werden kann. Kamera, Licht, Mesh usw. sind alle Entitäten und sie leiten sich alle von der Basisklasse Entity ab.

```csharp
public class Node : SceneObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Node](node/#constructor)() | Initialisiert eine neue Instanz der `Node`-Klasse. |
| [Node](node/#constructor_1)(string) | Initialisiert eine neue Instanz der `Node`-Klasse. |
| [Node](node/#constructor_2)(string, Entity) | Initialisiert eine neue Instanz der `Node`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AssetInfo](../../aspose.threed/node/assetinfo/) { get; set; } | Asset-Informationen pro Node |
| [ChildNodes](../../aspose.threed/node/childnodes/) { get; } | Liefert die untergeordneten Nodes. |
| [Entities](../../aspose.threed/node/entities/) { get; } | Liefert alle Node-Entitäten. |
| [Entity](../../aspose.threed/node/entity/) { get; set; } | Liefert oder setzt die erste an diesen Node angehängte Entität; beim Setzen werden andere Entitäten gelöscht. |
| [Excluded](../../aspose.threed/node/excluded/) { get; set; } | Liefert oder setzt, ob dieser Node und alle untergeordneten Nodes/Entitäten beim Export ausgeschlossen werden sollen. |
| [GlobalTransform](../../aspose.threed/node/globaltransform/) { get; } | Liefert die globale Transformation. |
| [Material](../../aspose.threed/node/material/) { get; set; } | Liefert oder setzt das erste Material, das diesem Node zugeordnet ist; beim Setzen werden andere Materialien gelöscht. |
| [Materials](../../aspose.threed/node/materials/) { get; } | Liefert die mit diesem Node verbundenen Materialien. |
| [MetaDatas](../../aspose.threed/node/metadatas/) { get; } | Liefert die in diesem Node definierten Metadaten. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [ParentNode](../../aspose.threed/node/parentnode/) { get; set; } | Liefert oder setzt den übergeordneten Node. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Liest die Szene, zu der dieses Objekt gehört. |
| [Transform](../../aspose.threed/node/transform/) { get; } | Liefert die lokale Transformation. |
| [Visible](../../aspose.threed/node/visible/) { get; set; } | Liefert oder setzt die Sichtbarkeit des Nodes. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Accept](../../aspose.threed/node/accept/)(NodeVisitor) | Durchläuft alle Nachfolger-Nodes (einschließlich des aktuellen Nodes) und ruft den Besucher mit dem Node auf. Der Besucher kann den Durchlauf abbrechen, indem er false zurückgibt. |
| [AddChildNode](../../aspose.threed/node/addchildnode/)(Node) | Fügt diesem Node einen untergeordneten Node hinzu. |
| [AddEntity](../../aspose.threed/node/addentity/)(Entity) | Fügt dem Node eine Entität hinzu. |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode)() | Erstellt einen untergeordneten Node. |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_1)(Entity) | Erstellt einen neuen untergeordneten Node mit angehängter Entität. |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_2)(string) | Erstellt einen neuen untergeordneten Node mit dem angegebenen Node-Namen. |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_3)(string, Entity) | Erstellt einen neuen untergeordneten Node mit dem angegebenen Node-Namen. |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_4)(string, Entity, Material) | Erstellt einen neuen untergeordneten Node mit dem angegebenen Node-Namen und fügt die angegebene Entität sowie ein Material hinzu. |
| [EvaluateGlobalTransform](../../aspose.threed/node/evaluateglobaltransform/)(bool) | Bewertet die globale Transformation, wobei die geometrische Transformation einbezogen wird oder nicht. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetBoundingBox](../../aspose.threed/node/getboundingbox/)() | Berechnet die Begrenzungsbox des Nodes. |
| [GetChild](../../aspose.threed/node/getchild/#getchild)(int) | Liefert den untergeordneten Node am angegebenen Index. |
| [GetChild](../../aspose.threed/node/getchild/#getchild_1)(string) | Liefert den untergeordneten Node mit dem angegebenen Namen. |
| [GetEntity&lt;T&gt;](../../aspose.threed/node/getentity/)() |  |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [Merge](../../aspose.threed/node/merge/)(Node) | Lösen Sie alles unter dem Knoten und hängen Sie es an den aktuellen Knoten an. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SelectObjects](../../aspose.threed/node/selectobjects/)(string) | Wählen Sie mehrere Objekte unter dem aktuellen Knoten mit einer XPath-ähnlichen Abfragesyntax aus. |
| [SelectSingleObject](../../aspose.threed/node/selectsingleobject/)(string) | Wählen Sie ein einzelnes Objekt unter dem aktuellen Knoten mit einer XPath-ähnlichen Abfragesyntax aus. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| override [ToString](../../aspose.threed/node/tostring/)() | Gibt die Zeichenkettenrepräsentation dieses Knotens zurück. |

### Siehe auch

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


