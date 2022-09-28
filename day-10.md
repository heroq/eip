## Day-10

[공부한 블로그](https://starrykss.tistory.com/1849?category=636189)

42. 모듈의 독립성을 나타내는 정도로, 모듈 내부 구성 요소 간 연관 정도를 나타내는 용어
> 응집도(Cohesion)

43. 응집도 유형 7가지
> 1. 우연적 응집도
> 2. 논리적 응집도
> 3. 시간적 응집도
> 4. 절차적 응집도
> 5. 통신적 응집도
> 6. 순차적 응집도
> 7. 기능적 응집도

44. 결합도의 유형 6가지
> 1. 내부 결합도
> 2. 공통 결합도
> 3. 외부 결합도
> 4. 제어 결합도
> 5. 스탬프 결합도
> 6. 자료 결합도

45. 배치 기법의 유형 3가지
> 1. 최적 적합(Best-Fit)
> 2. 최악 적합(Worst-Fit)
> 3. 최초 적합(First-Fit)

46. 교착 상태 해결 기법 4가지
> 1. 예방 기법(Prevention)
> 2. 회피 기법(Avoidance)
> 3. 발견 기법(Detection)
> 4. 복구/회복 기법(Recovery)

47. 시간의 흐름에 따라 상호작용 하는 과정을 액터, 객체, 메시지 등의 요소를 사용하여 그림으로 표현하는 UML 다이어그램
> 시퀀스 다이어그램

48. 테이블에서 일부 속성의 종속으로 인해 데이터 중복 문제가 발생하는 용어
> 1. 삽입 이상
> 2. 갱신 이상
> 3. 삭제 이상

49. 가상 테이블, 물리적으로 존재하지 않음
> 뷰(View)

50. 데이터베이스 정규화 단계
> 1. 1정규형(1NF) - 원자값으로 구성
> 2. 2정규형(2NF) - 부분 함수 종속
> 3. 3정규형(3NF) - 이행 함수 종속
> 4. 보이스-코드 정규형(BCNF) - 결정자 후보 키가 아닌 함수 종속
> 5. 4정규형(4NF) - 다치(다중 값) 종속
> 6. 5정규형(5NF) - 조인 종속

51. 테이블에서 일부 속성들의 종속으로 인해 데이터의 중복이 발생, 이 중복(Redundancy)으로 인해 테이블 조작 시 문제가 발생하는 현상
> 이상(Anomaly)

52. 데이터 정의어(Data Definition Language)의 종류를 쓰시오.
> 1. CREATE
> 2. ALTER
> 3. DROP
> 4. TRUNCATE

53. 데이터 조작어(Data Manipulation Language) 종류
> 1. CREATE
> 2. UPDATE
> 3. DELETE
> 4. SELECT

54. 데이터 제어어(Data Control Language) 종류
> 1. COMMIT
> 2. ROLLBACK
> 3. GRANT
> 4. REVOKE

55. TCL(Transaction Control Language)의 종류
> 1. COMMIT
> 2. ROLLBACK
> 3. SAVEPOINT

56. 참조되는 릴레이션에서 튜플을 삭제하고, 참조되는 릴레이션에서 이 튜플을 참조하는 튜플들도 함께 삭제하는 옵션
> CASCADE

57. 데이터베이스의 정의
> 1. 통합된 데이터(Integrated Data) - 자료의 중복을 배제한 데이터
> 2. 저장된 데이터(Stored Data) - 저장 매체에 저장된 데이터
> 3. 운영 데이터(Operational Data) - 조직의 업무를 수행하는 데 필요한 데이터
> 4. 공용 데이터(Shared Data) - 시스템들이 공동으로 사용하는 데이터

58. 데이터베이스 특성 4가지
> 1. 실시간 접근성(Real-Time Accessibility)
> 2. 계속적인 변화(Continuous Evolution)
> 3. 동시 공용(Concurrent Sharing)
> 4. 내용 참조(Content Reference)

59. 빅데이터의 특성 3가지
> 1. 데이터의 양(Volume)
> 2. 데이터의 다양성(Variety)
> 3. 데이터의 속도 (Velocity)

60. 데이터 마이닝의 주요 기법 4가지
> 1. 분류 규칙(Classification)
> 2. 연관 규칙(Association)
> 3. 연속 규칙(Sequence)
> 4. 데이터 군집화(Clustering)

61. 파티션의 종류 5가지
> 범위 파티셔닝(Range Partitioning)
> 해시 파티셔닝(Hash Partitioning)
> 목록 파티셔닝(List Partitioning)
> 컴포지트 파티셔닝(Composite Partitioning)
> 라운드로빈 파티셔닝(Round-Robin Partitioning)

62. 특정 테이블에 삽입, 수정, 삭제 등의 데이터 변경 이벤트가 발생 시 DBMS에서 자동적으로 실행
> 트리거(Trigger)

63. 기업에서 운영되는 서로 다른 플랫폼 및 애플리케이션들 간의 하나의 시스템으로 관리 운영할 수 있도록 서비스 중심의 통합을 지향하는 아키텍쳐
> ESB(Enterprise Service Bus)

64. 데이터 3가지
> 1. 데이터 무결성 - 부적절한 자료가 입력되어 동일한 내용에 대하여 서로 다른데이터가 저장되는 것을 허용 안함
> 2. 데이터 일관성 - 삽입, 삭제, 갱신 후에도 저장된 데이터가 변함이 없어야함
> 3. 데이터 회복성 - 장애가 발생시, 특정 상태로 복구 되어야함

65. HTTP, HTTPS, SMTP 등을 사용하여 XML 기반의 메세지를 네트워크 상태에서 교환
> SOAP(Simple Object Access Protocol)

66. 운영체제에서 프로세스 간 서로 데이터를 주고받기 위한 통신 기술
> IPC(Inter-Process Communication)

67. IPC(Inter-Process Communication)의 주요 기법 4가지
> 1. 메세지 큐
> 2. 공유 메모리
> 3. 소켓
> 4. 세마포어

68. 프로토콜의 기본 요소 3개
> 1. 구문(Syntax)
> 2. 의미(Semantic)
> 3. 타이밍(Timing)

69. 부분 함수적 종속 제거하여 완전 함수적 종속 만족
> 제 2정규형

70. 프로토콜
> 1. ICMP(Internet Control Message Protocol) - IP 패킷을 처리할 떄 발생되는 문제를 알려주는 프로토콜 
> 2. IGMP(Internet Group Management Protocol) - 멀티캐스트 그룹 멤버십을 구성하는ㄷ데 사용하는 프로토콜

