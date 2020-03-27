# ExilDirection is Closed. DeadlyTrade Started.
Path Of Exile Addon

# DeadlyTrade Overhaul Version
https://github.com/DeadlyCrush/DeadlyTradeOverhaul
# Status
## Build

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Download (Real-Time)

2020.02.16 ~ Now. ( Repository moved. : https://github.com/DeadlyCrush/DeadlyTradeOverhaul )

[![Github All Releases](https://img.shields.io/github/downloads/DeadlyCrush/DeadlyTrade/total.svg)]()

DeadlyTrade 1.0.0.0 Version. ~ 2020.02.15

[![Github All Releases](https://img.shields.io/github/downloads/DeadlyCrush/DeadlyTrade-Closed-Overhaul-Version-Open/total.svg)]()



안녕하세요. 데들리크러쉬입니다.
애드온 공유하는 입장인 저로써는 엑자일 디렉션, 머큐리, 필터 등등...

현재 시급하다고 생각하는 것들이 있는데 개인 시간은 부족하고 그래서,
그나마 간단하게 요청 사항을 반영할 수 있는 내용을 쉬어가는 업데이트? 정도로 생각하고 올립니다.
(
본 요청은
의외로 상당수의 의견과 마루치님 외... 스탠다드, 하드코어 유저의 요청 등... 
에 의해 추가되었습니다.
)

[ 2019.07.17 쉬어가는 업데이트 ]
: Ninja 시세창에서 리그를 선택할 수 있습니다.
: 첨부된 파일 압축을 풀고 아무 exe나 실행하시면 됩니다. ( 특수한 경우, x64를 실행하세요. )
: POExileDirection_LeagueSelect.zip 압축비번 1234




엑자일 디렉션을 처음 접하시는 분은 아래 게시물 내용들과
함께 소통한 많은 댓글들을 통해 정보를 습득하실 수 있습니다. ^_______^*

항상 응원해주시고 격려해주셔서 감사합니다.
의견, 지적, 제안, 오류 제보 등... 다른 여러 말씀도 주시면 감사하겠습니다.

오늘도 즐거운 엑자일 되세요. 미러 꼭 드시구요 ^^*~!


[ 참조 이미지 - 2019.07.17 시세 리그 선택 ]


![이미지_7](https://user-images.githubusercontent.com/11026168/61376563-6149aa80-a8dc-11e9-94ef-1117c394712b.png)
![이미지_039](https://user-images.githubusercontent.com/11026168/61376564-6149aa80-a8dc-11e9-9cae-51f2c2c50301.png)
![이미지_040](https://user-images.githubusercontent.com/11026168/61376565-61e24100-a8dc-11e9-87e9-5211d260ca4d.png)


![DeadlyCrush_2019_0717_000](https://user-images.githubusercontent.com/11026168/61376556-60b11400-a8dc-11e9-9a1b-cea50faeaa28.jpg)
![DeadlyCrush_2019_0717_001](https://user-images.githubusercontent.com/11026168/61376558-60b11400-a8dc-11e9-9338-3cff2c5dd3af.jpg)
![DeadlyCrush_2019_0717_002](https://user-images.githubusercontent.com/11026168/61376559-60b11400-a8dc-11e9-8cc6-6c4e838515d3.jpg)







[ Exile Direction 07.13 업데이트 안내 ]

   계획에 없었던 일이었는데 많은 분들이 수동 수정을 불편해하시는거 같아서,
   약간의 수정/보완만 포함해서 업데이트 올립니다. 정말 계획에 없던거에요;;

1. 카카오, ggg 클라이언트 선택
   1) client.txt 경로 등의 수정을 고민하지 마시고 그냥 선택하시면 됩니다.
   2) 최초 실행시 매번 물어봅니다. 다음번 업데이트에 개선할 생각입니다. 급하게 만드느라;;
   3) 결론, 카카오 클라이언트이든 ggg 클라이언트이든 메시지창에서 선택만 해주시면 됩니다.

   ![DeadlyCrush_2019_0713_002](https://user-images.githubusercontent.com/11026168/61376554-60187d80-a8dc-11e9-8429-6ee5adbef695.png)

2. 실시간 시세 데이터의 정확도 개선
   1) 이제 실시간 NINJA 데이터를 정확하게 현재 시분초 시점으로 가져옵니다.
   2) 창을 열 때 약간(2초 전후)의 시간이 걸려서 알림 메시지가 뜹니다.
   3) 그러므로, 하이드아웃 등... 안전한 곳에서만 사용하세요.
   

3. 오류 수정
   1) 은신처 이동시, 캐릭터 선택창으로 이동되는 현상 수정
   2) 나머지는... 정리중입니다. 긴급 업데이트니 이해해주세요. ^^;...

4. 오버레이 이미지 표현 외... 이미지를 사용하는 모든것에 대한 리소스를 줄였습니다.
   1) GDI 리소스를 원래도 거의 없다시피 했음을 알려드립니다.
   2) 이번에 이 부분을 넣은건 앞으로 계획중인 내용에서 GDI 리소스 관리가 필요해서 입니다.
   3) 원래 없던 GDI 리소스 조금이나마;; 더 줄었습니다.

5. 이제 x86은 별도로 배포하지 않습니다.
   1) AnyCPU에서 정상 동작해야 문제가 없는 PC이며, AnyCPU는 PC가 32비트이면 알아서 32bit로 동작합니다.
   2) x64는 특수한 상황을 고려해서 별도 배포합니다.
   3) .Net Framework는 정말 오래 PC관리를 하지 않은 이상 사용되는 4.6버전에 타게팅되어 있습니다.

