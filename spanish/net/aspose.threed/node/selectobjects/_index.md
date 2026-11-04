---
title: "Node.SelectObjects"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método del nodo. Selecciona múltiples objetos bajo el nodo actual usando sintaxis de consulta similar a XPath."
type: docs
weight: 230
url: /es/net/aspose.threed/node/selectobjects/
---
## Node.SelectObjects method

Seleccionar múltiples objetos bajo el nodo actual usando sintaxis de consulta similar a XPath.

```csharp
public List<object> SelectObjects(string path)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | String | La consulta tipo XPath |

### Valor de retorno

Múltiples objetos coinciden con la consulta similar a XPath.

### Excepciones

| excepción | condición |
| --- | --- |
| [ParseException](../../../aspose.threed.utilities/parseexception/) | Se lanzará ParseException si la ruta contiene una consulta malformada. |

## Ejemplos

Selecciona un solo nodo usando una expresión tipo XPath

```csharp
//Crea una escena para pruebas
Scene s = new Scene();
var a = s.RootNode.CreateChildNode("a");
a.CreateChildNode("a1");
a.CreateChildNode("a2");
s.RootNode.CreateChildNode("b");
var c = s.RootNode.CreateChildNode("c");
c.CreateChildNode("c1").AddEntity(new Camera("cam"));
c.CreateChildNode("c2").AddEntity(new Light("light"));
//Seleccionar objetos que tengan tipo Cámara o cuyo nombre sea 'light', sin importar dónde estén.
var objects = s.RootNode.SelectObjects("//*[(@Type = 'Camera') or (@Name = 'light')]");
```

### Ver también

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


