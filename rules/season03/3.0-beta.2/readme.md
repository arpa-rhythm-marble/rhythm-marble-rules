# 리듬마블 규칙 ver3.0-beta.2 (230213 업데이트) "2023 스프링 시즌 베타테스트 규칙"
![logo](/assets/logo.png)


## 김편집 승리 조건

- 리듬마블 게임 판을 3바퀴 완주하면 컨텐츠가 종료됩니다.

- 완주 조건: 주사위를 이용하여 출발 칸에 도달할 것
..(마이너스 이동 등으로 출발 칸을 거쳐도 그 바퀴 완주로 칩니다)

- 랜덤 이동, 무인도로 이동 등 황금 열쇠를 이용한 이동은 출발 칸을 거치지 않은 것으로 간주합니다.



## 컨텐츠 진행 방식

- 지정된 리듬마블 판에서 -1,1,2,3,4가 그려진 주사위를 굴려 나온 수만큼 전진합니다.

- 출발 칸에 도달하여 1바퀴 완주했을 경우, 남은 주사위 눈이 있더라도 출발 칸에서 멈춘 후 판을 섞습니다.
..판을 섞을 때에는 각 항목의 위치만 변경됩니다.

- 시작 후 4시간이 경과했을 경우, 진행 촉진을 위해 -1이 없는 전진 주사위를 사용합니다.



## 주제가 쓰여져 있는 칸에 도달했을 경우

- 칸에 도달할 때마다 한 번 곡을 추첨하여 플레이합니다.

- 선곡 범위는 리듬마블 진행일 기준 김편집이 '집에서' 플레이할 수 있는 곡으로 한정합니다.
..(굳이 집에서 강조한 이유: 자꾸 오락실 게임 시키려고 염병함)



## 무인도에 도달했을 경우

- 무인도에 있는 동안 매 턴마다 곡을 추첨하여 플레이합니다.

- 무인도에서 나오려면 주사위를 2번 굴려 같은 수의 눈이 나오거나 (더블), 3턴 동안 곡을 플레이해야 합니다.



## 황금 열쇠가 그려져 있는 칸에 도달했을 경우

- 별도의 툴을 이용해 황금 열쇠 항목을 추첨합니다.

- 투네이션 룰렛을 통해 황금열쇠 항목을 추가할 수 있습니다.
..(1000원으로 55% 당첨/약한 항목들, 3000원으로 99.9% 당첨/빡센 항목들 추가 가능)

- 황금 열쇠에서 막고라가 나왔을 경우, 칸을 이동하지 않고 그 칸에서 곡을 추천받아 진행합니다.
..만약 패배하는 경우 황금 열쇠 항목을 하나 더 추첨합니다.



## 곡 추천 규칙

- 곡 길이는 3분 이내로 제한하나, 일부 상징적인 곡의 경우 3분을 조금 넘더라도 재량으로 플레이할 수 있습니다.
..(ex. 테스티파이 등)

- 같은 곡은 하루에 한 번만 나올 수 있습니다. (중복X)

- 여러 키 모드를 지원하는 게임의 경우, 현재 진행 중인 바퀴 수에 따라 플레이하는 모드를 변경합니다.
..(1바퀴: 4키, 2바퀴: 5키, 3바퀴: 6&8키)

- 게이지 설정을 지원하는 게임의 경우, 게임에 따라 정해진 국룰을 따릅니다.
..(ARCAEA: 하드게이지, 프세카: 힐카 포함한 풀 파워 덱)



## 일반, 무인도 칸 곡 추첨 규칙

- 현재 칸에 추천받은 곡 중 하나를 별도의 툴을 통해 추첨합니다.

- 곡은 !픽 (칸 번호) (곡 제목) 명령어를 통해 추천할 수 있습니다.
..칸 번호는 뱅하싶 칸을 제외하고 시계 방향으로, 시작 칸의 다음 칸부터 1로 하여 지정합니다.
..(예시: !픽 1 페로페로인더유니버스)

- !픽 명령어를 이용할 때, 1~24 범위 밖의 칸 번호를 지정하면 곡 추천으로 등록되지 않습니다.
..(예시: !픽 25 참철검)

- 자신이 추천한 곡이 추첨된 경우, 이후 추첨 대상에서 제외됩니다.

- 만약 해당 칸에 추천된 곡이 없는 경우, 시청자 중 1인을 추첨하여 곡을 추천받을 수 있습니다.



## 황금 열쇠 막고라, 추천된 곡이 없는 상황에서의 곡 추첨 규칙

- 시청자 중 1인을 추첨하여, 현재 칸에 쓰여있는 주제에 맞는 곡을 추천받습니다.
..무인도일 경우 해당 무인도에 해당하는 게임의 곡을 추천받습니다.
..황금 열쇠 막고라 곡 추첨일 경우, 해당 막고라에 해당하는 게임의 곡을 추천받습니다.

- 빠른 진행을 위해, 추첨이 된 시청자가 일정 시간 이상 반응이 없을 경우 차례가 스킵될 수 있습니다.

- 추첨을 통해 선정된 시점으로부터 30분 이내에 채팅이 없을 경우 자동으로 스킵됩니다.
..(주기적으로 참여하실 분들은 아무말 하나씩 쳐달라고 말씀드리니 그때마다 와주시면 스킵될 일은 없을듯ㅎㅎ;;)

- 30분 이내에 채팅이 있는 경우라도, 추첨을 통해 선정된 시점으로부터 30초 이내에 응답이 없을 경우 스킵됩니다.

- 2분 이내에 선곡을 하지 못한 경우 스킵될 수 있습니다.

- 단, 선곡 시간 제한은 상황에 따라 방장이 재량껏 늘릴 수 있습니다.
..(곡을 잘 몰라서 채팅창 추천을 받아야 하는 경우나 중복인지 애매해서 고민중인 상황 등에는 더 기다려드립니다)















## 사용되는 주사위 일람

 - 일반 주사위를 제외한 나머지 특수 주사위들은 황금 열쇠나 기타 특수 상황 때 사용됩니다.

 일반 주사위 : -1, 1, 2, 3, 4
 (특별한 조건이 없을 때 사용하는 일반 주사위입니다.)

 홀수 주사위 : -1, 1, 1, 3, 3
 (황금열쇠 항목 / 홀수만 나오는 주사위입니다.)

 짝수 주사위 : -2, 2, 2, 4
 (황금열쇠 항목 / 짝수만 나오는 주사위입니다.)

 조커 주사위 : -4, -4, 4, 4, 4
 (황금열쇠 항목 / 매우 극단적인 주사위입니다.)

 전진 주사위 : 1, 2, 3, 4
 (진행 시간이 4시간을 넘겼을 때 속도 촉진을 위해 대체로 사용하는 주사위입니다.)

 후진 주사위 : 1, -1, -2, -3, -4
 (황금열쇠 항목 / 삭제마려움)

 내맘대로 주사위 : 뱅하싶, 트하싶
 (황금열쇠 항목 / 방장or트수가 일반 주사위 범위 내에서 갈 곳을 정할 수 있는 주사위입니다.)

 황금열쇠 주사위 : 다음 황금열쇠, 이전 황금열쇠
 (황금열쇠 항목 / 근처 황금열쇠 칸으로 이동하는 주사위입니다.)