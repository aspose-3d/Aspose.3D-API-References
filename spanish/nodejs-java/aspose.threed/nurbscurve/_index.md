---
title: "NurbsCurve"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

Una curva NURBS es una curva representada por NURBS (Non-uniform rational basis spline). Una curva NURBS se define por su Order, un conjunto de Geometry.ControlPoints ponderados y un KnotVectors. El componente w en el punto de control se usa como peso del punto de control, sea que sea CurveDimension.TWO_DIMENSIONAL o CurveDimension.THREE_DIMENSIONAL.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de la clase NurbsCurve. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(name) | Inicializa una nueva instancia de la clase NurbsCurve. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Nombre | Descripción |
| --- | --- |
| getControlPoints() | Obtiene todos los puntos de control |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| Nombre | Descripción |
| --- | --- |
| getMultiplicity() | Obtiene la multiplicidad. La multiplicidad. |

 **Result:**



---


### getOrder{#getOrder}

| Nombre | Descripción |
| --- | --- |
| getOrder() | Obtiene o establece el orden de una curva NURBS, define el número de puntos de control cercanos que influyen en cualquier punto dado de la curva. El orden. |

 **Result:**



---


### setOrder{#setOrder}

| Nombre | Descripción |
| --- | --- |
| setOrder(value) | Obtiene o establece el orden de una curva NURBS, define el número de puntos de control cercanos que influyen en cualquier punto dado de la curva. El orden. |

 **Result:**



---


### getDimension{#getDimension}

| Nombre | Descripción |
| --- | --- |
| getDimension() | Obtiene o establece la dimensión de la curva. El valor de la propiedad es una constante entera CurveDimension. Para una curva CurveDimension.TWO_DIMENSIONAL, el componente z en el punto de control no se usa. |

 **Result:**



---


### setDimension{#setDimension}

| Nombre | Descripción |
| --- | --- |
| setDimension(value) | Obtiene o establece la dimensión de la curva. El valor de la propiedad es una constante entera CurveDimension. Para una curva CurveDimension.TWO_DIMENSIONAL, el componente z en el punto de control no se usa. |

 **Result:**



---


### getCurveType{#getCurveType}

| Nombre | Descripción |
| --- | --- |
| getCurveType() | Obtiene o establece el tipo de la curva. El valor de la propiedad es la constante entera NurbsType. El tipo de la curva. |

 **Result:**



---


### setCurveType{#setCurveType}

| Nombre | Descripción |
| --- | --- |
| setCurveType(value) | Obtiene o establece el tipo de la curva. El valor de la propiedad es la constante entera NurbsType. El tipo de la curva. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Nombre | Descripción |
| --- | --- |
| getKnotVectors() | Obtiene el vector de nudos, es una secuencia de valores de parámetro que determina dónde y cómo los puntos de control afectan la curva NURBS. |

 **Result:**



---


### getRational{#getRational}

| Nombre | Descripción |
| --- | --- |
| getRational() | Obtiene o establece si es racional, este valor indica si este NurbsCurve es una spline racional o una spline no racional. La B-spline no racional es un caso especial de B-splines racionales. true si es una spline racional; de lo contrario, false es una spline no racional. |

 **Result:**



---


### setRational{#setRational}

| Nombre | Descripción |
| --- | --- |
| setRational(value) | Obtiene o establece si es racional, este valor indica si este NurbsCurve es una spline racional o una spline no racional. La B-spline no racional es un caso especial de B-splines racionales. true si es una spline racional; de lo contrario, false es una spline no racional. |

 **Result:**



---


### getColor{#getColor}

| Nombre | Descripción |
| --- | --- |
| getColor() | Obtiene o establece el color de la línea, el valor predeterminado es blanco(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| Nombre | Descripción |
| --- | --- |
| setColor(value) | Obtiene o establece el color de la línea, el valor predeterminado es blanco(1, 1, 1) |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nombre | Descripción |
| --- | --- |
| getParentNodes() | Obtiene todos los nodos padre; una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría. Los nodos. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nombre | Descripción |
| --- | --- |
| getExcluded() | Obtiene o establece si excluir esta entidad durante la exportación. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nombre | Descripción |
| --- | --- |
| setExcluded(value) | Obtiene o establece si excluir esta entidad durante la exportación. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nombre | Descripción |
| --- | --- |
| getParentNode() | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. El nodo padre. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nombre | Descripción |
| --- | --- |
| setParentNode(value) | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. El nodo padre. |

 **Result:**



---


### getScene{#getScene}

| Nombre | Descripción |
| --- | --- |
| getScene() | Obtiene la escena a la que pertenece este objeto |

 **Result:**



---


### getName{#getName}

| Nombre | Descripción |
| --- | --- |
| getName() | Obtiene o establece el nombre. El nombre. |

 **Result:**



---


### setName{#setName}

| Nombre | Descripción |
| --- | --- |
| setName(value) | Obtiene o establece el nombre. El nombre. |

 **Result:**



---


### getProperties{#getProperties}

| Nombre | Descripción |
| --- | --- |
| getProperties() | Obtiene la colección de todas las propiedades. |

 **Result:**



---


### evaluate{#evaluate}

| Nombre | Descripción |
| --- | --- |
| evaluate(steps) | Evalúa la curva NURBS |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| steps | Número | La frecuencia de evaluación entre dos nudos vecinos, el valor predeterminado es 20 |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| Nombre | Descripción |
| --- | --- |
| evaluateAt(u) | Evalúa el punto de la curva en la posición especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| u | Número | La posición en la curva, entre 0 y 1 |

 **Result:**
Vector4


---


### getEntityRendererKey{#getEntityRendererKey}

| Nombre | Descripción |
| --- | --- |
| getEntityRendererKey() | Obtiene la clave del renderizador de entidad registrado en el renderizador |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Nombre | Descripción |
| --- | --- |
| getBoundingBox() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Nombre | Descripción |
| --- | --- |
| removeProperty(property) | Elimina una propiedad dinámica. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| property | Property | Qué propiedad eliminar |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nombre | Descripción |
| --- | --- |
| removeProperty(property) | Eliminar la propiedad especificada identificada por nombre |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| propert | Cadena | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nombre | Descripción |
| --- | --- |
| getProperty(property) | Obtener el valor de la propiedad especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| property | Cadena | Nombre de la propiedad |

 **Result:**
Objeto


---


### setProperty{#setProperty}

| Nombre | Descripción |
| --- | --- |
| setProperty(property, value) | Establece el valor de la propiedad especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| property | Cadena | Nombre de la propiedad |
| valor | Objeto | El valor de la propiedad |

 **Result:**
Objeto


---


### findProperty{#findProperty}

| Nombre | Descripción |
| --- | --- |
| findProperty(propertyName) | Busca la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| propertyName | Cadena | Nombre de la propiedad. |

 **Result:**
Property


---



