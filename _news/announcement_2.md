---
layout: post
title: I finally finished my internship as a SWE at Common Computer!
date: 2022-08-31 16:11:00-0400
inline: false
related_posts: false
---

2022년 6월 30일부터 2022년 8월 31일까지 Common Computer 에서 개발자로 인턴 생활을 하면서 경험한 것들과 느낀 점들을 써보고자 한다.

지원 동기
대학 과정 3–2를 수료한 시점에 기본적인 cs지식(컴퓨터 구조, 운영 체제, 네트워크 …)은 다 갖췄다고 생각했고(회사와서 보니 아직 멀었다), 회사에서는 어떤 일을 하는지 직접 경험해보고 싶은 마음에 학교 연계 현장실습 인턴을 알아보게되었다.
내가 회사를 고를 때 고려한 우선순위는 다음과 같다.

내가 하고 싶은 업무 : AI, back-end …
(주관적으로) 좋은 회사 : 지인 평, 회사 사업 구조, 관련 뉴스 등
위치 : 양재 시민의숲
급여 : 다른 곳보다 쫌 더 줌!
위 기준에서 open source AI model fine tuning 을 통해 자사 플랫폼에 배포하는 실습을 할 수 있는 Common Computer에 지원하였다.
또 metaverse, blockchain, AI 등 신사업에 주력하며 시리즈B까지 투자를 마쳤고 ainetwork, ainize, afan등 자사 플랫폼을 가지고 있어서 배울 점이 많을 것같았다.
위치는.. 버스타고 1시간 정도지만 재택근무가 가능해서 참았다. 재택 만세.
(+ 선발 절차에 면접이 없는 것도 크게 작용했다..)

뭐하는 회사지?
Build a collaborative computing network to realize the internet of value.

구글 번역기 왈: 가치 있는 인터넷을 실현하기 위해 협업 컴퓨팅 네트워크를 구축합니다.

회사의 비전은 위와 같다. 어떤 의미인지 묻는다면. 저도 잘 몰라요..
그래도~ 한번 설명해보자면, 먼저 “가치 있는 인터넷"에서 ‘가치'가 의미하는 것은 ‘좋은', ‘멋있는'이 아닌 ‘가치를 가지는’ 인 것 같다. 이는 WEB2.0에서 WEB3.0으로의 큰 변화 중 하나에 해당한다. 이를 실현하기 위해 blockchain network(ainetwork), cloud service(ainize), SNS service(afan) 등 다양한 layer에서 서비스를 개발을 하고 있다.

네.. 이렇게 심오한 내용에 대해 설명을 듣고 창업이란 쉽지 않구나라는 생각을 했다.

사실상 ainetwork 내부 에서도 baby-shark nff, soul-fiction, stradivarius 등 다양한 프로젝트들이 있는데 나는 이 쪽으론 문외한이라서 blockchain 쪽에 관심이 있다면 ainetwork dao 디스코드 서버에서 어떤 프로젝트가 있는지 보면 좋을 것 같다.

Join the AI Network DAO Discord Server!
Check out the AI Network DAO community on Discord - hang out with 159 other members and enjoy free voice and text chat.
discord.gg

내가 한 일
여기서 내가 할 일은 처음에는 ainize 플랫폼에 모델을 서빙하는 업무였다. 하지만 AI보다는 Back-end쪽을 하고 싶은 마음이 2% 정도 더 커서 매니저님과 상담 끝에 ainize 에서 모든 유저에게 무료로 제공하는 GPU자원을 채굴하는데 사용하는 악성 유저를 탐지하는 업무를 할당받았다.

일단 ainize에서 k8s와 docker로 workspace를 제공하기 때문에 k8s와 docker의 기본 개념에 대해서 공부를 하고 어떻게 workspace를 조회해서 채굴자인지 아닌지 판단할 수 있을지 research를 했다. (이후 판단 알고리즘은 보안상 생략)
또 회사에서 대부분 node로 작업을 하기 때문에 한번도 사용해본 적 없는 js를 공부했다. c, java, python 등 여러 언어를 접해봤기 때문에 기본적인 js문법은 빠르게 익혔으나, js에서 주로 사용되는 코드 스타일, 라이브러리, JSDOC 등은 매니저님이 코드 리뷰를 해주면서 거의 일주일 공부해야 알 수 있었던 내용들(혹은 계속 몰랐을 것들)을 배우는 데에 시간을 훨씬 단축시켜주신 것 같다!!

이 외에도 워크숍, OKR 선정, Uncommon Gallery 행사 참여 등 개발 업무 이 외에도 다양한 경험을 할 수 있었다.

하이원 리조트 워크숍과 언커먼 갤러리
하이원 리조트 워크숍과 언커먼 갤러리 babyshark nft 행사
회사 문화
일단 수평적인 구조를 가지고 모두에게 ‘님'이라는 호칭을 붙인다. 그리고 기본적으로 재택이 가능한 회사라서 대부분의 회의는 비대면으로 진행했다. 휴가도 눈치안보고 사용하고 싶은 날 자유롭게 사용할 수 있고, 병가를 \*내가 알기론 언제든 사용할 수 있다.(아프지 말자가 모토라고..) 아쉽게도 나는 너무 건강했다. 이처럼 매우 자유로운 분위기의 회사이다.

그리고 점심 식대를 15000원까지 제공해주셔서 회사에서 맛있는 것을 매우매우 많이 먹은 것 같다.. 또 동료분들도 다들 착하시고 재미있으셔서 출근하는 날에도 즐겁게 근무를 했다. 물론 출퇴근길은 즐겁지 않았다. 첫 회사라서 잘 모르지만 이렇게 자유로운 문화를 가진 곳은 몇 없을 것 같다고 생각했다.

