---
title: "Enum MappingMode"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Entities.MappingMode enum. Bestimmt, wie das Element auf eine Oberfläche abgebildet wird. Der MappingMode definiert, wie VertexElement auf die Oberfläche der Geometrie abgebildet wird"
type: docs
weight: 500
url: /de/net/aspose.threed.entities/mappingmode/
---
## MappingMode enumeration

Bestimmt, wie das Element auf eine Oberfläche abgebildet wird. Der `MappingMode` definiert, wie [`VertexElement`](../vertexelement/) auf die Oberfläche der Geometrie abgebildet wird.

```csharp
public enum MappingMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| ControlPoint | `0` | Jeder Datensatz wird dem Kontrollpunkt der Geometrie zugeordnet. |
| PolygonVertex | `1` | Die Daten werden dem Scheitelpunkt des Polygons zugeordnet. Wenn ein Kontrollpunkt von mehreren Polygonen gemeinsam genutzt wird und die Daten als PolygonVertex zugeordnet werden, hat der Kontrollpunkt als unterschiedlicher Polygon‑Scheitelpunkt eigene Daten. |
| Polygon | `2` | Die Daten werden dem Polygon zugeordnet. Jeder Polygon‑Scheitelpunkt teilt dieselben Daten, wenn der Abbildungsmodus Polygon ist. |
| Edge | `3` | Die Daten werden der Kante zugeordnet. Jeder Endpunkt der Kante teilt dieselben Daten, wenn die Abbildung Edge ist. |
| AllSame | `4` | Ein Datensatz wird der gesamten Oberfläche zugeordnet. Unabhängig davon, ob die Daten als Kontrollpunkt/Polygon‑Scheitelpunkt/Kantenendpunkte interpretiert werden, sind die Daten stets dieselben, wie sie durch AllSame definiert sind. |

### Siehe auch

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


