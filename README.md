# AISL_toy_project: 컴퓨터 비전과 기계학습을 바탕으로 화살표를 인식하여 미로를 탈출하는 라즈베리파이 RC카 제작

### 코드컨벤션

---

### 개발환경

구글 코랩에 yolov4 설치 </br>


참고한 사이트 https://wiserloner.tistory.com/1181 </br>


#### 화살표 이미지 데이터셋 크롤링
`아나콘다 사용--python 3.6, tqdm library 4.56.0, selenium 3.141.0`

---

##### 사용한 코드
https://github.com/ssapsu/arrowImageCrawling

---

##### 사용 프로그램
Fritzing https://drive.google.com/uc?id=15LPVIRv8YhhKqkfJ6TLEI6f84MqwSygq&export=download <br/>

---

##### 라즈베리파이 기본 지식
PWM이란? https://m.blog.naver.com/emperonics/221725399383 <br/>
RPi.GPIO란? https://studymake.tistory.com/498 <br/>
초음파 센서 사용시 딜레이를 주는 이유 https://www.basic4mcu.com/bbs/board.php?bo_table=p2&wr_id=47 <br/>
풀업 저항, 풀다운 저항, 플로팅 https://k96-ozon.tistory.com/59 <br/>
hardware pwm와 software pwm 차이 https://sites.google.com/site/designersfinger/studio-hhjjj/pwm/hardware_pwm <br/>
GPIO 사용법 http://lhdangerous.godohosting.com/wiki/index.php/Raspberry_pi_에서_python으로_GPIO_사용하기 <br/>
GPIO 레지스터에 대한 설명 https://m.blog.naver.com/PostView.nhn?blogId=gwangryr&logNo=220556862760&proxyReferer=https:%2F%2Fwww.google.com%2F <br/>

---

##### 참고 문헌
마크다운 문법 정리 https://heropy.blog/2017/09/30/markdown/ <br/>
딥러닝에 대한 설명이 잘 되어 있는 웹사이트 https://ds-academy.net/chapter-1-introduction-to-dl/ <br/>
이미지 크롤링 참고 https://seopseop911.tistory.com/41 <br/>
데이터 어그멘테이션에 대한 설명 https://www.kakaobrain.com/blog/64 <br/>
YOLO에 대한 설명 https://pgmrlsh.tistory.com/6 <br/>

화살표 이미지 구글 드라이브 링크
https://drive.google.com/drive/folders/1UtckeZgpdl80X9dRA-MnHXorfusuAGhq?usp=sharing, https://drive.google.com/drive/folders/1wgBaBZHvmKd0ZSXdXGiI0sJAUT0ryzaR?usp=sharing <br/>
https://drive.google.com/drive/folders/1UtckeZgpdl80X9dRA-MnHXorfusuAGhq?usp=sharing

윈도우 10 우분투 설치 설명 https://m.blog.naver.com/6116949/221244246623 <br/>
YOLO 우분투 설치 참고한 블로그 https://j-remind.tistory.com/category/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%26%EB%94%A5%EB%9F%AC%EB%8B%9D/YOLO <br/>
-> python.h 을 찾을 수 없어서 일단 보류

YOLO모델을 파이썬으로 구현한 DARKFLOW를 사용해보고자 한다. https://junyoung-jamong.github.io/deep/learning/2019/01/22/Darkflow%EB%A5%BC-%ED%99%9C%EC%9A%A9%ED%95%B4-YOLO%EB%AA%A8%EB%8D%B8-%EC%9D%B4%EB%AF%B8%EC%A7%80-%EB%94%94%ED%85%8D%EC%85%98-%EA%B5%AC%ED%98%84-in-windows.html <br/>