회사에서 먹은 것들
회사에서 먹은 것들
무엇을 배웠나?
‘입사 전의 나’와 ‘현재의 나'를 비교해보니 짧은 시간에 정말 많은 것이 바뀐 것 같다. 개발 역량 이 외에도 다양한 분야에서 배운 것들이 많지만 압축해서 세가지 분야로 바뀐 점들을 나누어 보았다.

1. 협업 프로젝트 진행 방식
   이전 학교에서 팀프로젝트를 했을 때에는 github를 사용하기는 했으나, 거의 각자의 코드를 한 곳에 저장하는 용도였던 것 같다. 하지만 회사에서 처음으로 gitflow와 같은 git branch 방법론을 적용하고 어떻게 분업을 할지, 어떻게 function들 간의 dependency를 줄일지에 대해 고민을 하면서 협업 능력을 큰 폭으로 키울 수 있었다.

내가 한 프로젝트에서는 모든 사람들이 PR을 보낼 때 code review를 받는 과정을 거쳤다. 이 과정에서 어떻게하면 코드를 더 직관적으로 짤 수 있고 내가 만든 기능을 잘 설명할 수 있을지 항상 염두에 두고 코딩하는 습관을 기를 수 있었다. 그리고 review에서 받은 한마디 한마디가 내 삽질 시간을 몇시간씩 단축시켜주었다.
옛날에는 PR도 잘 모르고 reviewer approve 없이 merge를 즐겨해서 github YOLO 배지를 박제 당한 망나니였지만 회사에서 PR - code review process를 제대로 익힌 것 같다!

2. 커뮤니케이션에 대한 인식
   이전에는 다른 개발자와 소통할 수 있는 기회도 많이 없었고, 공동의 목표를 가지고 함께 무언가를 발전시키는 경험은 더더욱 없었다. 이로 인해 당연히 커뮤니케이션 능력을 키우기 힘든 상황이었다.
   하지만 여기서는 분기별로 1주일동안은 업무에서 손을 떼고 현재 자신의 업무와 고민 거리에 대해 동료들과 얘기하는 시간을 가지면서 각자 조금씩 흐트러진 공동의 목표를 재겨냥하는 시간을 가졌다. 물론 나는 이 때 입사 1주일차라서 많은 대화는 못했지만 주변에서 오가는 대화를 같이 경청하며 깨달은 점도 많았고 회사에서 얼마나 커뮤니케이션을 중요시하는지 알 수 있었다.

또, 우리 부서에서는 위클리(주차별 회의)에서 딱딱한 보고 형식을 지양한다. 대신 현재 업무 진척도와 부족한 점, 개선 점들을 솔직하게 말하고 동료들의 집단 지성을 사용해 조언을 해주며 토론 형식으로 회의를 진행한다. 이렇게 회의에서 진척도, 부족한 점, 개선 사항들을 정리하니 내가 지금까지 해왔던 것들이 정리가 되고 업무 속도에 대한 추정도 쉬워져서 시간 관리를 더 쉽게 할 수 있게 되었다. 또한 내 업무와 큰 관련없는 개발자분들도 무엇이든 물어보살의 서장훈처럼 진지하게 문제 해결에 도움을 많이 주셔서 빠르게 성장할 수 있었다.

이처럼 동료간의 커뮤니케이션은 코드 100줄 짜는 시간을 빼앗기는 것같지만 코드 1000줄을 수정하는 것을 미연에 막아주는 중요한 요소임을 깨달았다.

3. 개발 능력
   당연히 개발 능력도 많이 는 것이 느껴졌다. 여기서 처음으로 싱글 스레드인 nodejs를 배우면서 callback, promise, async/await 등 비동기 처리를 공부했다. 처음 공부할 때에는 머릿속이 꼬인 이어폰 줄처럼(사실 이것보단 덜..) 복잡했는데 지금은 어느 정도 추상화가 가능해졌다.

또, jest framework로 처음 테스트 코드를 작성하면서 테스트 코드의 중요성을 깨달았다. 프로그램이 복잡해질수록 유지/보수의 편의성을 위해 테스트 코드가 필요하고, 다른 개발자가 프로그램의 흐름을 빨리 파악하는데에 굉장한 이점을 주는 것을 느꼈다. 집을 나설 때 폰, 지갑, 마스크를 확인해야 나중에 다시 계단을 뛰어올라가는 일을 방지해주는 것처럼 처음 테스트 코드를 짜는 것이 귀찮더라도 나중에 함수 스택을 타고타고 올라가는 일을 막아 줄 수 있을 것이다.

끝으로
사실 끝이 아니다. 지금까지 글을 읽었다면 알겠지만 회사에 대한 만족도가 매우 높아서 올해 말까지 더 근무하기로 했다. 2개월은 정말 순식간에 지나간 것 같다. 거의 회사에 적응하고 이제 좀 알겠구나 싶을 때가 떠날 때였다. 이렇게 2개월간 느낀 점들을 글로써 정리하니 생각보다 많이 성장한 것같아서 뿌듯하다. 혹시나 옛날의 나와 같이 인턴을 고민하고 있는 사람이라면 나는 어떤 회사든 인턴을 해보는 것을 추천한다. 실전은 다르니까 ..

앞으로의 4개월기간에는 적응 기간없이 순수하게 회사에 기여할 수 있을 것 같다. 앞으로 내가 무슨 업무를 맡을지는 모르지만 회사가 나를 성장시켜준만큼 꼭 보답을 해야겠다.
