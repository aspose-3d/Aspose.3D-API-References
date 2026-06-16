---
title: "NurbsCurve"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

Una curva NURBS è una curva rappresentata da NURBS (Non-uniform rational basis spline).  Una curva NURBS è definita dal suo Ordine, da un insieme di Geometry.ControlPoints ponderati e da KnotVectors.  Il componente w nel punto di controllo è usato come peso del punto di controllo, indipendentemente dal fatto che sia CurveDimension.TWO_DIMENSIONAL o CurveDimension.THREE_DIMENSIONAL.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() | Inizializza una nuova istanza della classe NurbsCurve. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(name) | Inizializza una nuova istanza della classe NurbsCurve. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| name | Stringa | Nome |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Nome | Descrizione |
| --- | --- |
| getControlPoints() | Ottiene tutti i punti di controllo |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| Nome | Descrizione |
| --- | --- |
| getMultiplicity() | Ottiene la molteplicità. La molteplicità. |

 **Result:**



---


### getOrder{#getOrder}

| Nome | Descrizione |
| --- | --- |
| getOrder() | Ottiene o imposta l'ordine di una curva NURBS, definisce il numero di punti di controllo vicini che influenzano qualsiasi punto della curva. L'ordine. |

 **Result:**



---


### setOrder{#setOrder}

| Nome | Descrizione |
| --- | --- |
| setOrder(value) | Ottiene o imposta l'ordine di una curva NURBS, definisce il numero di punti di controllo vicini che influenzano qualsiasi punto della curva. L'ordine. |

 **Result:**



---


### getDimension{#getDimension}

| Nome | Descrizione |
| --- | --- |
| getDimension() | Ottiene o imposta la dimensione della curva. Il valore della proprietà è la costante intera CurveDimension. Per una curva CurveDimension.TWO_DIMENSIONAL, la componente z nel punto di controllo non è utilizzata. |

 **Result:**



---


### setDimension{#setDimension}

| Nome | Descrizione |
| --- | --- |
| setDimension(value) | Ottiene o imposta la dimensione della curva. Il valore della proprietà è la costante intera CurveDimension. Per una curva CurveDimension.TWO_DIMENSIONAL, la componente z nel punto di controllo non è utilizzata. |

 **Result:**



---


### getCurveType{#getCurveType}

| Nome | Descrizione |
| --- | --- |
| getCurveType() | Ottiene o imposta il tipo della curva. Il valore della proprietà è la costante intera NurbsType. Il tipo della curva. |

 **Result:**



---


### setCurveType{#setCurveType}

| Nome | Descrizione |
| --- | --- |
| setCurveType(value) | Ottiene o imposta il tipo della curva. Il valore della proprietà è la costante intera NurbsType. Il tipo della curva. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Nome | Descrizione |
| --- | --- |
| getKnotVectors() | Ottiene il vettore dei nodi, è una sequenza di valori di parametro che determina dove e come i punti di controllo influenzano la curva NURBS. |

 **Result:**



---


### getRational{#getRational}

| Nome | Descrizione |
| --- | --- |
| getRational() | Ottiene o imposta se è razionale, questo valore indica se questo NurbsCurve è una spline razionale o una spline non razionale. La B-spline non razionale è un caso speciale delle B-spline razionali. true se è una spline razionale; altrimenti, false indica una spline non razionale. |

 **Result:**



---


### setRational{#setRational}

| Nome | Descrizione |
| --- | --- |
| setRational(value) | Ottiene o imposta se è razionale, questo valore indica se questo NurbsCurve è una spline razionale o una spline non razionale. La B-spline non razionale è un caso speciale delle B-spline razionali. true se è una spline razionale; altrimenti, false indica una spline non razionale. |

 **Result:**



---


### getColor{#getColor}

| Nome | Descrizione |
| --- | --- |
| getColor() | Ottiene o imposta il colore della linea, il valore predefinito è bianco(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| Nome | Descrizione |
| --- | --- |
| setColor(value) | Ottiene o imposta il colore della linea, il valore predefinito è bianco(1, 1, 1) |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nome | Descrizione |
| --- | --- |
| getParentNodes() | Restituisce tutti i nodi genitore, un'entità può essere collegata a più nodi genitore per l'instancing della geometria. I nodi. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nome | Descrizione |
| --- | --- |
| getExcluded() | Ottiene o imposta se escludere questa entità durante l'esportazione. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nome | Descrizione |
| --- | --- |
| setExcluded(value) | Ottiene o imposta se escludere questa entità durante l'esportazione. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nome | Descrizione |
| --- | --- |
| getParentNode() | Ottiene o imposta il primo nodo genitore; se impostato il primo nodo genitore, questa entità verrà staccata dagli altri nodi genitore. Il nodo genitore. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nome | Descrizione |
| --- | --- |
| setParentNode(value) | Ottiene o imposta il primo nodo genitore; se impostato il primo nodo genitore, questa entità verrà staccata dagli altri nodi genitore. Il nodo genitore. |

 **Result:**



---


### getScene{#getScene}

| Nome | Descrizione |
| --- | --- |
| getScene() | Ottiene la scena a cui appartiene questo oggetto |

 **Result:**



---


### getName{#getName}

| Nome | Descrizione |
| --- | --- |
| getName() | Ottiene o imposta il nome. Il nome. |

 **Result:**



---


### setName{#setName}

| Nome | Descrizione |
| --- | --- |
| setName(value) | Ottiene o imposta il nome. Il nome. |

 **Result:**



---


### getProperties{#getProperties}

| Nome | Descrizione |
| --- | --- |
| getProperties() | Ottiene la collezione di tutte le proprietà. |

 **Result:**



---


### evaluate{#evaluate}

| Nome | Descrizione |
| --- | --- |
| evaluate(steps) | Valuta la curva NURBS |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| steps | Numero | La frequenza di valutazione tra due nodi adiacenti, il valore predefinito è 20 |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| Nome | Descrizione |
| --- | --- |
| evaluateAt(u) | Valuta il punto della curva nella posizione specificata |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| u | Numero | La posizione nella curva, tra 0 e 1 |

 **Result:**
Vector4


---


### getEntityRendererKey{#getEntityRendererKey}

| Nome | Descrizione |
| --- | --- |
| getEntityRendererKey() | Ottiene la chiave del renderer dell'entità registrata nel renderer |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Nome | Descrizione |
| --- | --- |
| getBoundingBox() | Ottiene il bounding box dell'entità corrente nel suo sistema di coordinate dello spazio oggetto. |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Nome | Descrizione |
| --- | --- |
| removeProperty(property) | Rimuove una proprietà dinamica. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| property | Property | Quale proprietà rimuovere |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nome | Descrizione |
| --- | --- |
| removeProperty(property) | Rimuovi la proprietà specificata identificata per nome |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| propert | Stringa | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nome | Descrizione |
| --- | --- |
| getProperty(property) | Ottieni il valore della proprietà specificata |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| property | Stringa | Nome della proprietà |

 **Result:**
Oggetto


---


### setProperty{#setProperty}

| Nome | Descrizione |
| --- | --- |
| setProperty(property, value) | Imposta il valore della proprietà specificata |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| property | Stringa | Nome della proprietà |
| valore | Oggetto | Il valore della proprietà |

 **Result:**
Oggetto


---


### findProperty{#findProperty}

| Nome | Descrizione |
| --- | --- |
| findProperty(propertyName) | Trova la proprietà. Può essere una proprietà dinamica (creata da CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata dal suo nome) |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| propertyName | Stringa | Nome della proprietà. |

 **Result:**
Property


---