6. 안내
   1) 업데이트 기능을 포함한 충전 기간의 아이디어와
   2) 제보해주신 내용들... 감사합니다.
   3) 여러 건의 및 의견들... 감사합니다.
   4) 모두 수용할 순 없지만 필요한 것들과 가능한 것들 선별해서 최대한 반영할 예정입니다.

※ 네이버 카페 첨부 파일 ( 본 게시물의 첨부파일 )
   ▷ ExileDirection_0713_AnyCPU.zip
   ▷ ExileDirection_0713_x64.zip

* GitHub
   ▷ https://github.com/DeadlyCrush/ExileDirection/releases/tag/1.1.1.1


감사합니다. 즐거운 주말 되세요 ^___________^*~.
( 조금 늦더라도 6. 안내에 말씀드린 업데이트 기다려주세용~. )



![이미지_4](https://user-images.githubusercontent.com/11026168/61376561-6149aa80-a8dc-11e9-8b4e-02e1d03272b7.png)
![이미지_5](https://user-images.githubusercontent.com/11026168/61376562-6149aa80-a8dc-11e9-9bc3-f3c85ca7f690.png)

![DeadlyCrush_2019_0707_004](https://user-images.githubusercontent.com/11026168/61376547-5f7fe700-a8dc-11e9-95a3-f106e291295e.png)
![DeadlyCrush_2019_0707_006](https://user-images.githubusercontent.com/11026168/61376548-5f7fe700-a8dc-11e9-9ec9-392d2a0183c7.png)
![DeadlyCrush_2019_0707_007](https://user-images.githubusercontent.com/11026168/61376549-5f7fe700-a8dc-11e9-89a1-b96b6ff960ae.png)
![DeadlyCrush_2019_0707_008](https://user-images.githubusercontent.com/11026168/61376550-60187d80-a8dc-11e9-94a8-4f9dc7bb5cf7.png)
![DeadlyCrush_2019_0708_003](https://user-images.githubusercontent.com/11026168/61376551-60187d80-a8dc-11e9-82ee-5cc56c404593.png)


다음 카카오 클라이언트, ggg 클라이언트 (한글UI, 영문 UI) 모두 사용 가능 합니다.
+=======================+
+ Exile Direction V2. ( 07.08  )
+                  Ver. 1.1.1.1
+=======================+

안녕하세요. 데들리크러쉬 입니다.
혼신의업데이트는 뭐 거창한게 아니구요...
다름이 아니라 마눌님이 주말에도 집에서 일하냐고;; ㅠㅠ;; 혼신의 변명으로 막았습니다.

여러 의견들과 격려에 힘입어서 많은 부분 참고해서 부랴부랴 만들었습니다.
몇몇 오류나 정보 부족은 언제나 처럼 시간 능력 피로도 핑계를 대겠습니다~.
하지만, 피드백 주시는 내용들 확인해서 최대한 업데이트 하겠습니다!

[ 07.08 Ver. 1.1.1.1 ]



1. 이제 기본적으로 '관리자 권한'으로 실행을 요구합니다.

2. JUN (신디케이트), ALVA (템플,인커젼), Map (맵 추천) 오버레이가 각각 다른 창에 오버레이됩니다.

   1) 각각의 단축키로 3가지 오버레이를 켜고 끌 수 있습니다. 원하는 오버레이를 자유롭게 켜고 끄세요.
   2) 각각의 오버레이의 위치를 다르게 지정할 수 있습니다. 원하는 위치에 원하는 오버레이를 위치시키세요.
   3) 각각의 오버레이의 확대,축소 값을 각각 기억합니다.

   * 모든 오버레이를 완벽히 자유롭게 사용할 수 있습니다.
   물론, NINJA 실시간 확인창도 별도로 사용하실 수 있습니다.

![DeadlyCrush 2019_0708_003](https://user-images.githubusercontent.com/11026168/60776309-33d76100-a166-11e9-9345-d7023f98430f.png)

3. NINJA 실시간 시세 확인 기능 확장 및 편의 기능
   
   1) 커런시, 프레그먼트, 인큐베이터, 스카랍, 포실, 리조네이터, 에센스,
      디비네이션 카드, 프로퍼시, 유니크 맵, 맵 (엘더,쉐이퍼,일반), 유니크 쥬얼,
      유니크 플라스크, 유니크 웨폰, 유니크 아머, 유니크 악세서리
      : 총 16가지 카테고리별 실시간 시세를 확인하실 수 있습니다.
     ( 시세 확인 후 아이템 한글명을 확인하실 수 있습니다. : 한글명 일부 누락이 있습니다. )

   2) 실시간 시세 기준 엑잘 ↔ 카오스 변환기가 지원됩니다.
      : 향후 모든 커런시 변환(실시간 계산)기가 업데이트될 예정입니다.
      
![DeadlyCrush 2019_0708_002](https://user-images.githubusercontent.com/11026168/60771541-a4f62480-a124-11e9-85a9-1375bea11eea.png)


![DeadlyCrush 2019_0708_004](https://user-images.githubusercontent.com/11026168/60776559-24591780-a168-11e9-8994-30b2c89a97b0.png)


+=======================+
+ Exile Direction V2. ( 07.06  )
: 다음 카카오 클라이언트, ggg 클라이언트 (한글UI, 영문 UI) 모두 사용 가능
+=======================+

안녕하세요. 데들리크러쉬 입니다.
여러 의견 주신 내용들을 토대로 아래와 같이 기능을 수정/보완하고 추가하였습니다.

역시나 부족한 시간으로 욕심보다는 많이 공개하지 못했고 테스트 부족으로 인해서,
몇몇 정보가 부족하거나 오류가 있을지 모르겠습니다.

양해 부탁드리구요. 피드백 주시면 감사하겠습니다.

[ Exile Direction V2. ]

영상으로 소개/설명 https://youtu.be/BmhGuDk_5PI

: 반드시 관리자 권한으로 실행해주세요.

1. 메인창을 확대 축소할 수 있습니다.
2. 모든 창의 위치 및 크기가 기억됩니다.
3. 듀얼 모니터를 포함한 어느 곳이든 위치할 수 있습니다.
4. 오버레이 정보 이미지를 확대/축소할 수 있습니다.
5. 오버레이 정보를 단축키를 사용할 수 있도록 되돌렸습니다.
6. 각각의 단축키를 설정할 수 있습니다.
7. 몬스터 수 확인 기능을 다시 사용할 수 있습니다.
8. Poe.Ninja의 실시간 커런시 정보를 확인할 수 있습니다. (긴급 수정) 테스트 코드가 포함되어 있었습니다. 첨부 다시 올렸어요;; 죄송합니다. ㅠㅠ
9. 커런시 정보를 통해 현재 시세의 소숫점 엑잘을 카오스로 빠르게 계산할 수 있습니다.
10. 대부분의 창들을 위치와 크기를 조절해서 띄워놓거나 숨겨놓고 사용할 수 있습니다.
11. 컨트롤+마우스휠로 보관함 탭을 이동할 수 있습니다. (알려진 버그) 마우스 휠 업시 줌인이 같이 되는 현상

★ 중요 ★
설치가 정상이고 다른 기능들도 정상인데 액트 퀘스트 헬퍼에서 지역 이동시,
지역 인식이 정상적으로 되지 않는 분들은 로컬(지역) 채팅을 켜주세요.
( 제보해주신 '에베레체아'님 감사합니다~! )



[ 기능 안내 ] - 오버레이 확대 축소 및 이동이 가능합니다.
: 반드시 관리자 권한으로 실행해주세요.

Quest : 퀘스트 헬퍼
JUN : 신디케이트
ALVA : 템플(인커젼)
Map : 아틀라스
$ : 인게임 실시간 Ninja 커런시 시세 확인 ( 엑잘 소숫점 카오스 계산 포함 )
Setting : 단축키 설정
* 기타 : CTRL+마우스휠 보관함 탭 이동 기 (알려진 버그) 마우스 휠 업시 줌인이 같이 되는 현상


■ 기본 메인 창 : 위치이동 가능, 축소 가능, 퀘스트 헬퍼 및 오버레이 등을 여러곳에 배치해두고 사용 가능


■ 메인창 축소 및 자유로운 위치 이동



■ 실시간 시세 확인 ( Poe.Ninja 실시간 조회 ) : 기능 확장 예정입니다~~~ / 소숫점까지 표현해야 겠네요.



■ 액트 퀘스트 헬퍼 ( 영문/한글, 액트, 마을, 하이드아웃, 지역별(파악된 지역에 한해) 퀘스트 도움말과 이미지 )



■ JUN 아이콘 기능 (단축키 설정 가능 / 확대,축소 가능, 위치이동 가능(듀얼모니터 지원))



■ ALVA 아이콘 기능 (단축키 설정 가능 / 확대,축소 가능, 위치이동 가능(듀얼모니터 지원))



■ MAP 아이콘 기능 (단축키 설정 가능 / 확대,축소 가능, 위치이동 가능(듀얼모니터 지원))



■ 편의 기능 : 컨트롤+마우스휠로 보관함 탭 이동 기능 ( 알려진 버그 : 줌인 현상 수정 예정입니다. )

![DeadlyCrush 2019_0708_002](https://user-images.githubusercontent.com/11026168/60771541-a4f62480-a124-11e9-85a9-1375bea11eea.png)

![DeadlyCrush 2019_0707_009](https://user-images.githubusercontent.com/11026168/60761810-711af080-a08b-11e9-9305-adc06a2dae14.png)

![DeadlyCrush 2019_0707_002](https://user-images.githubusercontent.com/11026168/60761783-31ec9f80-a08b-11e9-8e7f-547ed348578c.png)

![DeadlyCrush 2019_0707_003](https://user-images.githubusercontent.com/11026168/60761795-46c93300-a08b-11e9-91ef-19ae7912dc2e.png)

![DeadlyCrush 2019_0707_004](https://user-images.githubusercontent.com/11026168/60761796-4a5cba00-a08b-11e9-851b-e205bab91609.png)

![DeadlyCrush 2019_0707_006](https://user-images.githubusercontent.com/11026168/60761798-4f216e00-a08b-11e9-9083-22f74d4fa8b9.png)

![DeadlyCrush 2019_0707_007](https://user-images.githubusercontent.com/11026168/60761802-53e62200-a08b-11e9-85df-097450b8dcbc.png)

![DeadlyCrush 2019_0707_008](https://user-images.githubusercontent.com/11026168/60761805-56e11280-a08b-11e9-8b72-cfbd15efcd41.png)




* 카페 게시물 첨부 파일 : AnyCPU, x64, x86 ( .Net Framework은 4.6으로 타게팅 통일했습니다. )
* GitHub 다운로드 : https://github.com/DeadlyCrush/ExileDirection/releases/tag/1.0.0.2

#패스오브엑자일 #PathOfExile #매크로 #Macro #애드온 #Addon 
#퀘스트 #액트 #헬퍼 #한글 #다음 #카카오


