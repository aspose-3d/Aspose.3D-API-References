---
title: "RelativeRectangle"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

상대 사각형  상대 구성 요소와 절대 값 사이의 공식은:  Scale (Reference Width) + offset  따라서 절대 값을 나타내려면 모든 scale 필드를 0으로 두고, offset 필드를 대신 사용하십시오.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(left, top, width, height) | RelativeRectangle를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| lef | 숫자 | null |
| to | 숫자 | null |
| 너비 | 숫자 | null |
| 높이 | 숫자 | null |

 **Result:**



---


### getScaleX{#getScaleX}

| 이름 | 설명 |
| --- | --- |
| getScaleX() | 상대 좌표 X |

 **Result:**



---


### setScaleX{#setScaleX}

| 이름 | 설명 |
| --- | --- |
| setScaleX(value) | 상대 좌표 X |

 **Result:**



---


### getScaleY{#getScaleY}

| 이름 | 설명 |
| --- | --- |
| getScaleY() | 상대 좌표 Y |

 **Result:**



---


### setScaleY{#setScaleY}

| 이름 | 설명 |
| --- | --- |
| setScaleY(value) | 상대 좌표 Y |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| 이름 | 설명 |
| --- | --- |
| getScaleWidth() | 상대 너비 |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| 이름 | 설명 |
| --- | --- |
| setScaleWidth(value) | 상대 너비 |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| 이름 | 설명 |
| --- | --- |
| getScaleHeight() | 상대 높이 |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| 이름 | 설명 |
| --- | --- |
| setScaleHeight(value) | 상대 높이 |

 **Result:**



---


### getOffsetX{#getOffsetX}

| 이름 | 설명 |
| --- | --- |
| getOffsetX() | 좌표 X에 대한 오프셋을 가져오거나 설정합니다 |

 **Result:**



---


### setOffsetX{#setOffsetX}

| 이름 | 설명 |
| --- | --- |
| setOffsetX(value) | 좌표 X에 대한 오프셋을 가져오거나 설정합니다 |

 **Result:**



---


### getOffsetY{#getOffsetY}

| 이름 | 설명 |
| --- | --- |
| getOffsetY() | 좌표 Y에 대한 오프셋을 가져오거나 설정합니다 |

 **Result:**



---


### setOffsetY{#setOffsetY}

| 이름 | 설명 |
| --- | --- |
| setOffsetY(value) | 좌표 Y에 대한 오프셋을 가져오거나 설정합니다 |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| 이름 | 설명 |
| --- | --- |
| getOffsetWidth() | 너비에 대한 오프셋을 가져오거나 설정합니다 |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| 이름 | 설명 |
| --- | --- |
| setOffsetWidth(value) | 너비에 대한 오프셋을 가져오거나 설정합니다 |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| 이름 | 설명 |
| --- | --- |
| getOffsetHeight() | 높이에 대한 오프셋을 가져오거나 설정합니다 |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| 이름 | 설명 |
| --- | --- |
| setOffsetHeight(value) | 높이에 대한 오프셋을 가져오거나 설정합니다 |

 **Result:**



---


### toAbsolute{#toAbsolute}

| 이름 | 설명 |
| --- | --- |
| toAbsolute(left, top, width, height) | 상대 사각형을 절대 사각형으로 변환합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 왼쪽 | 숫자 | 사각형의 왼쪽 |
| 위쪽 | 숫자 | 사각형의 위쪽 |
| 너비 | 숫자 | 사각형의 너비 |
| height | 숫자 | 사각형의 높이 |

 **Result:**
Rect


---


### fromScale{#fromScale}

| 이름 | 설명 |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | 주어진 매개변수로 스케일 필드를 설정하고 모든 오프셋 필드를 0으로 하여 RelativeRectangle를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 스케일 | 숫자 | null |
| 스케일 | 숫자 | null |
| scaleWidt | 숫자 | null |
| scaleHeigh | 숫자 | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 이 인스턴스의 값을 java.lang.String으로 변환합니다. |

 **Result:**
RelativeRectangle


---



