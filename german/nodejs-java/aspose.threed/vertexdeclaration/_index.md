---
title: "VertexDeclaration"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/vertexdeclaration/
---
## VertexDeclaration class

Die Deklaration der Struktur eines benutzerdefinierten Vertex


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
| getSealed() | Ein VertexDeclaration wird versiegelt, wenn es von com.aspose.threed.TriMesh`1 oder TriMesh verwendet wurde; weitere Änderungen sind nicht mehr erlaubt. |

 **Result:**



---


### getCount{#getCount}

| Name | Beschreibung |
| --- | --- |
| getCount() | Ermittelt die Anzahl aller in dieser VertexDeclaration definierten Felder |

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
| addField(dataType, semantic, index, alias) | Ein neues Vertex-Feld hinzufügen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| dataType | Zahl | VertexFieldDataType |
| semantic | VertexFieldSemantic | VertexFieldSemantic |
| index | Zahl | Der Index für das gleiche Feldsemantic, -1 für automatische Erzeugung |
| alias | String | Der Alias-Name des Feldes |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Name | Beschreibung |
| --- | --- |
| fromGeometry(geometry, useFloat) | Erstelle eine VertexDeclaration basierend auf dem Layout einer Geometry. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| geometr | Geometry | null |
| useFloat | boolean | Verwende float anstelle des double-Typs |

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
Zahl


---


### equals{#equals}

| Name | Beschreibung |
| --- | --- |
| equals(obj) | Bestimmt, ob diese Instanz und ein angegebenes Objekt, das ebenfalls ein VertexDeclaration-Objekt sein muss, denselben Wert haben. |

 **Result:**
Zahl


---


### iterator{#iterator}

| Name | Beschreibung |
| --- | --- |
| iterator() | Für die interne Verwendung reserviert. |

 **Result:**
Zahl


---



