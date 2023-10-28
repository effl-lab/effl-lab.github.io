---
title: "Onboarding"
weight: 70
bookHidden: true
bookToc: false
---

EffL에 오신 것을 환영합니다! 🥳🥳

&nbsp; 

#### About this page
이 페이지는 대학원 입학허가를 받으신 분들의 온보딩을 돕기 위해서 작성되었습니다.  
입학허가를 받은 날부터 포항에 도착하여 Slack Workspace 액세스를 받기 전까지의 step들을 다룹니다.  
Slack 초대를 받은 이후에는, 슬랙 내에 기재 예정인 온보딩 절차를 따르시면 됩니다.  

물론, 별도로 학과에서 요구하는 절차들도 따라주세요.

**Still not sure?** EffL에 오실지, 다른 곳으로 진학하실지 아직 미정이라면 어떤 것도 진행하지 마시기 바랍니다. 결정 이후에 진행해주세요.

{{<color "#b4b4b4" "현 버전은 pre-alpha version으로, 일부 정보가 누락됐을 수 있습니다 😅" >}}

&nbsp; 

#### Before Arrival

{{< details title="**1. GitHub Access**" open=false >}}
[PI에게 메일](mailto:jaeho.lee@postech.ac.kr)을 보내, 사용하시는 GitHub 계정을 알려주세요. 연구실 웹페이지 [repository](https://github.com/effl-lab/effl-lab.github.io)에 collaborator로 추가드릴 예정입니다.

**Git?** Git/GitHub 이용에 익숙하시길 기대합니다 🥹 잘 모르신다면 웹에 튜토리얼이 많으니 공부해두세요 (e.g., [여기](https://docs.github.com/en/get-started/quickstart/set-up-git)).

{{< /details >}}

{{< details title="**2. Present yourself in EffL Webpage**" open=false >}}
연구실 홈페이지 내 서브페이지로 본인의 페이지를 만들어주세요. 만약 본인의 웹페이지가 이미 있는 경우, 링크만 해두셔도 좋습니다.

현재 연구실 홈페이지는 [Hugo](https://gohugo.io)를 사용하고 있으며, Markdown 문서를 작성하는 것 만으로도 개인 소개 서브페이지를 손쉽게 만들 수 있습니다. 사용법은 [튜토리얼](https://gohugo.io/getting-started/quick-start/)을 참고하세요.

대략, 다음 순서를 따라가시면 됩니다.
- Repository의 `content/docs/people/member/` 디렉토리에 자신의 이름으로 된 문서를 추가합니다 (e.g., jaeho.md)
	- 초보자의 경우, 다른 분이 이미 작성하신 문서를 복붙하시면 좋습니다.
- 헤더에서 이름을 수정하고, 내용을 자신을 잘 소개할 수 있는 내용으로 자유롭게 수정해주세요.
	- 이미지 등을 추가하고 싶으신 경우 `assets/` 서브디렉토리를 만들어 저장하시면 될 것 같습니다.
- Repository의 `content/docs/people/members.md`에 자신의 이름을 추가하고, 웹페이지를 링크해주세요.
- 컴퓨터에 Hugo가 설치되어 있는 경우, 정상적으로 웹페이지가 작동하는 것을 확인한 뒤 (예: `hugo server` 커맨드 이후 localhost 접속) 컴파일하여 repository에 업데이트해주세요.

**질문.** 궁금한 사항이 있다거나, 실수로 웹페이지를 터뜨렸다면 [PI에게 메일](mailto:jaeho.lee@postech.ac.kr)로 알려주세요.
{{< /details >}}

{{< details title="**3. Purchase your Computers**" open=false >}}
도착하시자마자 일을 시작하실 수 있게 미리 연구용 컴퓨터를 구입하시기 바랍니다.

**예산.** 2023년 10월 기준, 최대 300만원의 예산을 배정할 예정입니다.

**용도.** 데스크탑/노트북/모니터 구입에 사용하실 수 있고, 키보드/마우스/모니터암 등은 구입이 불가능합니다. 

**소유권.** 학교 소유물이기 때문에 연구용으로만 사용해주시고, 졸업 시 반납하셔야 합니다. 개인용으로 사용하실 노트북은 따로 구비하시길 권합니다.

**추천.** MacBook Pro 혹은 iMac을 구입하시는 것을 강력하게 추천드립니다. 딥러닝서버에서 사용하는 linux 문법에 익숙해지기 좋고, 터미널 사용이 편리하며, 보안과 시스템 안정성이 뛰어나기 때문입니다. 그리고 PI가 앱등이이기 때문에 co-work하기 편합니다 😅

구입하고 싶으신 모델을 결정하고 나서, 견적서를 PI에게 전달해주세요. 연구비로 구입하는 것이기 때문에, 정확한 구입시기와 구매처는 변동이 있을 수 있습니다 (Apple의 경우 교육할인이 아쉽게도 불가능합니다).

{{< /details >}}

{{< details title="**4. Plan for Pohang Life**" open=false >}}
포항의 거주옵션들을 알아보시고 합류일정을 PI에게 메일로 알려주세요.

학기 시작 전 미리 합류하시는 경우에도 기숙사를 이용가능한 경우가 있습니다. 학과사무실을 통해 이용가능한 옵션을 문의해주세요.

**추천.** 재택근무 경험이 많지 않으시다면, 기숙사 이용을 추천드립니다. 이외에도 유강, SK뷰, 효자시장 등에 괜찮은 housing option이 있다고 알고 있습니다. 연구실은 제2공학관에 위치해 있으니 위치 선정에 참고하시기 바랍니다. [네이버 지도](https://naver.me/xxxQFF2Y)
{{< /details >}}

{{< details title="**5. Keep in Touch**" open=false >}}
PI에게 주기적으로 연락을 취해 연구 및 관련 공부를 미리 진행하시면 대학원 생활에서 훨씬 더 많은 것을 얻어가실 수 있습니다.

많은 경우, PI가 몇 가지 미션을 드릴 수 있을 것입니다... 🤔
{{< /details >}}

&nbsp; 

#### After Arrival


{{< details title="**6. Let Jaeho Know**" open=false >}}
[PI에게 메일](mailto:jaeho.lee@postech.ac.kr)을 보내, 무사히 도착했다는 사실과 언제 연구실에 첫 방문을 하실 지 알려주세요.  
보통은 PI와 간단하게 미팅을 한 뒤, PI가 연구실로 모시고 가서 간단하게 소개를 드릴 예정입니다.  

**위치.** PI의 오피스는 제2공학관 407호입니다.

{{< /details >}}

{{< details title="**7. Desk Assignment**" open=false >}}
연구실에 오셔서 자리를 고르세요. 빈 자리 중에서 마음에 드는 곳을 선택하시면 됩니다.  
{{<color "#b4b4b4" "(TODO: 누가 어디 앉는지 기록하는 시스템)" >}}


**위치.** EffL Lab은 제2공학관 404호에 있습니다.

**재배정.** 매년 가을학기 초, 첫번째 Group Meeting에서 재배정을 진행할 예정입니다.
{{< /details >}}

{{< details title="**8. Request Slack Access**" open=false >}}
연구실 Slack이 있습니다. [PI에게 메일](mailto:jaeho.lee@postech.ac.kr)을 보내, 어떤 이메일 계정으로 초대메일을 보내면 되는지 알려주세요.  
{{<color "#b4b4b4" "(TODO: Slack 학생 관리자)" >}}  

**주의.** 연구실 내 소통은 Slack을 이용해주시고, 불가피한 경우를 제외하고 전화/문자/카톡 등은 삼가주세요.

{{< /details >}}

{{< details title="**9. After Getting Slack Access**" open=false >}}
이후의 step들은 Slack 내 온보딩 기능을 활용하여 안내를 할 예정입니다.  
이 기능은 아직까지는 구현되지 않았습니다 ㅠㅠ  
Meanwhile, Office Team Lead (이지운님)을 통해 필요한 것들을 여쭤보세요.

(TODO: 프린터, 와이파이, 연구실 비밀번호, 서버 및 서버실 액세스, 포비스, MS Teams)

{{< /details >}}

