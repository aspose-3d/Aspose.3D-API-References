---
title: RelativeRectangle
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

Rectangle relatif  La formule entre le composant relatif et la valeur absolue est :  Échelle  (Largeur de référence) + décalage  Ainsi, si l'on veut qu'il représente une valeur absolue, laissez tous les champs d'échelle à zéro et utilisez les champs de décalage à la place.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(left, top, width, height) | Construit un RelativeRectangle |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| lef | Number | null |
| to | Number | null |
| widt | Number | null |
| heigh | Number | null |

 **Result:**



---


### getScaleX{#getScaleX}

| Nom | Description |
| --- | --- |
| getScaleX() | Coordonnée relative X |

 **Result:**



---


### setScaleX{#setScaleX}

| Nom | Description |
| --- | --- |
| setScaleX(value) | Coordonnée relative X |

 **Result:**



---


### getScaleY{#getScaleY}

| Nom | Description |
| --- | --- |
| getScaleY() | Coordonnée relative Y |

 **Result:**



---


### setScaleY{#setScaleY}

| Nom | Description |
| --- | --- |
| setScaleY(value) | Coordonnée relative Y |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| Nom | Description |
| --- | --- |
| getScaleWidth() | Largeur relative |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| Nom | Description |
| --- | --- |
| setScaleWidth(value) | Largeur relative |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| Nom | Description |
| --- | --- |
| getScaleHeight() | Hauteur relative |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| Nom | Description |
| --- | --- |
| setScaleHeight(value) | Hauteur relative |

 **Result:**



---


### getOffsetX{#getOffsetX}

| Nom | Description |
| --- | --- |
| getOffsetX() | Obtient ou définit le décalage pour la coordonnée X |

 **Result:**



---


### setOffsetX{#setOffsetX}

| Nom | Description |
| --- | --- |
| setOffsetX(value) | Obtient ou définit le décalage pour la coordonnée X |

 **Result:**



---


### getOffsetY{#getOffsetY}

| Nom | Description |
| --- | --- |
| getOffsetY() | Obtient ou définit le décalage pour la coordonnée Y |

 **Result:**



---


### setOffsetY{#setOffsetY}

| Nom | Description |
| --- | --- |
| setOffsetY(value) | Obtient ou définit le décalage pour la coordonnée Y |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| Nom | Description |
| --- | --- |
| getOffsetWidth() | Obtient ou définit le décalage pour la largeur |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| Nom | Description |
| --- | --- |
| setOffsetWidth(value) | Obtient ou définit le décalage pour la largeur |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| Nom | Description |
| --- | --- |
| getOffsetHeight() | Obtient ou définit le décalage pour la hauteur |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| Nom | Description |
| --- | --- |
| setOffsetHeight(value) | Obtient ou définit le décalage pour la hauteur |

 **Result:**



---


### toAbsolute{#toAbsolute}

| Nom | Description |
| --- | --- |
| toAbsolute(left, top, width, height) | Convertir le rectangle relatif en rectangle absolu |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| gauche | Number | Gauche du rectangle |
| haut | Number | Haut du rectangle |
| largeur | Number | Largeur du rectangle |
| hauteur | Number | Hauteur du rectangle |

 **Result:**
Rect


---


### fromScale{#fromScale}

| Nom | Description |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | Construit un RelativeRectangle avec tous les champs de décalage à zéro et les champs d'échelle provenant des paramètres fournis. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| scale | Number | null |
| scale | Number | null |
| scaleWidt | Number | null |
| scaleHeigh | Number | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() | Convertit la valeur de cette instance en java.lang.String. |

 **Result:**
RelativeRectangle


---



