---
title: "KeyFrame"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

키 프레임은 주로 시간과 값으로 정의되며, 일부 보간 유형에서는 최종 샘플 값을 계산할 때 접선/텐션/바이어스/연속성도 사용됩니다. 키 프레임이 아닌 시간 위치의 샘플 값은 이전 및 다음 키 프레임 사이의 키 프레임에 의해 보간됩니다. 첫 번째/마지막 키 프레임 이전/이후의 값은 Extrapolation 클래스에 의해 계산됩니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(curve, time) | 지정된 곡선에 새로운 키 프레임을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| curve | KeyframeSequence | 키 프레임이 생성될 곡선 |
| time | 숫자 | 키 프레임의 시간 위치 |

 **Result:**



---


### getTime{#getTime}

| 이름 | 설명 |
| --- | --- |
| getTime() | list.data[index] 키 프레임의 시간 위치를 초 단위로 가져오거나 설정합니다. 시간. |

 **Result:**



---


### setTime{#setTime}

| 이름 | 설명 |
| --- | --- |
| setTime(value) | list.data[index] 키 프레임의 시간 위치를 초 단위로 가져오거나 설정합니다. 시간. |

 **Result:**



---


### getValue{#getValue}

| 이름 | 설명 |
| --- | --- |
| getValue() | 키 프레임의 값을 가져오거나 설정합니다. 값. |

 **Result:**



---


### setValue{#setValue}

| 이름 | 설명 |
| --- | --- |
| setValue(value) | 키 프레임의 값을 가져오거나 설정합니다. 값. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| 이름 | 설명 |
| --- | --- |
| getInterpolation() | 키의 보간 유형을 가져오거나 설정합니다. list.data[index]는 샘플링된 값이 계산되는 알고리즘을 정의합니다. 속성의 값은 Interpolation 정수 상수입니다. 보간. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| 이름 | 설명 |
| --- | --- |
| setInterpolation(value) | 키의 보간 유형을 가져오거나 설정합니다. list.data[index]는 샘플링된 값이 계산되는 알고리즘을 정의합니다. 속성의 값은 Interpolation 정수 상수입니다. 보간. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| 이름 | 설명 |
| --- | --- |
| getTangentWeightMode() | 키의 탄젠트 가중치 모드를 가져오거나 설정합니다. 외부 탄젠트 또는 다음 내부 탄젠트를 올바른 WeightedMode를 선택하여 사용자 지정할 수 있습니다. 속성의 값은 WeightedMode 정수 상수입니다. 탄젠트 가중치 모드. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| 이름 | 설명 |
| --- | --- |
| setTangentWeightMode(value) | 키의 탄젠트 가중치 모드를 가져오거나 설정합니다. 외부 탄젠트 또는 다음 내부 탄젠트를 올바른 WeightedMode를 선택하여 사용자 지정할 수 있습니다. 속성의 값은 WeightedMode 정수 상수입니다. 탄젠트 가중치 모드. |

 **Result:**



---


### getStepMode{#getStepMode}

| 이름 | 설명 |
| --- | --- |
| getStepMode() | 키의 단계 모드를 가져오거나 설정합니다. 보간 유형이 Interpolation.CONSTANT인 경우, list.data[index]는 보간 중에 사용할 키 프레임의 값을 결정합니다. StepMode.PREVIOUS_VALUE는 왼쪽 키 프레임의 값을 사용함을 의미하고, StepMode.NEXT_VALUE는 오른쪽 다음 키 프레임의 값을 사용함을 의미합니다. 속성의 값은 StepMode 정수 상수입니다. 단계 모드. |

 **Result:**



---


### setStepMode{#setStepMode}

