# API 문서화 및 공유
> Apidog에서 API 문서를 설계하는 방법을 설명합니다.  
> Apidog을 활용하여 작성된 API 문서를 공유하고 배포하는 방식을 설명합니다.

1. [Getting Started](#1-getting-started)
2. [빠르게 문서 공유하기](#2-빠르게-문서-공유하기)
3. [문서 배포하기](#3-문서-배포하기)
    * [3.1. Custom Layout](#31-custom-layout)
    * [3.2. Custom Domain](#32-custom-domain)
    * [3.3. SEO 설정](#33-seo-설정)

## 1. Getting Started
API 문서를 빠르고 쉽게 공유하고, 배포할 수 있습니다.
    
    1. 공유 범위를 설정할 수 있습니다.
    2. 서로 다른 공유범위를 가진 문서를 생성할 수 있습니다.
    3. 원하는 형식으로 Export - Import 를 제공합니다.
    4. 매개변수를 통해 환경변수 정보를 전달할 수 있습니다.
    5. 환경설정을 통해 Running, Debbuging 기능을 제공할 수 있습니다.

## 2. 빠르게 문서 공유하기
API 문서를 빠르고 쉽게 공유할 수 있습니다.

![quick-1](/docs/api-documentation-sharing/quick-1.png)
![quick-2](/docs/api-documentation-sharing/quick-2.png)


    1. Share Docs 메뉴에 진입합니다.
    2. +New 버튼을 클릭하여, 공유 시 필요한 설정을 지정할 수 있습니다.

[**Scope to Share > Manual Selection**] 항목을 클릭하여 공유 범위를 지정할 수 있으며, 태그를 지정한 경우 [**Tag**] 항목에서 범위를 지정할 수 있습니다.

![quick-3](/docs/api-documentation-sharing/quick-3.png)   
![quick-4](/docs/api-documentation-sharing/quick-4.png)  

[**Scope to Share > Show API Field**] 항목을 클릭하여 API Field의 공유 여부와 필드 범위를 설정할 수 있습니다.

![quick-5](/docs/api-documentation-sharing/quick-5.png)  

## 3. 문서 배포하기
Apidog 문서 프로젝트를 온라인에 게시할 수 있습니다.

![publish-1](/docs/api-documentation-sharing/publish-1.png)
![publish-2](/docs/api-documentation-sharing/publish-2.png)

    1. Share Docs 메뉴에 진입합니다.
    2. Publish Project 항목의 Publish 메뉴에 진입합니다.
    3. 배포 옵션을 설정하고 Publish 버튼을 눌러 배포합니다.

### 3.1. Custom Layout
API 문서를 배포할 때, 문서의 레이아웃을 커스터마이징 할 수 있습니다.

![custom-layout](/docs/api-documentation-sharing/custom-layout.png)

### 3.2. Custom Domain
온라인 상에서 API 문서 접근시, 기본적으로 *[subdomain].apidog.io* 경로로 접근할 수 있습니다. 

사용자가 원한다면 Domain을 커스터마이징 하여 제공할 수 있습니다. 

![custom-domain](/docs/api-documentation-sharing/custom-domain.png)

또한 자체 Reverse-proxy 서비스를 구축하여 설정할 수 있습니다.



### 3.3. SEO 설정
Apidog에 게시된 문서에 대해 SEO를 적용할 수 있습니다.

![seo](/docs/api-documentation-sharing/seo.png)

    * Custom URL : 검색 엔진 친화적인 URL 구조를 설정할 수 있습니다.
    * Meta Data : Title, Description, Keywords를 설정할 수 있습니다.
    * Meta Social : 소셜 미디어에서 공유할 때 노출 할 이미지, 제목, 설명을 설정할 수 있습니다.