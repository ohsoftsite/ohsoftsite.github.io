---
layout: post
title: "[FAQ]오캠을 설치 할 때 Failed to get path of 64-bit Common Files directory 에러가 나는 경우 해결방안"
---

키보드의 Windows Key + R 단축키를 누르면 실행창이 뜨며, regedit 이라고 입력합니다.

그리고 다음 영상처럼 따라하시면 됩니다.

<https://youtu.be/6GyJV5SgZsY>

영상에서 나오는 추가해야할 레지스트리 키 값은 다음과 같습니다.

CommonFilesDir = C:\Program Files\Common Files

ProgramFilesDir = C:\Program Files

