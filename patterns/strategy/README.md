# Strategy Pattern
## Description
- Strategy Pattern (= Policy Pattern)은 실행 중에 알고리즘을 선택할 수 있게 하는 행위 소프트웨어 디자인 패턴이다.
- 특정 계열의 알고리즘들을 정의하고
- 각 알고리즘을 캡슐화하며
- 이 알고리즘들을 ***해당 계열 안에서 상호 교체*** 가 가능하게 만든다.  
  
![Strategy-Pattern](https://upload.wikimedia.org/wikipedia/commons/4/45/W3sDesign_Strategy_Design_Pattern_UML.jpg "Strategy Pattern")

## 🎮 Toy Project - 콘도회원등급에 따른 예약시스템
### 요구사항
1. 회원유형은 브론즈회원, 실버회원, 골드회원, 플래티넘회원이 있다. 
2. 객실유형은 일반객실, 디럭스객실, 스페셜객실, 패밀리객실, 파티객실
3. 브론즈회원은 일반객실과 디럭스객실을 예약할수 있다.
4. 실버회원은 일반객실, 디럭스객실, 스페셜객실을 예약할수 있다.
5. 골드회원은 일반객실과, 디럭스객실, 스페셜객실, 패밀리객실을 예약할수 있다.
6. 플래티넘회원은 모든 객실을 예약할수 있다. 
7. 골드회원과 플래티넘회원은 파티객실을 15% 할인된 가격에 예약할수 있다.