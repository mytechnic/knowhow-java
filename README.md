# 애플리케이션  노하우

* 맵과 도메인
  * 문서로서의 가치
  
* 패키지 구성에 대한 고민 : 웹서비스, 배치서비스, 스케쥴러, MSA 등 여러 패키지에서 수용할 수 있는 패키지에 대한 고민
  * MVC 관점에서 컨트롤러, 스케쥴러, 메인 클래스 및 모델 패키지 위치
  * 클라이언트 패키지
  * 서비스 패키지

* 도메인 이름 컨벤션에 대한 고민
  * 도메인 + DTO, 도메인 + Entity, 도메인명의 가독성에 대한 고민
  * 도메인 + DAO, 도메인 + Mapper
  * JSON 데이터의 DB 저장 그리고 JsonString vs JsonObject vs Object 그리고 규격으로서의 가치

* 코드 중복과 모듈화 고민 : 코드 중복을 제거하는 것은 쉽지만, 모듈에서 사용한 DB 조회 등의 결과를 다시 전달받고 싶을 때 해결 방법

* DB 스키마에서 PK(ID)는 어떤 유형을 선택할까?
  * 일련번호 + FK : Integer? Long?
  * UUID + FK
  * FK

* JSON 통신에서 적절한 규격
  * Object형과 List형 그리고 규격으로서의 가치

* 애플리케이션의 오류 처리 방법 그리고 메시지 레이어
  * 비즈니스 로직의 오류메시지 전달 방법, 그리고 멀티라인 지원에 대한 고민
  * 애플리케이션 시스템 오류메시지와 외부 라이브러리의 오류메시지 전달에 대한 고민

* 요청과 응답 그리고 규격으로서의 가치, 그리고 레이어
  * 애플리케이션의 요청과 응답
  * DB의 저장, 검색과 결과
  * 통신의 요청과 결과

* 웹서비스의 이해
  * DNS 서비스의 이해와 인프라 지원 요청
  * 요청과 응답, 그리고 CPU, 메모리의 상관 관계
  
* 애플리케이션에 업로드/다운로드
  * 대용량 업로드와 스트림, 메모리의 관계
  * 대용량 다운로드와 스트림, 메모리와의 관계

* i18N, 로케일, 인코딩 ..... 등의 환경에 대한 고려
  * 시간
  * 인코딩
  
* 애플리케이션 Graceful Shutdown
