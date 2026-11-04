---
title: "Node.SelectSingleObject"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Node. Selecciona un solo objeto bajo el nodo actual usando la sintaxis de consulta tipo XPath"
type: docs
weight: 240
url: /es/net/aspose.threed/node/selectsingleobject/
---
## Node.SelectSingleObject method

Seleccionar un solo objeto bajo el nodo actual usando sintaxis de consulta similar a XPath.

```csharp
public object SelectSingleObject(string path)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | String | La consulta tipo XPath |

### Valor de retorno

Objeto localizado por la consulta tipo XPath.

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
//Selecciona un solo objeto de cámara bajo los nodos hijos del nodo llamado 'c' bajo el nodo raíz
var c1 = s.RootNode.SelectSingleObject("/c/*/<Camera>");
// Selecciona el nodo llamado 'a1' bajo el nodo raíz, incluso si 'a1' no es un nodo hijo directo del
var obj = s.RootNode.SelectSingleObject("a1");
//Selecciona el propio nodo, ya que '/' se selecciona directamente en el nodo raíz, por lo que se selecciona el nodo raíz.
obj = s.RootNode.SelectSingleObject("/");
```

### Ver también

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


