---
layout: post
title: "[FAQ]오캠으로 마인크래프트 녹화를 시작하자마자 게임이 튕기는 경우 ( 엔비디아 그래픽카드 )"
---

최근 배포 된 엔비디아 드라이버 ( 378.49 ) 버전 ( 그 외에 버전도 포함 될 수 있음 ) 설치 시 java로 만들어진 앱에서 쿠다를
초기화하는 함수를 호출하면 ( cuInit, Stack cookie instrumentation code detected a stack-
based buffer overrun. ) 크래시가 나는 버그가 있습니다.

이것은 오캠의 버그는 아니며 쿠다를 사용하는 모든 앱에 다 적용됩니다.

최신 버전의 378.66 이상의 드라이버를 설치하시면 해결됩니다.

