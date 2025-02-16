---
layout: post
title: "[FAQ]녹화 시작 시 The endpoint device is already in use. 에러가 뜨는 경우"
---

이 경우는 보통 Asio4all을 사용하는 DAW가 실행중일 경우( 예를 들어, FL Studio ) 시스템의 오디오를 독점하게 되는데 이
때 해당 프로그램 외에 다른 프로그램은 소리 재생이나 녹음이 불가능한 상태가 되기 때문에 발생합니다.

만약 Asio4all을 사용하는 경우 해당 프로그램에서 재생장치를 Asio4all로 사용하지 마시고 "주 사운드 드라이버"같은 장치로
변경하시면 정상적으로 녹화가 가능합니다.

예를 들어, FL Studio 12.0의 경우 Options - Audio Settings 에 들어가셔서 아래처럼 "주 사운드 드라이버"로
설정하시고 재생을 하면 녹음이 가능합니다.

![](/images/faq_49_img_1.png)

부득이하게 DAW 사용 시 Asio4all을 반드시 사용하는 경우는 미디 건반의 레이턴시 등의 문제 때문에 사용해야 하는데 이 때는 작업
시에만 Asio4all을 사용하고 작업이 끝나고 녹화 시에 DAW에서 재생 장치를 DirectSound로 변경하여 Asio4all을
중지시키고 녹화를 해야합니다.

