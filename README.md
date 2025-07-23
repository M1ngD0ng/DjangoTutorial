## Django Tutorial - Polls App

### 주요 기능
- 일반 사용자
  - 설문 목록 조회
  - 설문 상세 페이지 조회 & 항목 선택 및 투표
  - 설문 결과 확인
- admin
  - 관리자 로그인
  - Question & Choice 추가/수정/삭제

### 주요 내용
**Part 1 : 프로젝트 설정 및 기본 View 구현**
- 프로젝트 생성 및 역할 이해
- urls.py를 통해 각각의 view와 URL 요청 연결
- HttpRequest & HttpResponse 기본 활용

**Part 2 : 데이터베이스, 모델, Admin**
- ORM 활용
- makemigration & migrate 활용으로 모델 변경사항을 DB 스키마에 반영
- 데이터 관리자 페이지 자동 생성

**Part 3 & 4 : Template, Form, Generic View**
- MVT 패턴 기본 이해
- 동적인 HTML 페이지 작성
- Form 처리 & CSRF 보안
- Generic View를 사용하여 코드 개선

**Part 5 : 테스트**
- TestCase를 활용하여 모델 & 뷰의 동작을 검증하는 테스트 코드 작성
- 간단한 TDD 방식 이해

**Part 6 & 7 : 정적 파일 & Admin 페이지 커스터마이징**
- static 디렉토리 생성 및 정적 파일 관리
- ModelAdmin 활용하여 관리자 페이지 커스터마이징

**Part 8 : 서트파티 패키지**
- django-debug-toolbar 설치하여 기능 확장
