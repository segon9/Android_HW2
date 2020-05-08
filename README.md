# SOPT 2주차 - 기본과제1,2

### 실습 결과 사진
![KakaoTalk_20200508_155616071_01](https://user-images.githubusercontent.com/63635840/81379768-a4635b80-9144-11ea-8f60-a38abcb7b2d8.jpg)
![KakaoTalk_20200508_155616071_02](https://user-images.githubusercontent.com/63635840/81379771-a5948880-9144-11ea-8273-554b44875be3.jpg)
![KakaoTalk_20200508_155616071_03](https://user-images.githubusercontent.com/63635840/81379772-a62d1f00-9144-11ea-9d34-460804dbaf8c.jpg)
![KakaoTalk_20200508_155616071_04](https://user-images.githubusercontent.com/63635840/81379773-a62d1f00-9144-11ea-97d6-ce35a19850d1.jpg)

### Recyclerview의 Itemdecoration이란?
#### Recyclerview 내부에 있는 추상 클래스로 Recyclerview 내의 item들을 꾸미는 역할을 한다. 그 중 이번 실습에선 item 사이를 나누고 구분하는 divider기능으로 사용했다.
#### 사용방법 : ItemDecoration 클래스를 상속할 클래스를 정의하고, item의 어디를 기준으로 divide할지 결정한다. 클래스 정의 후, Itemdecoration을 적용 할 fragment에 fragment명.addItemDecoration(정의한 클래스명(기준선 너비)) 한 줄을 추가한다.

### Recyclerview의 clipToPadding이란?
#### user가 스크롤을 하는 경우 패딩공간을 활용한다면 뷰를 더 넓게 활용할 수 있고, 조금 더 사용하기 편하게 해준다.
#### clipToPadding 옵션을 사용할 xml에서 해당 view에 android:clipToPaddin="false"을 선언하여 사용한다. 
#### Layout에 padding 값을 10을 줬다고 가정했을 때 위, 아래로 10dp만큼의 공간이 생기는데, clipToPadding = false를 할 경우 10dp 만큼의 padding 공간에도 view를 볼 수 있다.
