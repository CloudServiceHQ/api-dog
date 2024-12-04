# API 요청

> Apidog에서 API 요청을 관리하고 사용하는 방법을 설명하는 문서입니다.

1. [개요](#1-개요)
2. [API 요청 보내기](#2-api-요청-보내기)
   - [디자인 모드와 디버그 모드](#디자인-모드와-디버그-모드)
3. [인증](#3-인증)
4. [HTTP/2](#4-http2)

## 1. 개요

Apidog의 API 요청 기능은 다양한 인증 방식과 모드를 지원하여 개발자들이 손쉽게 API를 테스트하고 디버깅할 수 있도록 도와줍니다.

![api-request-overview](/docs/api-request/api-request-overview.png)

- 다양한 인증 방식 지원: 여러 인증 방식을 지원하여 다양한 API 요청을 손쉽게 관리할 수 있습니다.
- 디자인 모드와 디버그 모드 제공: 개발 과정에서 디자인과 디버그 모드를 통해 효율적으로 작업할 수 있습니다.
- HTTP/2 지원: 최신 프로토콜을 지원하여 빠르고 효율적인 요청을 보장합니다.

## 2. API 요청 보내기

### 디자인 모드와 디버그 모드

Apidog에서는 API 요청을 디자인 모드와 디버그 모드로 관리할 수 있습니다.

1. 디자인 모드: API 요청을 시각적으로 구성하고, 요청의 구조와 데이터를 정의합니다.
2. 디버그 모드: 실시간으로 API 요청을 보내고, 응답을 확인하며 문제를 디버깅할 수 있습니다.

![design-mode](/docs/api-request/design-mode.png)
![debug-mode](/docs/api-request/debug-mode.png)

## 3. 인증

API 요청에서 인증은 중요한 역할을 합니다. Apidog은 다양한 인증 방식을 제공하여 사용자들이 요구에 맞는 인증 방법을 선택할 수 있도록 합니다.

| 인증 방식       | 설명                                                           |
| --------------- | -------------------------------------------------------------- |
| 부모로부터 상속 | 부모로부터 인증 정보를 상속받아 사용할 수 있습니다.            |
| 인증 없음       | 인증이 필요 없는 API 요청을 할 수 있습니다.                    |
| API 키          | 헤더나 URL 매개변수에 API 키를 포함하여 인증하는 방법입니다.   |
| Bearer Token    | Bearer 토큰을 사용하여 인증하는 방법입니다.                    |
| JWT             | JSON Web Token을 사용하여 인증하는 방법입니다.                 |
| Basic Auth      | 사용자 이름과 비밀번호를 사용하여 기본 인증을 하는 방법입니다. |
| Digest Auth     | Digest 접근 인증을 사용하는 방법입니다.                        |
| OAuth 1         | OAuth 1.0a를 사용하여 인증하는 방법입니다.                     |
| OAuth 2         | OAuth 2.0을 사용하여 인증하는 방법입니다.                      |
| Hawk Auth       | Hawk 인증 방식을 사용하는 방법입니다.                          |
| NTLM            | NTLM 인증 방식을 사용하는 방법입니다.                          |
| Akamai EdgeGrid | Akamai EdgeGrid 인증 방식을 사용하는 방법입니다.               |

![authentication-overview](/docs/api-request/authentication-overview.png)

## 4. HTTP/2

Apidog은 HTTP/2 프로토콜을 지원하여 빠르고 효율적인 API 요청을 할 수 있습니다. HTTP/2는 여러 개의 요청을 하나의 TCP 연결에서 동시에 처리할 수 있어 성능을 향상시킵니다.

![http2-support](/docs/api-request/http2-support-1.png)
![http2-support](/docs/api-request/http2-support-2.png)
