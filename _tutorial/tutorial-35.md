---
layout: post
title: "[사용팁]x264vfw 외장 코덱 사용하기"
---

오캠은 외장 코덱(VFW)을 지원하며 여기서는 x264 코덱을 사용하는 방법에 대해서 알아봅니다.

x264 코덱은 아래 사이트에서 다운로드 받으실 수 있습니다.

<http://sourceforge.net/projects/x264vfw/>

해당 사이트로 이동하여 다운로드 버튼을 클릭합니다.

![](/images/tutorial_35_img_1.png)

다운로드가 자동으로 시작됩니다.

![](/images/tutorial_35_img_2.png)

설치화면은 다음다음만 누르면 됩니다.

![](/images/tutorial_35_img_3.png)

약관에 동의하세요.

![](/images/tutorial_35_img_4.png)

설치 경로를 지정합니다.

![](/images/tutorial_35_img_5.png)

설치가 완료되었습니다.

![](/images/tutorial_35_img_6.png)

완료를 클릭합니다.

![](/images/tutorial_35_img_7.png)

코덱 설치 후 반드시 오캠을 재실행해야 외장 코덱 목록에서 보실 수 있습니다.

오캠을 재실행 후 오캠 메인 창에서 코덱 버튼을 클릭하고 외장 코덱 메뉴를 클릭합니다.

![](/images/tutorial_35_img_8.png)

외장 코덱 사용하기 체크박스에 체크합니다.

![](/images/tutorial_35_img_9.png)

목록에서 x264vfw - H264/MPEG-4 AVC codec 를 선택합니다.

![](/images/tutorial_35_img_10.png)

그리고 설정 버튼을 클릭해서 코덱에 세부설정을 보도록 하겠습니다.

![](/images/tutorial_35_img_11.png)

다음과 같이 코덱 설정창이 뜨며, 현재 우리는 일반적인 동영상 인코딩이 아닌 화면을 실시간으로 녹화해야 하기 때문에 Preset 에서
Ultrafast를 선택하고 Zero Latency 체크박스에 체크하여 가장 빠르게 인코딩이 되도록 설정하고 OK 버튼을 누릅니다.

( 이 설정방식은 실시간 녹화에 유용하며, 상황에 따라서 알맞게 설정하시면 됩니다. )

![](/images/tutorial_35_img_12.png)

이렇게 설정하신 후 녹화를 하시면 x264 코덱을 사용하여 녹화가 됩니다.

* 게임 녹화의 경우 녹화하려는 게임이 64비트인 경우 x264vfw 설치 시 64비트 버전도 같이 설치해야 되며 ( 기본적으로 x264vfw 설치 시 옵션을 건드리지 않는 이상은 자동으로 설치됩니다. ), 시작 메뉴에서 x264vfw - Configure x264vfw64 를 실행하셔서 위에 설명과 같은 방식으로 설정하시면 됩니다.

* x264vfw 설정에 Keep/Accept only YUV 4:2:0, Keep/Accept only YUV 4:2:2, Keep/Accept only YUV 4:4:4 는 지원하지 않으며 해당 설정 사용 시 녹화가 실패합니다.

