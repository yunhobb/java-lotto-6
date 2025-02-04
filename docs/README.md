# 기능 목록
- [x] 로또 구입 금액 요청 메시지를 출력한다.
- [x] 로또 구입 금액을 입력 받는다.
  - [x] [예최처리] 숫자가 아닌 입력값을 받으면 예외처리한다.
  - [x] [예외처리] 10만원이 넘는 금액을 구매시 예외처리한다.
- [x] 구입금액 일급컬랙션을 생성 및 사용한다.
  - [x] [예외처리] 1,000단위로 입력을 받지 않으면 예외처리한다.
- [x] 구매한 로또수를 출력한다.
- [x] 로또 번호를 로또번호만큼 저장한다.
- [x] 로또 번호를 출력한다.
- [x] 당첨 번호를 입력 받는다.
  - [x] [예외처리] 숫자가 아닌값을 입력하면 예외처리한다.
- [x] 당첨 번호를 저장한다.
  - [x] [예외처리] 당첨 번호에 구분자가 없으면 예외처리한다.
- [x] 보너스 번호를 입력받는다.
  - [x] [예외처리] 추가번호가 당첨번호에 있을시 예외처리한다.
  - [x] [예외처리] 보너스 숫자는 1 ~ 45 범위여야 한다.
- [x] 결과 값을 판단하기 위한 enum을 만든다
- [x] 입력한 당첨번호와 랜덤으로 생성한 로또번호를 비교하는 기능을 구현한다.
  - [x] [예외처리] 범위가 벗어난 번호를 저장하면 예외처리를한다.
  - [x] [예외처리] 번호 중 중복이 있으면 예외처리한다.
- [x] 라이브러리를 사용해 Random한 로또번호를 구입금액에 비례해 출력한다.
- [x] 당첨 내역을 계산한다.
- [x] 수익률을 계산한다.
- [x] 당첨 통계를 출력한다.
- [x] 입력 실패시 에러메시지 출력 후 다시 입력받기
- [x] [예외처리] 로또 값을 가져올때 값이 없으면 예외처리 (State)
- [x] [예외처리] Ticket 가져올시 값이 없으면 예외처리 (State)

# 기능 요구사항
로또를 구현하는 게임입니다.

1. 금액을 입력합니다.
2. 입력한 금액만큼의 로또 매수를 출력한다.
3. 당첨번호 및 보너스 번호를 입력합니다.
4. 당첨 통계를 출력합니다.

# 프로그래밍 요구사항
* 2주차
  * indent depth를 2까지
  * 3항 연산자 사용 금지
  * 함수는 한가지 일만 하도록 작성
  * 테스트코드 작성
* 3주차
  * 함수의 길이가 15라인이 넘어가지 않도록
  * else 사용금지
  * Java Enum 적용
  * 도메인 로직의 단위테스트 구현 