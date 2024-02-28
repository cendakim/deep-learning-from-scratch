# 2024 봄학기 "빅데이터 응용 보안" - python 프로그래밍 언어 및 딥러닝 개요 
- 본 과목 수강생들이 python 프로그래밍 언어에 대해서 기본적인 사항을 이해하고 있는 것을 전제로 합니다.
- 다만, 아직 익숙치 않은 학생들을 위해 python 언어 및 딥러닝 개요에 대해 설명을 빠르고 효과적으로 진행하기 위해 참고도서의 github repository 를 활용하여 수업을 진행합니다. 
- 참고도서는 아래와 같습니다. 슬라이드 파일을 이용하여 수업이 진행되므로 도서는 구매하지 않아도 무방합니다. 

# 『밑바닥부터 시작하는 딥러닝』

<a href="http://www.yes24.com/Product/Goods/34970929"><img src="https://github.com/WegraLee/deep-learning-from-scratch/blob/master/cover.jpeg" width="150" align=right></a>

:white_check_mark: 책 본문의 수식 및 그림 파일 

* [equations_and_figures.zip](https://github.com/WegraLee/deep-learning-from-scratch/blob/master/equations_and_figures.zip?raw=true)

## 책 미리보기
[issuu](https://issuu.com/hanbit.co.kr/docs/____________________________________38d0e6451f0ddf) | [SlideShare](http://www.slideshare.net/wegra/ss-70456623) | [Yumpu](https://www.yumpu.com/xx/document/view/56594155/-)

## 파일 구성

|폴더 이름 |설명                         |
|:--        |:--                          |
|ch01       |1장에서 사용하는 소스 코드 |
|ch02       |2장에서 사용하는 소스 코드    |
|...        |...                          |
|ch08       |8장에서 사용하는 소스 코드    |
|common     |공통으로 사용하는 소스 코드  |
|dataset    |데이터셋용 소스 코드 |


소스 코드 해설은 책을 참고하세요.

## 요구사항
소스 코드를 실행하려면 아래의 소프트웨어가 설치되어 있어야 합니다.

* 파이썬 3.x
* NumPy
* Matplotlib

※ Python은 3 버전을 이용합니다.

## 실행 방법

각 장의 디렉터리로 이동한 후 파이썬 명령을 실행하세요(**다른 디렉터리에서는 제대로 실행되지 않을 수 있습니다!**).

```
$ cd ch01
$ python man.py

$ cd ../ch05
$ python train_nueralnet.py
```

## 라이선스

이 저장소의 소스 코드는 [MIT 라이선스](http://www.opensource.org/licenses/MIT)를 따릅니다.
상업적 목적으로도 자유롭게 이용하실 수 있습니다.

## 책의 오류

이 책의 오탈자 등 오류 정보는 아래 페이지에서 확인하실 수 있습니다.

http://www.hanbit.co.kr/store/books/look.php?p_code=B8475831198

## 머신러닝/딥러닝 번역 용어표

이 책을 번역하며 정리한 [용어표](https://docs.google.com/spreadsheets/d/1ccwGiC01X-gs3PPcXPUz67W9rS6l994LD4AL18KF1_0)입니다.


---
## 기타 도서 역자의 커멘트는 아래 참조 
:red_circle: **[공지]** 종종 실습용 손글씨 데이터셋 다운로드 사이트( http://yann.lecun.com/exdb/mnist/ )가 연결되지 않습니다.
그래서 예제 수행에 필요한 데이터셋 파일을 /dataset/ 디렉터리에 올려뒀습니다.
혹 사이트가 다운되어 데이터를 받을 수 없다면 아래 파일 4개를 각자의 <예제 소스 홈>/dataset/ 디렉터리 밑에 복사해두면 됩니다. ^__^

* [t10k-images-idx3-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/t10k-images-idx3-ubyte.gz)
* [t10k-labels-idx1-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/t10k-labels-idx1-ubyte.gz)
* [train-images-idx3-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/train-images-idx3-ubyte.gz)
* [train-labels-idx1-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/train-labels-idx1-ubyte.gz)

---

## 시리즈 소개

<a href="https://github.com/WegraLee/deep-learning-from-scratch-3/blob/master/%EB%B0%91%EB%B0%94%EB%8B%A5%20%EC%8B%9C%EB%A6%AC%EC%A6%88%20%EC%86%8C%EA%B0%9C.pdf"><img src="https://github.com/WegraLee/deep-learning-from-scratch-3/blob/master/%EB%B0%91%EB%B0%94%EB%8B%A5%20%EC%8B%9C%EB%A6%AC%EC%A6%88%20%EC%86%8C%EA%B0%9C.png" width=1000></a>

『밑바닥부터 시작하는 딥러닝』 시리즈는 현재 4편까지 출간되었고, 2024년 중으로 5편도 출간될 예정입니다. 5편까지의 핵심 주제와 관계는 대략 다음 그림처럼 정리할 수 있습니다.

<img src="https://github.com/WegraLee/deep-learning-from-scratch-4/blob/master/series overview.png" width="600">

시리즈의 모든 책은 기존 편을 읽지 않았어도 무리가 없도록 꾸려졌습니다. 예를 들어 3편에서 만드는 프레임워크는 작동 원리뿐 아니라 API 형태까지 파이토치와 거의 같습니다. 그래서 3편을 읽지 않았어도 4편을 읽는 데 전혀 무리가 없습니다.

* [❷편의 깃허브 저장소](https://github.com/WegraLee/deep-learning-from-scratch-2)
* [❸편의 깃허브 저장소](https://github.com/WegraLee/deep-learning-from-scratch-3)
* [❹편의 깃허브 저장소](https://github.com/WegraLee/deep-learning-from-scratch-4)

## 선수지식

다음은 역자가 추천하는 선수지식입니다.
<img src="https://github.com/WegraLee/deep-learning-from-scratch-3/blob/master/%EB%B0%91%EB%B0%94%EB%8B%A5%20%EC%84%A0%EC%88%98%EC%A7%80%EC%8B%9D.png" width=1000>

