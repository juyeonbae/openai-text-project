## OpenAI API를 사용하여 텍스트 생성 및 처리
### 학습 목표
    - OpenAI의 최신 버전 ChatGPT OpenAPI를 사용하여 텍스트 생성 및 처리를 구현한다.
    - 자연어 처리(NLP)의 기본 개념을 이해하고, OpenAI API를 활용하여 실용적인 텍스트 생성 및 분석 애플리케이션을 개발한다.
    - OpenAI API를 통해 텍스트 생성, 요약, 번역, 질문-응답 등의 기능을 구현하며, 이러한 기능을 통합하여 간단한 웹 애플리케이션을 개발한다. 
 
### Overview
1. OpenAI API 계정 생성 및 API 키 발급
2. 프로젝트 초기 설정: 프로젝트 폴더 생성 및 초기화, 필요한 패키지 설치 (예: axios, express 등)
3. OpenAI API와 통신하는 모듈 개발: API 호출을 위한 함수 작성 및 테스트
4. 텍스트 생성 기능 구현: 입력받은 프롬프트를 기반으로 텍스트를 생성하는 기능 개발
5. 텍스트 요약 기능 구현: 긴 텍스트를 요약하는 기능 개발
6. 번역 기능 구현: 다국어 텍스트를 번역하는 기능 개발
7. 질문-응답 기능 구현: 사용자의 질문에 대한 답변을 생성하는 기능 개발
8. 간단한 웹 인터페이스 개발: React 또는 Vue.js를 사용하여 사용자 인터페이스 구현
9. API와 웹 인터페이스 연동: 백엔드와 프론트엔드 통합
10. 테스트 및 디버깅: 각 기능이 정상적으로 동작하는지 확인하고, 버그 수정
11. 사용 설명서 작성: 프로젝트 설정, 사용 방법, API 키 관리 방법 등을 설명하는 README 파일 작성
*** 
### 세부 계획 수립 단계
#### 계획 수립 단계(스택 선정 및 준비)
- OpenAI API 발급
    - GPT-4o mini 모델 사용
        - 선정 이유: 2024년 9월 23일까지 GPT-4o mini 모델의 파인 튜닝이 무료로 제공. 매일 최대 200만 개의 토큰을 무료로 사용할 수 있으며, 이를 초과하는 토큰은 백만 개당 3달러의 요금이 부과됨
- 필요 기술 스택 분석
    - 프로젝트 폴더 생성 및 초기화 : Node.js (npm)
    - 필요 패키지
        - axios (API 호출)
        - express (서버)
        - cors (Cross-Origin Resource Sharing)
        - dotenv (환경 변수 관리)

#### 프로젝트 진행 단계
1. OpenAI API와 통신하는 모듈 개발 : Axios (API 호출을 위한 HTTP 클라이언트)
2. 텍스트 생성 기능 구현
3. 텍스트 요약 기능 구현
4. 번역 기능 구현 (언어 선정)
5. 질문-응답 기능 구현
6. 웹 인터페이스 개발 툴 선택 (React 또는 Vue.js)
7. API와 웹 인터페이스 연동 (Express.js (백엔드)), Axios 또는 Fetch API (프론트엔드에서 API 호출)

#### 마무리 단계
1. 테스트 및 디버깅
2. readme 작성 
