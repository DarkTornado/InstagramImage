# Instagram Image Downloader

© 2021 Dark Tornado, All rights reserved.

* 인스타그램에 있는 사진을 뜯어와보자
* 않이 우클릭해서 다운하는거 웨않댄돼??

## 대충 분석한 것
* F12 눌러서 뒤적거리면 사진 url이 나온다.
* 그런데, 비동기로 불러오는지 직접 긁으면 사진이 안보인다.
* 단, 가장 앞에 있는 사진은 미리보기 이미지로 되어있어서 접근할 수 있다.

## 일단 구현된 것
* 이미지 하나만 다운로드 하기
