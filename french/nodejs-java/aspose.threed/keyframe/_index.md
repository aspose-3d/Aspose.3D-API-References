---
title: "KeyFrame"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

Une image clé est principalement définie par un temps et une valeur, pour certains types d'interpolation, la tangente/la tension/le biais/la continuité sont également utilisés pour calculer la valeur échantillonnée finale.  Les valeurs échantillonnées à une position temporelle sans image clé sont interpolées par les images clés entre les images clés précédentes et suivantes.  La valeur avant/après la première/dernière image clé est calculée par la classe Extrapolation.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(curve, time) | Créer une nouvelle image clé sur la courbe spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| curve | KeyframeSequence | La courbe sur laquelle l'image clé sera créée |
| time | Nombre | La position temporelle de l'image clé |

 **Result:**



---


### getTime{#getTime}

| Nom | Description |
| --- | --- |
| getTime() | Obtient ou définit la position temporelle de l'image clé list.data[index], mesurée en secondes. Le temps. |

 **Result:**



---


### setTime{#setTime}

| Nom | Description |
| --- | --- |
| setTime(value) | Obtient ou définit la position temporelle de l'image clé list.data[index], mesurée en secondes. Le temps. |

 **Result:**



---


### getValue{#getValue}

| Nom | Description |
| --- | --- |
| getValue() | Obtient ou définit la valeur de l'image clé. La valeur. |

 **Result:**



---


### setValue{#setValue}

| Nom | Description |
| --- | --- |
| setValue(value) | Obtient ou définit la valeur de l'image clé. La valeur. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| Nom | Description |
| --- | --- |
| getInterpolation() | Obtient ou définit le type d'interpolation de la clé, list.data[index] définit l'algorithme de calcul de la valeur échantillonnée. La valeur de la propriété est la constante entière Interpolation. L'interpolation. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| Nom | Description |
| --- | --- |
| setInterpolation(value) | Obtient ou définit le type d'interpolation de la clé, list.data[index] définit l'algorithme de calcul de la valeur échantillonnée. La valeur de la propriété est la constante entière Interpolation. L'interpolation. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| Nom | Description |
| --- | --- |
| getTangentWeightMode() | Obtient ou définit le mode de poids de la tangente de la clé. La tangente de sortie ou la prochaine tangente d'entrée peut être personnalisée en sélectionnant le WeightedMode correct. La valeur de la propriété est la constante entière WeightedMode. Le mode de poids de la tangente. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| Nom | Description |
| --- | --- |
| setTangentWeightMode(value) | Obtient ou définit le mode de poids de la tangente de la clé. La tangente de sortie ou la prochaine tangente d'entrée peut être personnalisée en sélectionnant le WeightedMode correct. La valeur de la propriété est la constante entière WeightedMode. Le mode de poids de la tangente. |

 **Result:**



---


### getStepMode{#getStepMode}

| Nom | Description |
| --- | --- |
| getStepMode() | Obtient ou définit le mode d'étape de la clé. Si le type d'interpolation est Interpolation.CONSTANT, list.data[index] détermine quelle valeur de l'image clé sera utilisée pendant l'interpolation. Un StepMode.PREVIOUS_VALUE signifie que la valeur de l'image clé de gauche sera utilisée. Un StepMode.NEXT_VALUE signifie que la valeur de l'image clé de droite suivante sera utilisée. La valeur de la propriété est la constante entière StepMode. Le mode d'étape. |

 **Result:**



---


### setStepMode{#setStepMode}

| Nom | Description |
| --- | --- |
| setStepMode(value) | Obtient ou définit le mode d'étape de la clé. Si le type d'interpolation est Interpolation.CONSTANT, list.data[index] détermine quelle valeur de l'image clé sera utilisée pendant l'interpolation. Un StepMode.PREVIOUS_VALUE signifie que la valeur de l'image clé de gauche sera utilisée. Un StepMode.NEXT_VALUE signifie que la valeur de l'image clé de droite suivante sera utilisée. La valeur de la propriété est la constante entière StepMode. Le mode d'étape. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| Nom | Description |
| --- | --- |
| getNextInTangent() | Obtient ou définit la prochaine tangente d'entrée (gauche) sur cette image clé. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| Nom | Description |
| --- | --- |
| setNextInTangent(value) | Obtient ou définit la prochaine tangente d'entrée (gauche) sur cette image clé. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| Nom | Description |
| --- | --- |
| getOutTangent() | Obtient ou définit la tangente de sortie (droite) sur cette image clé. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| Nom | Description |
| --- | --- |
| setOutTangent(value) | Obtient ou définit la tangente de sortie (droite) sur cette image clé. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| Nom | Description |
| --- | --- |
| getOutWeight() | Obtient ou définit le poids de sortie (droite) sur cette image clé. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| Nom | Description |
| --- | --- |
| setOutWeight(value) | Obtient ou définit le poids de sortie (droite) sur cette image clé. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| Nom | Description |
| --- | --- |
| getNextInWeight() | Obtient ou définit le poids suivant d’entrée (gauche) sur cette image clé. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| Nom | Description |
| --- | --- |
| setNextInWeight(value) | Obtient ou définit le poids suivant d’entrée (gauche) sur cette image clé. |

 **Result:**



---


### getTension{#getTension}

| Nom | Description |
| --- | --- |
| getTension() | Obtient ou définit la tension utilisée dans le spline TCB. |

 **Result:**



---


### setTension{#setTension}

| Nom | Description |
| --- | --- |
| setTension(value) | Obtient ou définit la tension utilisée dans le spline TCB. |

 **Result:**



---


### getContinuity{#getContinuity}

| Nom | Description |
| --- | --- |
| getContinuity() | Obtient ou définit la continuité utilisée dans le spline TCB. |

 **Result:**



---


### setContinuity{#setContinuity}

| Nom | Description |
| --- | --- |
| setContinuity(value) | Obtient ou définit la continuité utilisée dans le spline TCB. |

 **Result:**



---


### getBias{#getBias}

| Nom | Description |
| --- | --- |
| getBias() | Obtient ou définit le biais utilisé dans le spline TCB. |

 **Result:**



---


### setBias{#setBias}

| Nom | Description |
| --- | --- |
| setBias(value) | Obtient ou définit le biais utilisé dans le spline TCB. |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| Nom | Description |
| --- | --- |
| getIndependentTangent() | Obtient ou définit que les tangentes de sortie et la suivante d’entrée sont indépendantes. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| Nom | Description |
| --- | --- |
| setIndependentTangent(value) | Obtient ou définit que les tangentes de sortie et la suivante d’entrée sont indépendantes. |

 **Result:**



---


### getFlat{#getFlat}

| Nom | Description |
| --- | --- |
| getFlat() | Obtient ou définit si l’image clé est plate. L’image clé doit être plate si l’image clé suivante ou précédente a la même valeur. Une image clé plate possède des tangentes plates et une interpolation fixe. |

 **Result:**



---


### setFlat{#setFlat}

| Nom | Description |
| --- | --- |
| setFlat(value) | Obtient ou définit si l’image clé est plate. L’image clé doit être plate si l’image clé suivante ou précédente a la même valeur. Une image clé plate possède des tangentes plates et une interpolation fixe. |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| Nom | Description |
| --- | --- |
| getTimeIndependentTangent() | Obtient ou définit que la tangente est indépendante du temps. |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| Nom | Description |
| --- | --- |
| setTimeIndependentTangent(value) | Obtient ou définit que la tangente est indépendante du temps. |

 **Result:**



---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() | Obtient la représentation sous forme de chaîne de l’image clé |

 **Result:**
String


---



