# API 디자인
> Apidog 에서 어떻게 API를 디자인하는지 설명하는 문서입니다.
1. [Get Start](#1-get-start)
2. [Design](#2-design)
    + [2.1. schema 정의](#21-schema-정의)
    + [2.2. schema 관리 및 자동생성](#22-schema-관리-및-자동생성)
    + [2.3. schema 고급타입](#23-schema-고급-타입)
    + [2.4. 자주 사용되는 Parameter 등록](#24-자주-사용되는-parameter-등록)
    + [2.5. Response Template 정의](#25-response-template-정의)
3. [Management](#3-management)
    + [3.1. 복수개의 API 관리](#31-복수개의-api-관리)
    + [3.2. Custom Field 정의](#32-custom-field-정의)
    + [3.3. API End-point에 고유 식별자 추가](#33-api-end-point에-고유-식별자-추가)

## 1. Get Start
새로운 End-point를 생성하거나, Import 하여 API Design 문서를 작성할 수 있습니다.  

![get-started-1](/docs/api-design/get-started-1.png)
![get-started-2](/docs/api-design/get-started-2.png)

## 2. Design
명확하고 완전한 API 문서를 만들기 위해, 아래의 과정을 거쳐 작성합니다.

    1. API Path 설정
    2. Request Method 명시
    3. Request Parameters 상세정보 기입
    4. Response Example 작성
    5. 온라인 문서 작성 및 배포

### 2.1. Schema 정의
API Response 정보와 JSON/XML 형태의 body parameters에서 사용됩니다. 이는 Apidog의 GUI를 활용해서 작성하거나, JSON/XML 데이터를 사용하여 설정할 수 있습니다.

또한 Database와 연동하여 데이터 구조를 적용할 수 있습니다.

![schema-1](/docs/api-design/schema-1.png)
![schema-2](/docs/api-design/schema-2.png)
![schema-3](/docs/api-design/schema-3.png)

### 2.2. Schema 관리 및 자동생성
스키마 작성 시, [**Reference Schema**]를 선택하여 다른 schema에 정의되어있는 데이터 구조를 불러올 수 있습니다.

작성중인 스키마에 한하여 구조를 변경하거나 Hide 버튼을 통해 숨김처리를 할 수 있습니다.

![schema-4](/docs/api-design/schema-4.png)

[**Generation Code**] 버튼을 통해 작성한 스키마를 여러 언어별 코드로 제공받을 수 있습니다. 
[**JSON Schema**] 버튼을 통해 직접 입력할 수도 있습니다.

![schema-6](/docs/api-design/schema-6.png)
![schema-5](/docs/api-design/schema-5.png)

### 2.3. Schema 고급 타입
HashMap, Dictionary, Array, Tuple 과 같은 타입을 스키마에 지정해줄 수 있습니다.

![schema-7](/docs/api-design/schema-7.png)
![schema-8](/docs/api-design/schema-8.png)

### 2.4. 자주 사용되는 Parameter 등록
자주 사용되는 Paramaters는 [**Common Parameters**] 에서 설정하고 관리할 수 있습니다.

![common-parameter](/docs/api-design/common-parameter.png)

### 2.5. Response Template 정의
API End-point 생성 시, 기본 Response를 설정할 수 있습니다.

![response-template-1](/docs/api-design/response-template-1.png)

Responses 항목에서 생성한 Response Template에서 [**Added in new endpoints by default**]를 *Yes*로 설정하는 경우, API End-point 생성시 자동으로 해당 Response가 추가됩니다.

![response-template-2](/docs/api-design/response-template-2.png)

API End-point에서 Responses 영역의 +Add 버튼을 클릭하여 필요한 [**Response Components**] 를 추가할 수 있습니다.

![response-template-3](/docs/api-design/response-template-3.png)

## 3. Management

### 3.1. 복수개의 API 관리
복수개의 API를 bulk로 관리할 수 있습니다.

![api-directory](/docs/api-design/api-directory.png)

    1. API 최상단 폴더를 클릭합니다.
    2. 네비게이션 메뉴에서 Endpoints를 클릭하여 API를 한 번에 관리합니다.

### 3.2. Custom Field 정의
API End-point 생성 시, default로 추가되는 기본정보 Field를 설정할 수 있습니다.

![custom-field](/docs/api-design/custom-field.png)

    1. Settings 메뉴에 진입합니다.
    2. Feature Settings > Endpoint Feature Settings 메뉴에 진입합니다.
    3. Endpoint Fields 항목에서 field 관련 정보를 설정합니다.

### 3.3. API End-point에 고유 식별자 추가
API End-point에 고유한 식별자를 지정하여 API 호출 시 발생할 수 있는 충돌을 방지합니다. 

![unique-field](/docs/api-design/unique-field.png)

    1. API 최상단 폴더를 클릭합니다.
    2. 네비게이션 메뉴에서 Folder Settings를 클릭합니다.
    3. Endpoint Unique ID 에서 Unique ID 방식을 선택합니다.
