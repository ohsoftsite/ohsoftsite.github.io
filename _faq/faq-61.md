---
layout: post
title: "[FAQ]Error while writing video frame (error=-28) 해결방안"
---

녹화를 하다가 일정시간이 지나면 다음과 같은 오류가 뜰 경우

Error while writing video frame (error=-28)

( 오류코드 번호가 28번 )

녹화 된 동영상 파일이 저장되는 경로의 파일 시스템 포맷이 FAT인 경우 동영상 파일의 크기가 4GB 가 넘어갈 때 이 에러 메세지가 뜨게
됩니다.

( FAT 파일 시스템은 파일의 최대 크기가 4GB까지 입니다. )

사용하고 있는 파일 시스템을 포맷 후에 NTFS로 변경하거나 또는 다른 NTFS 파일 시스템을 사용하고 있는 경로로 오캠의 저장 경로를
변경해야 합니다.

