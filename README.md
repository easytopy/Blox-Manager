# Blox Manager
- This is a Discord Bot.
- This is a bot that has passed Discord's verification process.
#### Bot Status
- Serer DataBase: 700+
- Authenticator DataBase: 10k+
- Premium Server: 200+
- Joined Server: 600+

---
- Bot Name: `Blox Manager` 
- Roblox Bot Account: `Blox_ManagerBot` 
- Language: `Korean`
- How To Contact Developer: `easytopy` <-- Discord ID

---
#### Since 2020. 9. 10
###### Bot Name & Bot Account Change
##### NastyCore (2020. 9. 10) -> SparkleSystem (2022.7.15) -> Blox Manager (2023.10.7 ~)
---
### working structure
```mermaid
graph LR
A[Discord] -- Requests--> B((Blox Manager))
B -- Requests --> D{Roblox}
D -- Requests --> B
B --Requests --> A
```
# Links
- [Blox Manager Discord App Directory](https://discord.com/application-directory/1160070137580363787)
- [Blox Manager Guide - YouTube](https://www.youtube.com/@BloxManager)
- [Blox Manager Wiki - GitBook](https://wiki.blox-manager.kro.kr/)
- [Support Community - Discord](https://discord.gg/ANeNwBAt7m)
## Commands
```mermaid
graph LR
A[인증 관련] --> 인증
A --> 인증해제
A --> 업데이트
B[검색 관련] --> 유저검색
B --> 유저정보
B --> 그룹검색
B --> 그룹정보
C[설정 관련] --> F[설정]
D[프리미엄 관련]
D --> 샤우트
D --> 진급
D --> 강등
D --> 역할변경
D --> 그룹수락
D --> 그룹추방
E[그룹 연동 관련]
E --> 유저블랙
E --> 그룹블랙
F -- 버튼 --> a[일반설정]
F -- 버튼 --> b[업데이트설정]
F -- 버튼 --> c[로그설정]
F -- 버튼 --> d[프리미엄설정]
F -- 버튼 --> e[설정확인]
a -- 버튼 --> a1[그룹 연동 관련]
a -- 버튼 --> a2[역할 관련 설정]
a -- 버튼 --> a3[서브그룹 관련 설정]
a -- 버튼 --> a4[이름 관련 설정]
b -- 버튼 --> b1[업데이트 활성화]
b -- 버튼 --> b2[업데이트 비활성화]
c -- 버튼 --> c1[일반 설정 로그]
c -- 버튼 --> c2[프리미엄 설정 로그]
c -- 버튼 --> c3[블랙리스트 로그]
d -- 버튼 --> d1[봇 그룹에 추가]
d -- 버튼 --> d2[로블록스 역할 설정]
d -- 버튼 --> d3[디스코드 권한 설정]
d -- 버튼 --> d4[프리미엄 설정 확인]
e -- 버튼 --> e1[역할 설정확인]
e -- 버튼 --> e2[이름 설정확인]
e -- 버튼 --> e3[로그 설정확인]
a1 -- 버튼 --> 그룹연동
a1 -- 버튼 --> 그룹업데이트
a1 -- 버튼 --> 초기화
a2 -- 버튼 --> 그룹역할설정
a2 -- 버튼 --> 역할설정
a2 -- 버튼 --> 역할화리설정
a3 -- 버튼 --> 서브그룹역할설정
a3 -- 버튼 --> 서브그룹이름설정
a4 -- 버튼 --> 이름설정
a4 -- 버튼 --> 이름형식설정
d2 -- 버튼 --> d21[역할 잠금 설정]
d2 -- 버튼 --> d22[최대 변경 가능 역할설정]
d3  -- 버튼 --> d31[프리미엄 로그 채널 설정]
d3 -- 버튼 --> d32[모드 권한 설정]
d3 -- 버튼 --> d33[어드민 권한 설정]
d3 -- 버튼 --> d34[오너 권한 설정]
d4 -- 버튼 --> d41[로블록스 역할 설정 확인]
d4 -- 버튼 --> d42[디스코드 서버 설정 확인]
```
