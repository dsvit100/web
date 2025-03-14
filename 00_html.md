## HTML
- 하이퍼텍스트 - 클릭하면 기능하는 글자
- HTML 구조 / CSS 예쁘게 꾸밈 / javascript 동작
- mdn 튜토리얼을 기반하여 HTML을 공부할 것
- <opening tag> content </closing tag> = 하나의 요소
- <a></a> = 눌렀을 때 다른 페이지로 이동
- vscode 주석처리 방법 = ctrl + /
- html 코드 자동작성 = !
- <head> = 설정하는 부분 (사용자가 실제로 보는 부분 X)
- <body> = 사용자에게 보여지는 부분
- tag명 + tab = 여는 tag, 닫는 tag 자동완성
- <h1> = heading, 제목1
  - 계층을 표시할 때 씀 (단순히 크기에 대한 것이 아님)
- <p>
- strong, b = 둘 다 볼드체로 출력
- <strong> = 시멘틱태그(검색엔진최적화를 위해 강조하는 개념으로 사용됨)
- ul = 순서가 없는 리스트
- ol = 순서가 있는 리스트 (인덱스번호 출력)

### 기능 있는 태그
- <a href="">google</a> # href에 등록된 주소에 연결해주는 태그
- <img src="./hello.jpg" alt=""> # 이미지 넣는 태그, 글자 등 다른 방법으로 노출할 필요가 없으므로 닫는 태그가 없음
# alt = 지정한 이미지가 정상적으로 출력되지 않은 경우 대신 보여주는 부분
- <form>
- <input type="text"> # 사용자로부터 값을 입력받음
# text 대신 여러 값을 넣을 수 있음
- label, input과 함께 사용
- label은 id와 같은 이름으로 설정
- <br> 한줄 내리기