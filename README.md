# 자동차 경주 게임

## 규칙

---
- indent(인덴트, 들여쓰기) depth를 3이 넘지 않도록 구현한다. 2까지만 허용
- else 예약어를 쓰지 않는다
- 3항 연산자를 쓰지 않는다.
- 함수(또는 메소드)가 한 가지 일만 하도록 최대한 작게 만들어라.
- **모든 기능을 TDD로 구현해 단위 테스트가 존재해야 한다.**
- **모든 원시 값과 문자열을 포장한다.**
- **일급 컬렉션을 쓴다.**
- **Getter를 쓰지 않는다.**

## 기능 요구사항

---
- 각 자동차에 이름을 부여할 수 있다. 자동차 이름은 5자를 초과할 수 없다.
- 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.
- 자동차 이름은 쉼표(,)를 기준으로 구분한다.
- 전진하는 조건은 0에서 9 사이에서 random 값을 구한 후 random 값이 4이상일 경우이다.
- 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한명 이상일 수 있다.


## 구현 사항

---
- 자동차 이름들을 입력한다.
    - [x] "자동차 이름"은 5자를 초과 할 수 없다.
- "시도 할 횟수"를 입력한다.
    - [x] 시도 횟수는 음수 일 수 없다.
- 경기를 시작한다.
- 시도 횟수 만큼 자동차들을 움직인다.
  - [ ] 모든 자동차를 움직인다.
    - [x] 자동차를 움직인다.
      - [x] 0 이상 9 이하의 랜덤 값을 받는다. 
      - [x] 4 이상일 경우 한 칸 전진한다.
- 우승자를 출력한다.
