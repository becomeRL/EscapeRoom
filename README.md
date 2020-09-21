# ESCAPE ROOM
## collaborated with c2lv
***
+ How to Play

    1. ~에 갇힌 주인공의 탈출을 돕는 게임
    2. 화면 속 주변에 있는 단서를 수집하고 분석하여 나갈 수 있는 힌트를 얻는다.
    3. 제한 시간안에 성공하는 것이 관건.
    4. 만약 제시간에 탈출하지 못한다면...
   
+ What is needed 

    1. 오프닝, 엔딩, 게임 배경 화면
    2. 넘어가는 기능
    3. 화면 넘길 시 그 전 화면의 단서(이미지)를 숨기는 기능과 다시 나타나는 기능
    4. 단서(아이템)와 그 단서의 사용처 그리고 올바르게 했는지 판별하는 기능
    5. 단서를 보여주는 인벤토리와 사용한 후 삭제하는 기능  
    -> 아이템 소지여부 판단 boolean 변수(0,1) 먼저 추가하고 알고리즘 차근차근 짜면 모두 구현할 수 있을 것으로 보임. 1번부터 만들어보자
    6. 최종 문제와 그 문제의 정답 입력 및 판별 기능  
    참고한 방탈출 게임처럼 여러 문제를 풀어서 그 문제들의 정답을 조합하여 최종 문제의 답을 찾는 것?
    7. 어떠한 행동들을 할 경우, 화면 상단에 텍스트 보여주기 기능  
    이런 식으로? -> 물병을 클릭해서 획득한 경우, 화면 상단에 "물병을 획득했다. 어디에 쓰면 좋을까?" 플로팅

+ Game Story

    1. 게임 클리어시 교육적인 내용이나 교훈이 들어갔으면 하는 생각. 무한도전의 나비효과 특집을 참고하면 어떨까? 주제 선정부터 해도 괜찮겠다는 생각.
    2. 주인공이 방에 갇힌 이유를 잘 설정하여 플레이어의 몰입도와 흥미를 높이고 싶다는 생각.
    3. 엔딩을 여러 개 설정하여 리플레이성을 높였으면 하는 생각. 특정 아이템 소지 여부, 특정 미션 수행 여부, 클리어 소요 시간을 조건으로 해서...  
    참고할 만한 인디 게임: [지구멸망 60초전](https://namu.wiki/w/%EC%A7%80%EA%B5%AC%EB%A9%B8%EB%A7%9D%2060%EC%B4%88%20%EC%A0%84!)
