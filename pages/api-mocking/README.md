# API Mocking

> Apidog 에서 API Mocking 사용법을 설명합니다.

1. [API Mocking의 종류](#1-api-mocking의-종류)
2. [Mock 데이터 생성 방법에 따른 분류](#2-mock-데이터-생성-방법에-따른-분류)
   - [2.1. Smart Mock](#21-smart-mock)
   - [2.2. Advanced Mock](#22-advanced-mock)
3. [Mock 사용 환경에 따른 분류](#3-mock-사용-환경에-따른-분류)
   - [3.1. Local Mock](#31-local-mock)
   - [3.2. Cloud Mock](#32-cloud-mock)

## 1. API Mocking의 종류

API Moking의 방식은 크게 2가지로 분류됩니다.

Mock 데이터 생성 방법에 따른 분류

    1. Smart Mock
    2. Advanced Mock

Mock 사용 환경에 따른 분류

    1. Local Mock
    2. Cloud Mock

## 2. Mock 데이터 생성 방법에 따른 분류

Smart Mock과 Advanced Mock은 API 문서에 정의된 스펙을 기반으로 자동으로 Mock 데이터를 생성하여, 개발자들이 빠르게 API 호출에 대한 응답을 확인할 수 있게 합니다.

Smart Mock과 Advanced Mock은 응답 생성의 복잡성, 조건 처리 및 로직에 따라 구분됩니다.

### 2.1. Smart Mock

Smart Mock은 API 문서에 정의된 스펙을 기반으로 상대적으로 간단한 응답을 생성합니다.

Smart Mock은 단순한 조건과 기본적인 로직 처리가 가능합니다.

![smark-mock-1](/docs/api-mocking/smart-mock-1.png)

    - Response의 Mock 탭에 값을 지정하지 않으면 해당 타입의 Random 값으로 설정

    - Mock 탭에 타입을 지정하면 Faker.js 기반의 Mock 데이터 생성

![smark-mock-2](/docs/api-mocking/smart-mock-2.png)

### 2.2. Advanced Mock

Advanced Mock은 좀 더 복잡하고 정교한 응답을 생성합니다.

Advanced Mock은 복잡한 조건과 다양한 로직을 처리할 수 있습니다. 또한, 요청 파라미터에 따라 동적으로 응답을 생성 할 수 있습니다.

![advanced-mock-1](/docs/api-mocking/advanced-mock-1.png)

    Case 1 : Expectations을 작성하여 조건과 로직을 처리

![advanced-mock-2](/docs/api-mocking/advanced-mock-2.png)

    Case 2 : Script를 작성하여 조건과 로직을 처리

![advanced-mock-3](/docs/api-mocking/advanced-mock-3.png)

## 3. Mock 사용 환경에 따른 분류

Mock을 사용하기 위한 환경으로는 Local Mock과 Cloud Mock이 있습니다.

### 3.1. Local Mock

로컬 환경에서 실행되는 Mock으로써, 개발자의 로컬 머신 또는 로컬 네트워크 내에서 Mock 서버를 구성하여 사용합니다.

네트워크 제한이 있는 환경에서 유용하지만, 외부에서 접근하기 어렵습니다.

![local-mock-1](/docs/api-mocking/local-mock-1.png)
![local-mock-2](/docs/api-mocking/local-mock-2.png)

### 3.2. Cloud Mock

Apidog의 클라우드 서버를 통해 Mock API를 호스팅합니다.

클라우드 서버를 통해 동작하기 때문에 외부 서비스와 통합하기 쉽습니다.

![cloud-mock-1](/docs/api-mocking/cloud-mock-1.png)

    Cloud Mock을 사용하기 위해서는 Setting/Mock Setting 에서 Cloud Mock을 허용합니다.

![cloud-mock-2](/docs/api-mocking/cloud-mock-2.png)
![cloud-mock-3](/docs/api-mocking/cloud-mock-3.png)
