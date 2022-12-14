### Day-1

[공부한 블로그](https://starrykss.tistory.com/1850)

두 개 이상의 하드디스크를 병렬로 연결   
- __RAID-0__

침입자를 속여 실제 공격당하는 것처럼 보여줌, 크래커를 추적   
- __허니팟__

오류를 제거하거나 수정한 시스템에서 오류 제거와 수정에 의해 새로이 유입된 오류가 없는지 확인하는 반복 테스트   
- __Regression(회기) Testing__

 짧은 시간에 사용자가 물릴 때 시스템의 반응을 측정하는 테스트 기법   
 - __Spike Testing__

멀티프로그래밍 환경에서 공유 자원에 대한 접근을 제한하는 기법   
한 프로세스 에서 ( )의 값을 변경하는 동안 프로세스가 동시에 이 값을 변경해서는 안됨   
()은 P, V 연산 기반  
 - __세마포어(Semaphore)__

저작권에 대한 사용 권한, 라이센스 발급, 사용량 관리 및 키 관리, 라이센서 발급 관리 등을 수행하는 도구   
- __클리어링 하우스__

콘텐츠를 메타데이터와 함께 배포 가능한 단위로 묶는 도구   
- __패키저__

컨테이너 응용 프로그램의 배포를 자동화하는 오픈소스 엔진, 소프트웨어 컨테이너 안에 응용 프로그램들을 배치시키는 일을 자동화      
- __도커__   

웹사이트를 크롤링하여 구조화된 데이터를 수집하는 파이썬 기반  
- __스크레파이__

 하나의 객체에 여러 개의 독립적인 객체들이 구성되는 관계   
- __집합 관계__

 테이블 분할 기법 중, ( ) 추가는 이력 관리 등의 목적으로 추가하는 테이블, 적절한 데이터양의 유지와 활용도를 높이기 위해 기본키를 적절히 설정   
- __진행 테이블__

컴퓨터 네트워크를 경유하는 프로세스 간 통신의 종착점   
OSI 7계층의 애플리케이션 계층에 존재하는 네트워크 응용 프로그램들 데이터를 송수신   
- __소켓__

 중요 데이터가 보관된 데이터베이스는 암호화가 필수, 암호화 복호화 모듈이 DB서버에 설치된 방식   
- __Plug In__ 

 7계층과 4계층 사이에서 클라이언트와 서버 간의 웹데이터 암호화(기밀성), 무결성 보장 443 포트   
- __SSL/TLS__

```
#include <stdio.h
void main() {
int i, j;
int a[3][2] = {{1, 2}, {3, 4}, {5, 6}};
int sum = 0;
    for (i = 0; i < 3; i++) {
        for (j = 0; j < 2; j++) {
            sum += a[i][j];
        }
    }
    printf("%.2f", (float)sum/(3*2));
}
답: 3.50 (%.2f여서 0을 붙혀야함)
```

 관리자가 인사담당자 고길동에게 '직원' 테이블에 대해 INSERT 할 수 있는 권한을 부여      
- __GRANT INSERT ON '직원' TO '고길동';__
 
 파라미터가 아닌 모듈 밖에 선언되어 있는 전역 변수를 참조   
- __공통 결합도(Common Coupling)__

 모듈 내에서 한 활동으로부터 나온 출력값을 다른 활동이 사용할 경우   
- __순차적 응집도(Sequential Cohesion)__

 위조된 매체 접근 제어(MAC) 주소를 지속적으로 네트워크로 흘려보내, 스위치 MAC 주소 테이블의 저장 기능을 혼란   
- __스위치 재밍__   

 MAC 주소로 위조한 ARP Reply 만들고, 희생자에게 지속적으로 전송   
- __ARP 스푸핑__

 애플리케이션에 사용자가 요구를 입력한 시점부터 트랙잭션을 처리, 그 결과의 출력이 완료할 때까지 걸리는 시간   
- __Turnaround Time__   

 애플리케이션이 트랙잭션 처리하는 동안 사용하는 CPU, 메모리, 네트워크 사용량   
- __Resource Usage__
 
