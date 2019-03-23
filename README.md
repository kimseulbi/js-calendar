# JS-Calendar

## Calendar

월별, 주별, 일별로 등록된 일정등록 할 수 있습니다.

## npm 명령

웹 실행시에 아래와같은 명렁어를 실행해주시면 됩니다.

- `npm install` - 프로젝트 실행에 필요한 파일을 설치하는 명령. 프로젝트 최초 실행 시 반드시 실행해주어야 합니다.
- `npm start` - 개발용 서버를 실행시키는 명령

## 기능

- [x] 처음실행시화면은월별캘린더의현재의달로시작되며, 오늘은다른색으로표시합니다.
- [ ] 상단에현재날짜(월별일경우년.월, 주별일경우월.몇째주, 일별일경우월.일로표시)
- [x] 화살표버튼과오늘버튼이있는메뉴툴바와월간, 주간, 일간을선택할수있는툴바가있다.
- [x] 화살표를통해날짜를바꾼다.
- [x] 오늘버튼을누를경우오늘로다시되돌아온다.
- [ ] 월간, 주간, 일간버튼을통해캘린더의모양이월별캘린더, 주별캘린더, 일별캘린더로변한다.
- [x] 주말의경우다른색으로표시(토요일은파란색, 일요일은빨간색)
- [ ] 캘린더의날짜에일정이있는경우가로막대바로일정이있는기간만큼표시하고(일정의시작부터일정의끝까지이어지도록)일정의시작부분막대바위에일정의제목을표시합니다.
- [ ] 같은날짜에중복된일정이있는경우시간순서대로아래로막대바를표시하고캘린더칸의높이만큼일정이가득차면표시하지않습니다.
- [ ] 주별캘린더의경우, 일주일단위로캘린더상단에오늘의일정을, 하단에시간별일정이나오도록합니다.
- [ ] 일별캘린더의경우, 하루단위시간별일정을표시합니다.일정추가
- [x] 일정을추가할수있는버튼또는캘린더안에날짜를눌렀을때일정을추가할수있는팝업이가운데표시됩니다.
- [x] 일정제목,시작시간,종료시간,메모를입력할수있어야합니다.
- [ ] 일정을입력한후확인버튼을누르면캘린더화면에일정이추가됩니다.
- [ ] 캘린더안에일정이표시된바를클릭하면일정에대한자세한내용이팝업으로표시됩니다.
- [ ] 표시된팝업에서일정을수정하거나삭제할수있어야합니다