| 이름 | 설명 |
| --- | --- |
| setStepMode(value) | 키의 단계 모드를 가져오거나 설정합니다. 보간 유형이 Interpolation.CONSTANT인 경우, list.data[index]는 보간 중에 사용할 키 프레임의 값을 결정합니다. StepMode.PREVIOUS_VALUE는 왼쪽 키 프레임의 값을 사용함을 의미하고, StepMode.NEXT_VALUE는 오른쪽 다음 키 프레임의 값을 사용함을 의미합니다. 속성의 값은 StepMode 정수 상수입니다. 단계 모드. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| 이름 | 설명 |
| --- | --- |
| getNextInTangent() | 이 키 프레임의 다음 내부(왼쪽) 탄젠트를 가져오거나 설정합니다. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| 이름 | 설명 |
| --- | --- |
| setNextInTangent(value) | 이 키 프레임의 다음 내부(왼쪽) 탄젠트를 가져오거나 설정합니다. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| 이름 | 설명 |
| --- | --- |
| getOutTangent() | 이 키 프레임의 외부(오른쪽) 탄젠트를 가져오거나 설정합니다. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| 이름 | 설명 |
| --- | --- |
| setOutTangent(value) | 이 키 프레임의 외부(오른쪽) 탄젠트를 가져오거나 설정합니다. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| 이름 | 설명 |
| --- | --- |
| getOutWeight() | 이 키 프레임의 외부(오른쪽) 가중치를 가져오거나 설정합니다. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| 이름 | 설명 |
| --- | --- |
| setOutWeight(value) | 이 키 프레임의 외부(오른쪽) 가중치를 가져오거나 설정합니다. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| 이름 | 설명 |
| --- | --- |
| getNextInWeight() | 이 키 프레임에서 다음 인(왼쪽) 가중치를 가져오거나 설정합니다. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| 이름 | 설명 |
| --- | --- |
| setNextInWeight(value) | 이 키 프레임에서 다음 인(왼쪽) 가중치를 가져오거나 설정합니다. |

 **Result:**



---


### getTension{#getTension}

| 이름 | 설명 |
| --- | --- |
| getTension() | TCB 스플라인에서 사용되는 장력을 가져오거나 설정합니다. |

 **Result:**



---


### setTension{#setTension}

| 이름 | 설명 |
| --- | --- |
| setTension(value) | TCB 스플라인에서 사용되는 장력을 가져오거나 설정합니다. |

 **Result:**



---


### getContinuity{#getContinuity}

| 이름 | 설명 |
| --- | --- |
| getContinuity() | TCB 스플라인에서 사용되는 연속성을 가져오거나 설정합니다. |

 **Result:**



---


### setContinuity{#setContinuity}

| 이름 | 설명 |
| --- | --- |
| setContinuity(value) | TCB 스플라인에서 사용되는 연속성을 가져오거나 설정합니다. |

 **Result:**



---


### getBias{#getBias}

| 이름 | 설명 |
| --- | --- |
| getBias() | TCB 스플라인에서 사용되는 바이어스를 가져오거나 설정합니다. |

 **Result:**



---


### setBias{#setBias}

| 이름 | 설명 |
| --- | --- |
| setBias(value) | TCB 스플라인에서 사용되는 바이어스를 가져오거나 설정합니다. |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| 이름 | 설명 |
| --- | --- |
| getIndependentTangent() | 출력 및 다음 입력 탄젠트가 독립적인지 가져오거나 설정합니다. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| 이름 | 설명 |
| --- | --- |
| setIndependentTangent(value) | 출력 및 다음 입력 탄젠트가 독립적인지 가져오거나 설정합니다. |

 **Result:**



---


### getFlat{#getFlat}

| 이름 | 설명 |
| --- | --- |
| getFlat() | 키 프레임이 평평한지 여부를 가져오거나 설정합니다. 다음 또는 이전 키 프레임이 동일한 값을 가지면 키 프레임은 평평해야 합니다. 평평한 키 프레임은 평평한 탄젠트와 고정된 보간을 가집니다. |

 **Result:**



---


### setFlat{#setFlat}

| 이름 | 설명 |
| --- | --- |
| setFlat(value) | 키 프레임이 평평한지 여부를 가져오거나 설정합니다. 다음 또는 이전 키 프레임이 동일한 값을 가지면 키 프레임은 평평해야 합니다. 평평한 키 프레임은 평평한 탄젠트와 고정된 보간을 가집니다. |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| 이름 | 설명 |
| --- | --- |
| getTimeIndependentTangent() | 탄젠트가 시간에 독립적인지 가져오거나 설정합니다. |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| 이름 | 설명 |
| --- | --- |
| setTimeIndependentTangent(value) | 탄젠트가 시간에 독립적인지 가져오거나 설정합니다. |

 **Result:**



---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 키 프레임의 문자열 표현을 가져옵니다. |

 **Result:**
String


---



