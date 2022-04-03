***Ransomware groups continue to target healthcare, critical services; here’s how to reduce risk***

https://www.microsoft.com/security/blog/2020/04/28/ransomware-groups-continue-to-target-healthcare-critical-services-heres-how-to-reduce-risk/


![human-operated-ransomware-payloads-blog-4](https://user-images.githubusercontent.com/75001605/161414059-75cc710c-22f8-4bb4-b405-3090cb644365.png)

APT공격? 초기공격 특정시스템을 노리고 머무르면서 추가공격하는것을 APT 공격이라한다.

Initial access 

credential theft
시스템 장악. 개인정보, 중요정보를 가져가려 한다.


lateral movement 백도어나 랜섬웨어 배포하는단계


공격 방법

**RDP BRUTE FORCE** 무작위 대입공격

**internet facing system** sql injectio 이런것들
**weak application settings** 앱 설정들이 미흡할때(관리자 페이지에 인증처리가 안되있다거나)
시스템 정보들에 인증없이 접근

mimiaktz: 시스템에 저장되있는 중요한 계정정보를 평문으로 가져온다 메모리덤프
Credential in plaintext: 데이터베이스에 중요한 정보들이 나

abuse of service accounts
계정 정보 취득

cobalt strike
WMI:윈도우 계정 공격
Abuse of management tools
PsExec:새로운 도구 설치할때 그흔적들. 

OSINT나 이런데에 노출되있으면 공격자들이 원격으로 공격
CVE 2020 0688영향받는 Microsoft exchange 서버
