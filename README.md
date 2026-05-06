<div align="center">

# 🍳 CookClick

### 레시피 공유 & 식료품 구매 정적 웹사이트

> 요리 레시피를 찾고, 필요한 재료를 한 번에 구매할 수 있는 원스톱 웹 플랫폼

<br>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
![Static](https://img.shields.io/badge/Type-Static%20Web-FF6B6B?style=flat-square)
![Course](https://img.shields.io/badge/웹프로그래밍-기초과정-FFA500?style=flat-square)

<br>

</div>

---

## 📖 프로젝트 소개

**CookClick**은 웹 프로그래밍 기초 과정에서 **HTML과 CSS만으로 제작한 정적 웹사이트**입니다.

바쁜 일상 속에서 레시피를 찾고 재료를 따로 구매해야 하는 번거로움을 해소하고자,
레시피 검색부터 장보기까지 **하나의 플랫폼**에서 해결할 수 있도록 기획·제작했습니다.

<br>

## 💡 기획 의도

| 🕐 시간 절약 | 🛒 편리성 증가 | 👨‍🍳 자신감 UP |
|:---:|:---:|:---:|
| 레시피 검색과 재료 구매를 한 곳에서 | 여러 사이트를 돌아다닐 필요 없이 한 번에 | 소요시간·난이도 표기로 초보자도 쉽게 |

<br>

## 🛠️ 기술 스택

```
HTML5   — 페이지 구조 및 시맨틱 마크업
CSS3    — 레이아웃, 스타일링
```

<br>

## 🗂️ 페이지 구성

| 페이지 | 파일 | 설명 |
|--------|------|------|
| 🏠 **메인** | `index.html` | 베스트·신규 레시피, 오늘의 테마 |
| 🍽️ **레시피 목록** | `recipes/recipe0.html` | 카테고리별 레시피 목록 |
| 🔐 **로그인** | `login.html` | 로그인 페이지 |
| 📝 **회원가입** | `signup.html` · `agree.html` | 약관 동의 + 회원가입 |
| 🛒 **장바구니** | `cart.html` | 장바구니 |
| ✍️ **레시피 작성** | `write.html` | 레시피 업로드 |
| 🎉 **이벤트** | `event.html` | 이벤트 페이지 |
| ❤️ **좋아요** | `like.html` | 좋아요 목록 |
| 👤 **마이페이지** | `mypage/abc.html` | 프로필 |
| 🎟️ **쿠폰** | `mypage/coupon.html` | 쿠폰 목록 |
| 📋 **정보 수정** | `mypage/information.html` | 회원정보 수정 |
| 📞 **고객센터** | `mypage/service-center.html` | 고객센터 |

<br>

## 🍜 레시피 카테고리

각 레시피는 개별 HTML 파일과 단계별 이미지(step1~N.jpg)로 구성되어 있습니다.

| 카테고리 | 레시피 예시 |
|----------|------------|
| 🇰🇷 **한식** | 김치찌개, 된장찌개, 비빔밥, 삼계탕, 잡채, 소불고기 등 |
| 🍜 **일식** | 돈가스, 미소시루, 야키소바, 연어덮밥, 타코야키 등 |
| 🍝 **양식** | 카르보나라, 맥앤치즈, 바베큐폭립, 채끝스테이크 등 |
| 🥗 **야식** | 낙곱새, 두부김치, 오징어순대, 치즈닭갈비 등 |
| 🍱 **중식** | 깐풍기, 꽃빵, 마파두부, 멘보샤, 유린기 등 |
| 🥗 **밑반찬** | 감자두부조림, 깻잎장아찌, 무생채, 장조림 등 |
| 🍰 **디저트** | 바크초콜릿, 수플레팬케이크, 키토티라미수 등 |

<br>

## 📁 프로젝트 구조

```
CookClick/
├── index.html                  # 메인 페이지
├── login.html                  # 로그인
├── signup.html                 # 회원가입
├── agree.html                  # 약관 동의
├── cart.html                   # 장바구니
├── write.html                  # 레시피 작성
├── event.html                  # 이벤트
├── like.html                   # 좋아요
├── header.html                 # 공통 헤더
│
├── main.css                    # 메인 스타일
├── header.css                  # 헤더 스타일
├── menu.css                    # 메뉴 스타일
├── kfood.css                   # 한식 카테고리 스타일
├── cart.css                    # 장바구니 스타일
│
├── images/                     # 공통 이미지
│   ├── header.png / header.jpg
│   ├── profile.PNG
│   ├── 100coupon.png / 30coupon.png
│   ├── 한식 사진/
│   ├── 일식 사진/
│   ├── 양식 사진/
│   ├── 야식 사진/
│   ├── 중식 사진/
│   ├── 밑반찬 사진/
│   └── 디저트 사진/
│
├── iframes/                    # 오늘의 테마 iframe
│   ├── today.css
│   ├── 간편식.html
│   ├── 다이어트간식.html
│   └── 술안주.html
│
├── mypage/                     # 마이페이지
│   ├── abc.html                # 마이페이지 메인
│   ├── coupon.html             # 쿠폰
│   ├── information.html        # 정보 수정
│   ├── service-center.html     # 고객센터
│   └── (css 파일들)
│
└── recipes/                    # 레시피
    ├── recipe0.html            # 레시피 목록
    ├── style.css
    ├── recipe0/                # 레시피 상세 이미지
    ├── 레시피-지민/            # 카테고리별 레시피 목록 페이지
    │   ├── 한식/ 일식/ 양식/ 야식/ 중식/ 밑반찬/
    └── 레시피/                 # 카테고리별 레시피 상세 HTML
        ├── 디저트(html)/
        ├── 야식(html)/
        └── 양식(html)/
```

<br>

## 📅 개발 일정

| 주차 | 내용 |
|------|------|
| 1주차 | 아이디어 구상 |
| 2~3주차 | HTML 마크업 |
| 3~4주차 | CSS 스타일링 |
| 5주차 | 프로젝트 보고서 작성 |
| 6주차 | 테스트 |
| 7주차 | 최종 실행 및 발표 |

> 📆 발표일 : 2024년 6월 13일

<br>

---

<div align="center">

🍽️ *웹 프로그래밍 기초 과정 첫 번째 프로젝트 — HTML & CSS*

</div>
