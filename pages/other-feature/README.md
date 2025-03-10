# 기타 부가기능

> Apidog 에서 부가적인 기능을 설명하는 문서입니다.

1. [Generate Code](#1-generate-code)
   - [1.1. Generate Client Code](#11-generate-client-code)
   - [1.2. Generate Server Stubs and Client SDKs](#12-generate-server-stubs-and-client-sdks)
2. [Importing and Exporting Data](#2-importing-and-exporting-data)

## 1. Generate Code

Apidog를 사용하여 다양한 언어와 프레임워크에 대한 코드를 생성하는 방법을 소개합니다.

원하는 API 및 Schemas 따른 변환이 가능합니다.

    1. Generate Client Code(언어, 코드)
    2. Generate Server Stubs & Client SDKs(서버, 통신)

![generate-code-1](/docs/order-feature/generate-code-1.png)

### 1.1. Generate Client Code

클라이언트 코드 생성은 API 요청을 다양한 개발 환경에서 쉽게 시작할 수 있도록 돕습니다.
클라이언트 애플리케이션에서 API를 호출하고 데이터를 가져오는 데 사용됩니다.

![generate-code-2](/docs/order-feature/generate-code-2.png)
![generate-code-3](/docs/order-feature/generate-code-3.png)

### 1.2. Generate Server Stubs and Client SDKs

서버 스텁 및 클라이언트 SDK는 서버 측 비즈니스 로직을 구현하거나 클라이언트 애플리케이션이 서버와 통신하는 데 필요한 코드를 생성합니다.

모든 엔드포인트 또는 특정 태그를 통해 선택된 엔드포인트의 코드를 생성할 수 있습니다.

![generate-code-4](/docs/order-feature/generate-code-4.png)

## 2. Importing and Exporting Data

Apidog는 OpenAPI(Swagger), Postman 및 기타 형식을 포함한 다양한 데이터 형식으로부터 데이터를 가져오는 것을 지원합니다.

Apidog는 다양한 데이터 형식 의 파일을 json가져 오는 것을 지원합니다.
매개변수가 모두 같은 Swagger 파일에 작성 되면 path API 이름은 우선순위 목록을 기반으로 Apidog에 설정됩니다.

![importing-and-exporting-data-1](/docs/order-feature/importing-and-exporting-data-1.png)

Apidog는 OpenAPI Specification, HTML, Markdown, Apidog 등의 데이터 형식으로 API를 내보내는 것을 지원합니다.

![importing-and-exporting-data-2](/docs/order-feature/importing-and-exporting-data-2.png)
