---
title: "Klasse RenderState"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Render.RenderState Klasse. Render-Status zum Aufbau der Pipeline. Änderungen am Render-Status wirken sich nicht auf die erstellten Pipeline-Instanzen aus."
type: docs
weight: 2330
url: /de/net/aspose.threed.render/renderstate/
---
## RenderState class

Renderzustand zum Aufbau der Pipeline Die Änderungen am Renderzustand wirken sich nicht auf die erstellten Pipeline-Instanzen aus.

```csharp
public class RenderState : IComparable<RenderState>, IDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RenderState](renderstate/)() | Konstruktor von `RenderState` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Blend](../../aspose.threed.render/renderstate/blend/) { get; set; } | Fragment-Blending aktivieren oder deaktivieren. |
| [BlendColor](../../aspose.threed.render/renderstate/blendcolor/) { get; set; } | Liest oder setzt die Blend-Farbe, wo sie in ConstantColor verwendet wird |
| [CullFace](../../aspose.threed.render/renderstate/cullface/) { get; set; } | Cull-Face aktivieren oder deaktivieren |
| [CullFaceMode](../../aspose.threed.render/renderstate/cullfacemode/) { get; set; } | Liest oder setzt, welche Seite verworfen wird. |
| [DepthFunction](../../aspose.threed.render/renderstate/depthfunction/) { get; set; } | Liest oder setzt die Vergleichsfunktion, die im Tiefentest verwendet wird |
| [DepthMask](../../aspose.threed.render/renderstate/depthmask/) { get; set; } | Aktiviert oder deaktiviert das Schreiben der Tiefe. |
| [DepthTest](../../aspose.threed.render/renderstate/depthtest/) { get; set; } | Aktiviert oder deaktiviert den Tiefentest. |
| [DestinationBlendFactor](../../aspose.threed.render/renderstate/destinationblendfactor/) { get; set; } | Liest oder setzt, wie die Farbe gemischt wird. |
| [FrontFace](../../aspose.threed.render/renderstate/frontface/) { get; set; } | Liest oder setzt, welche Reihenfolge die Vorderseite hat. |
| [PolygonMode](../../aspose.threed.render/renderstate/polygonmode/) { get; set; } | Liest oder setzt den Rendermodus des Polygons. |
| [ScissorTest](../../aspose.threed.render/renderstate/scissortest/) { get; set; } | Aktiviert oder deaktiviert den Scissor-Test. |
| [SourceBlendFactor](../../aspose.threed.render/renderstate/sourceblendfactor/) { get; set; } | Liest oder setzt, wie die Farbe gemischt wird. |
| [StencilBackFace](../../aspose.threed.render/renderstate/stencilbackface/) { get; } | Liest den Stencil-Zustand für die Rückseite. |
| [StencilFrontFace](../../aspose.threed.render/renderstate/stencilfrontface/) { get; } | Liest den Stencil-Zustand für die Vorderseite. |
| [StencilMask](../../aspose.threed.render/renderstate/stencilmask/) { get; set; } | Liest oder setzt die Maske, die bei Abschluss des Tests mit dem Referenz- und dem gespeicherten Stencil-Wert UND-verknüpft wird. |
| [StencilReference](../../aspose.threed.render/renderstate/stencilreference/) { get; set; } | Liest oder setzt den Referenzwert für den Stencil-Test. |
| [StencilTest](../../aspose.threed.render/renderstate/stenciltest/) { get; set; } | Aktiviert oder deaktiviert den Stencil-Test. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompareTo](../../aspose.threed.render/renderstate/compareto/)(RenderState) | Vergleicht den Renderzustand mit einer anderen Instanz |
| [Dispose](../../aspose.threed.render/renderstate/dispose/)() | Entfernt das `RenderState` und gibt alle internen Ressourcen frei. |
| override [Equals](../../aspose.threed.render/renderstate/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Objekt gleich ist. |
| override [GetHashCode](../../aspose.threed.render/renderstate/gethashcode/)() | Gibt den Hashcode für diese Instanz zurück. |

### Siehe auch

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


