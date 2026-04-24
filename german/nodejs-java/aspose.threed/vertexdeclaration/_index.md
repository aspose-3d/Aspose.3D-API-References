---
title: VertexDeclaration
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/vertexdeclaration/
---
## VertexDeclaration class

Die Deklaration der Struktur eines benutzerdefinierten Vertex.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getSealed{#getSealed}

| Name | Beschreibung |
| --- | --- |
| getSealed() | Eine VertexDeclaration wird versiegelt, wenn sie von com.aspose.threed.TriMesh`1 oder TriMesh verwendet wurde; weitere Änderungen sind nicht mehr erlaubt. |

 **Result:**



---


### getCount{#getCount}

| Name | Beschreibung |
| --- | --- |
| getCount() | Gibt die Anzahl aller in dieser VertexDeclaration definierten Felder zurück |

 **Result:**



---


### getSize{#getSize}

| Name | Beschreibung |
| --- | --- |
| getSize() | Die Größe in Byte der Vertex-Struktur. |

 **Result:**



---


### get{#get}

| Name | Beschreibung |
| --- | --- |
| get(index) |  |

 **Result:**



---


### clear{#clear}

| Name | Beschreibung |
| --- | --- |
| clear() | Alle Felder löschen. |

 **Result:**



---


### addField{#addField}

| Name | Beschreibung |
| --- | --- |
| addField(dataType, semantic, index, alias) | Ein neues Vertex-Feld hinzufügen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| dataType | Number | VertexFieldDataType |
| Semantik | VertexFieldSemantic | VertexFieldSemantic |
| Index | Number | Der Index für dieselbe Feldsemantik, -1 für automatische Generierung |
| Alias | String | Der Aliasname des Feldes |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Name | Beschreibung |
| --- | --- |
| fromGeometry(geometry, useFloat) | Erstellt eine VertexDeclaration basierend auf dem Layout einer Geometry. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Geometrie | Geometry | null |
| useFloat | boolean | Verwenden Sie float anstelle des double-Typs |

 **Result:**
VertexDeclaration


---


### compareTo{#compareTo}

| Name | Beschreibung |
| --- | --- |
| compareTo(other) | Vergleicht diese Instanz mit einem angegebenen Objekt und gibt einen Hinweis auf deren relative Werte zurück. |

 **Result:**
VertexDeclaration


---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### hashCode{#hashCode}

| Name | Beschreibung |
| --- | --- |
| hashCode() |  |

 **Result:**
Number


---


### equals{#equals}

| Name | Beschreibung |
| --- | --- |
| equals(obj) | Bestimmt, ob diese Instanz und ein angegebenes Objekt, das ebenfalls ein VertexDeclaration-Objekt sein muss, denselben Wert haben. |

 **Result:**
Number


---


### iterator{#iterator}

| Name | Beschreibung |
| --- | --- |
| iterator() | Für den internen Gebrauch reserviert. |

 **Result:**
Number


---



