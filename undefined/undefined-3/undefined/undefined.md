# 모델 관리

### 1. 모델 관리 페이지 개요

모델 관리 페이지에 진입하면 다음 두 가지 주요 영역이 표시됩니다.

<figure><img src="../../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

#### ① 모델 생성 버튼

* 사용자가 새로운 AI 모델을 직접 등록할 수 있는 기능입니다.
* 클릭 시 **모델 생성 화면**으로 이동합니다.

#### ② 모델 템플릿 목록

* 관리자가 사전에 생성한 모델 템플릿 목록입니다.
* 사용자는 해당 템플릿을 선택하여 **손쉽게 모델을 생성 및 활용**할 수 있습니다.
* 템플릿은 **관리자만 생성/수정 가능**합니다.



### 2. 모델 생성

모델 생성 버튼을 클릭하면 새로운 AI 모델을 카탈로그에 등록할 수 있습니다.

<figure><img src="../../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

***

## &#x20;모델 생성 항목 설명

### 1. 기본 정보

<figure><img src="../../../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

#### 모델명

* 예: GPT-4, Claude-3
* 등록할 AI 모델의 이름을 입력합니다.

#### 제공사

* 예: OpenAI, Anthropic
* 해당 모델을 제공하는 회사명을 입력합니다.

#### 카테고리

* 예: 텍스트
* 모델의 주요 기능 유형을 선택합니다. (예: 텍스트 생성, 이미지 생성 등)

#### 버전

* 예: 1.0.0, v2
* 모델의 버전을 입력합니다.

#### 상태

* 예: 안정
* 모델의 운영 상태를 정의합니다. (예: 안정, 베타, 중단등)

#### 로고 URL

* 예: [https://example.com/logo.png](https://example.com/logo.png)
* 모델을 대표하는 이미지 URL을 입력합니다.

#### 모델 설명

* 모델에 대한 상세 설명을 입력합니다.
* 사용자가 모델을 선택할 때 참고할 수 있는 정보입니다.

#### API URL (선택사항)

* 예: [https://api.example.com/v1/models](https://api.example.com/v1/models)
* 모델과 연동할 API 엔드포인트를 입력합니다.
* 외부 모델 연동 시 사용됩니다.

***

### &#x20;2. 토큰 설정

모델 사용 시 토큰 관련 제한을 설정합니다.

<figure><img src="../../../.gitbook/assets/image (94).png" alt=""><figcaption></figcaption></figure>

#### 최대 토큰 수 (Max Tokens)

* 예: 4096
* 한 번의 요청에서 사용할 수 있는 최대 토큰 수입니다.

#### 입력 토큰 제한 (Input Tokens)

* 예: 2048
* 사용자가 입력할 수 있는 최대 토큰 수입니다.

#### 출력 토큰 제한 (Output Tokens)

* 예: 2048
* 모델이 생성할 수 있는 최대 토큰 수입니다.

***

### &#x20;3. 비용 설정

모델 사용 비용을 정의합니다.

<figure><img src="../../../.gitbook/assets/image (103).png" alt=""><figcaption></figcaption></figure>

#### 입력 토큰 비용

* 예: 0.00001
* 입력 토큰 1개당 비용을 설정합니다.

#### 출력 토큰 비용

* 예: 0.00003
* 출력 토큰 1개당 비용을 설정합니다.
