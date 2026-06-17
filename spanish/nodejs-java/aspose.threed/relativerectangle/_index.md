---
title: "RelativeRectangle"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

Rectángulo relativo  La fórmula entre el componente relativo y el valor absoluto es:  Escala  (Ancho de referencia) + desplazamiento  Así que si queremos que represente un valor absoluto, deje todos los campos de escala en cero y use los campos de desplazamiento en su lugar.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(left, top, width, height) | Construye un RelativeRectangle |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| lef | Número | null |
| a | Número | null |
| widt | Número | null |
| heigh | Número | null |

 **Result:**



---


### getScaleX{#getScaleX}

| Nombre | Descripción |
| --- | --- |
| getScaleX() | Coordenada relativa X |

 **Result:**



---


### setScaleX{#setScaleX}

| Nombre | Descripción |
| --- | --- |
| setScaleX(value) | Coordenada relativa X |

 **Result:**



---


### getScaleY{#getScaleY}

| Nombre | Descripción |
| --- | --- |
| getScaleY() | Coordenada relativa Y |

 **Result:**



---


### setScaleY{#setScaleY}

| Nombre | Descripción |
| --- | --- |
| setScaleY(value) | Coordenada relativa Y |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| Nombre | Descripción |
| --- | --- |
| getScaleWidth() | Ancho relativo |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| Nombre | Descripción |
| --- | --- |
| setScaleWidth(value) | Ancho relativo |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| Nombre | Descripción |
| --- | --- |
| getScaleHeight() | Altura relativa |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| Nombre | Descripción |
| --- | --- |
| setScaleHeight(value) | Altura relativa |

 **Result:**



---


### getOffsetX{#getOffsetX}

| Nombre | Descripción |
| --- | --- |
| getOffsetX() | Obtiene o establece el desplazamiento para la coordenada X |

 **Result:**



---


### setOffsetX{#setOffsetX}

| Nombre | Descripción |
| --- | --- |
| setOffsetX(value) | Obtiene o establece el desplazamiento para la coordenada X |

 **Result:**



---


### getOffsetY{#getOffsetY}

| Nombre | Descripción |
| --- | --- |
| getOffsetY() | Obtiene o establece el desplazamiento para la coordenada Y |

 **Result:**



---


### setOffsetY{#setOffsetY}

| Nombre | Descripción |
| --- | --- |
| setOffsetY(value) | Obtiene o establece el desplazamiento para la coordenada Y |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| Nombre | Descripción |
| --- | --- |
| getOffsetWidth() | Obtiene o establece el desplazamiento para el ancho |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| Nombre | Descripción |
| --- | --- |
| setOffsetWidth(value) | Obtiene o establece el desplazamiento para el ancho |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| Nombre | Descripción |
| --- | --- |
| getOffsetHeight() | Obtiene o establece el desplazamiento para la altura |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| Nombre | Descripción |
| --- | --- |
| setOffsetHeight(value) | Obtiene o establece el desplazamiento para la altura |

 **Result:**



---


### toAbsolute{#toAbsolute}

| Nombre | Descripción |
| --- | --- |
| toAbsolute(left, top, width, height) | Convertir el rectángulo relativo a rectángulo absoluto |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| left | Número | Izquierda del rectángulo |
| top | Número | Superior del rectángulo |
| ancho | Número | Ancho del rectángulo |
| height | Número | Altura del rectángulo |

 **Result:**
Rect


---


### fromScale{#fromScale}

| Nombre | Descripción |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | Construir un RelativeRectangle con todos los campos de desplazamiento en cero y los campos de escala a partir de los parámetros proporcionados. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| escala | Número | null |
| escala | Número | null |
| scaleWidt | Número | null |
| scaleHeigh | Número | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() | Convierte el valor de esta instancia a un java.lang.String. |

 **Result:**
RelativeRectangle


---



