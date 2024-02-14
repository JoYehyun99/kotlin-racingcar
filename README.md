# kotlin-racingcar

### 그라운드 룰
- 예니와 에디
- 드라이버와 네비게이터는 기능 단위로 교체한다.
- 서로 배려한다.

### 구현 기능 정리
1. 자동차 이름을 입력 받는 기능
    - 자동차 이름은 5자를 초과할 수 없다. 
    - 자동차 이름은 쉼표(,)를 기준으로 구분한다.

2. 시도 횟수를 입력 받는 기능
    - 자동차를 몇 번 이동 시킬 지 입력 받는다.

3. 자동차 이동 기능 (전진 혹은 멈춤)
    - 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우 전진한다.

4. 진행 상황 출력 기능
    - 시도 횟수 만큼 자동차 이동 기능을 실행 한다.
    - 실행 할때 마다 자동차의 상태를 화면에 출력 한다.
    - 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력 한다.

5. 우승자 판별 기능
    - 가장 많이 이동한 자동차 우승자를 선별한다.
    - 우승자는 한 명 이상일 수 있다.