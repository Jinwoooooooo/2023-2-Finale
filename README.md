# 2023-2-Finale<br>
1학년 2학기 프론트엔드 기말과제<br>
<p style="text-align: center;">https://jinwoooooooo.github.io/2023-2-Final-Assignment/</p>

## 과제 소개

첫 화면은 상영 중인 영화 목록을 보여준다. 각 영화에는 영화 포스터, 영화 제목, 상영 시간, 
연령 등급이 있고 상단에는 상영 중인 영화의 예고편과 광고를 넣고 반복 재생을 한다.
영화 포스터를 클릭하면 일반, 청소년 인원 선택 창이 뜬다. 

인원은 일반, 청소년 합해서 최대 16명까지 가능하다.
인원 선택을 하고 다음 버튼을 클릭하면 좌석 선택 창이 뜬다.

선택한 인원만큼 좌석을 선택할 수 있고 여기서도 다음 버튼을 클릭하면 결제 창으로 넘어간다.
결제는 카드로만 결제가 가능하다.

카드는 미리 만들어놓은 카드를 드래그해서 카드 리더기에 올려놓으면 결제되고 “결제 완료” 
라는 경고창이 나온다. 그럼 정상적으로 결제가 된 것이다.
결제가 되면 영수증(티켓)을 화면에 띄운다.

영수증이 나온 화면 상단에 홈 버튼과 프린트 버튼이 있다.
프린트 버튼을 클릭하면 영수증을 프린트 할 수 있다.
홈 버튼을 클릭하면 다시 첫 화면으로 돌아오게 된다.

이전 사용자가 홈 버튼을 안 누르고 갈 수도 있겠다 라는 생각이 들어서
영수증 화면에서 20초가 지나면 자동으로 첫 화면으로 전환된다.
다음 사용자가 바로 오지 않았다면 다음 사용자는 첫 화면으로 키오스크를 바로 이용할 수 있다.

만약 이전 사용자가 아이언맨 3의 좌석 A1, A2를 예매했다면 그 다음 사용자는
당연히 아이언맨 3의 좌석 A1, A2를 예매할 수 없다.
예매할 수 없다는 것을 알 수 있게 예매된 좌석은 배경색을 회색으로 변경했다.
