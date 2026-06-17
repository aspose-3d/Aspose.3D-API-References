---
title: "Metered"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/metered/
---
## Metered class

metered key 를 설정하는 메서드를 제공합니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | 이 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### setMeteredKey{#setMeteredKey}

| 이름 | 설명 |
| --- | --- |
| setMeteredKey(publicKey, privateKey) | 계량형(public) 및 개인 키를 설정합니다. 계량형 라이선스를 구매한 경우 애플리케이션을 시작할 때 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다. 그러나 사용량 데이터를 업로드하는 데 지속적으로 실패하고 24시간을 초과하면 라이선스가 평가 상태로 전환됩니다. 이러한 상황을 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 이 API를 다시 호출해야 합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| publicKey | String | 공개 키 |
| privateKey | String | 개인 키 |

 **Result:**



---


### getConsumptionQuantity{#getConsumptionQuantity}

| 이름 | 설명 |
| --- | --- |
| getConsumptionQuantity() | 소비 파일 크기를 가져옵니다 |

 **Result:**
BigDecimal


---


### getConsumptionCredit{#getConsumptionCredit}

| 이름 | 설명 |
| --- | --- |
| getConsumptionCredit() | 소비 크레딧을 가져옵니다 |

 **Result:**
BigDecimal


---



