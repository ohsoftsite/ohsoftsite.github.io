---
layout: post
title: "[사용법]오캠 세부설정하기 - 저장"
---

오캠 메인 메뉴의 도구 - 옵션을 클릭 시 저장 카테고리 설정에 대해서 알아봅니다.

![](/images/tutorial_21_img_1.png)

저장 경로는 기본적으로 윈도우 10을 기준으로 "내 PC-문서-oCam" 폴더로 설정되어 있으며, 녹화, 녹음, 캡처를 하게 되면 모두 이
경로에 저장되게 됩니다.

저장 경로는

![](/images/tutorial_21_img_2.png)

버튼을 클릭하면 변경이 가능합니다.

저장하려는 파일 이름은 미리 정의 된 형식 및 사용자가 지정한 형식에 따라 저장되며 기본적으로
"<Prefix>_<YYYY_MM_DD_HH_NN_SS_Z>" 로 설정됩니다.

파일이름의 형식은 마찬가지로

![](/images/tutorial_21_img_3.png)

버튼을 클릭하여 변경할 수 있으며

![](/images/tutorial_21_img_4.png)

버튼을 클릭하면 미리 정의 된 형식들을 볼 수 있습니다.

![](/images/tutorial_21_img_5.png)

도움말 메뉴 아이템을 클릭하시면 형식에 대한 더 자세한 정보를 볼 수 있으며 다음과 같습니다.

( 2016년06월16일11시29분49초902밀리세컨드에 도움말 메뉴 아이템을 클릭했을 때 )

<Y> = 16

<YY> = 16

<YYYY> = 2016

<M> = 6

<MM> = 06

<MMM> = 6

<MMMM> = 6월

<D> = 16

<DD> = 16

<DDD> = 목

<DDDD> = 목요일

<DDDDD> = 2016-06-16

<DDDDDD> = 2016년 6월 16일 목요일

<C> = 2016-06-16 오전 11:29:49

<H> = 11

<HH> = 11

<N = 29

<NN> = 29

<S> = 49

<SS> = 49

<Z> = 902

<ZZZ> = 902

<T> = 오전 11:29

<TT> = 오전 11:29:49

<AM/PM> = AM

<a/p> = a

<ampm> = 오전

<Prefix> = 녹화

<ProgramName> = oCam

<UserID> = 사용자이름

<DisplayUserName> =

<#> = 1

<##> = 01

<###> = 001

파일 이름에 대한 형식이 일부 사용자에게 어렵게 느껴질 수 있는데 몇 가지 예를 들어보겠습니다.

\- 파일 이름이 <Prefix>_<#> 이라면 <Prefix>는 머릿글자이며, #은 일련번호입니다.

머릿글자는 녹화를 하면 녹화, 녹음을 하면 녹음, 캡처를 하면 캡처로 대체되며, #은 일련번호로 대체됩니다.

예를 들어, 화면을 녹화완료하면 녹화_1 이라는 파일이 생성됩니다. ( 단, 오캠 저장 폴더에 비슷한 형식을 가진 파일이 없을 경우 )

그리고 다시 녹화를 하면 녹화_2라는 이름으로 파일이 생성됩니다. 일련번호가 2가 된 이유는 녹화_1이라는 파일의 이름이 이미 존재하고 있기
때문입니다.

\- 파일 이름이 <ProgramName>_<#> 이라면 <ProgramName>은 녹화를 시작하는 프로그램 이름을 나타내며, 일반적인 화면
녹화 시 oCam이라는 이름으로 대체되고, <#>은 이전과 마찬가지로 일련번호 형태로 숫자가 붙습니다.

단, 게임을 녹화할 경우 게임 프로그램내에서 녹화가 시작되기 때문에 게임의 실행파일 이름으로 생성됩니다.

\- 파일 이름이 <dddddd>_<#> 이라면 dddddd는 지역화 된 날짜를 의미하는데 한국어 운영체제를 사용할 때 이 글을 작성하고
있는 현재 날짜인 2016년 6월 16일 목요일로 대체되게 되며 #은 일련번호가 들어갑니다.

지역화 된 날짜는 운영체제의 언어 설정에 따라서 다릅니다. 즉, 영문 OS에서는 다르게 표시되며 운영체제에 내장 된 형식을 사용하고
있습니다.

\- 파일 이름이 나의_<#>_번째_<Prefix>_파일 이라면 녹화 시 나의_1번째_녹화_파일 이라는 이름으로 파일이 생성되게 되며,
녹화를 다시 하면 나의_2번째_녹화_파일로 파일 이름이 생성됩니다.

\- 파일 이름이 <UserID>는(은) <ProgramName>(이)라는 게임을 <DDDDDD>날에 <Prefix>를(을) 하였다. 일
경우 "고급개발자는(은)LocalDeformablePRT(이)라는 게임을 2016년 6월 16일 목요일날에 녹화를(을) 하였다." 로 생성
될 수 있습니다. <> 안에 있는 내용은 무엇을 녹화하느냐에 따라 다릅니다.

일련번호 시작은 <>안에 들어간 #으로 설정할 수 있는 일련번호 시작번호를 나타냅니다.

