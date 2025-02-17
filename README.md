# dice 게임 만들기

1. 컴퓨터랑 붙는 게임
   - 나, 컴퓨터 배열이 존재
2. 각자 주사위 4개를 동시에 굴림

   - 각 주사위별 시간차를 두어서 재미요소를 더 할 수 있음 ( setTimeout )
   - 0.1초마다 주사위가 돌아가게끔 구현 ( setInterval )
   - 주사위 마다 각자의 값이 존재하게끔 구현
   - index \* 1초 한 값만 딜레이가 있게끔 구현

   - generateRandomNumber 라는 함수를 만들어서 1~6까지의 숫자가 나오도록 구현
   - .1초마다 각 주사위의 값을 저장해둔 index 값을 바꿔서 주사위의 모양 구현

3. 주사위 값을 합산한 값이 높으면 승리

   - 배열의 모든 값 더하는 방법(reduce)

4. 주사위 굴리기 버튼을 클릭해서 게임 시작

5. 주사위가 모두 돌아가면 게임 끝나면서 버튼 문구를 한 판 더!

6. 몇 대 몇인지에 대한 스코어도 출력해줌
