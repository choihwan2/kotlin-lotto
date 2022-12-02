# kotlin-lotto

## 로또 

1. 로또 구매 
   1. 로또 구매 금액/1000 = 로또 개수
2. 로또 발급 
   1. 랜덤으로 1~50까지의 6개 숫자 발급하여 하나의 로또 구성 
   2. 추가로 1개의 숫자 발급하여 보너스볼 구성 
3. 당첨 금액 
   1. 3개 일치 : 5000원 
   2. 4개 일치 : 50000원 
   3. 5개 일치 : 1500000원
   4. 5개 일치 + 보너스볼 일치 : 30000000원
   5. 6개 일치 : 2000000000원
4. 입력값 검증 
   1. 로또 구매 금액은 음수가 아닌 숫자여야 한다.
5. 수입률 계산 
   1. 수입률 = (당첨금액-구입금액)/구입금액 

## 문자열 덧셈 계산기 

1. 구분자를 기준으로 분리한 숫자의 합을 반환한다. 
   1. 기본 구분자 : 쉼표(,) 또는 클론(:)
   2. 커스텀 구분자 : 문자열앞부분의 '//' 와 '\n' 사이의 문자 
2. 입력값을 검증한다.
   1. 음수 , 숫자이외는 RuntimeException 발생
