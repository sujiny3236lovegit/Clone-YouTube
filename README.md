# Mobile First Coding - Clone YouTube
---

## 목표(or 목적) :rocket: 
1. 평소 PC버전의 UI를 먼저 구상하곤 했다. 하지만 이번에는 "Mobile First"작업을 시행해 어떻게 하면 반응형까지 만들 수 있을지에 대해 고민해본다. 
1. 디자인을 할때 모바일을 먼저 고려하는 습관을 갖는다. 
2. HTML과 CSS 연습을 통해 이해도를 높인다. 
---
## 개발인원
- 개인 프로젝트

---

## 개발기간
- 11/13 - 11/14

---

## 기술스팩(Tools)
- HTML
- CSS

---

## 아키텍쳐
:sparkles: FRONT-END 디자인패턴: MVC, OOP :sparkles:
- Model : 데이터 상태 관리, 검증, api
- View : ui components, action event emit
- Controller: View 와 Model 에 data 혹은 action 전달

---

## 기능
* 스크롤링
	* 비디오가 고정되어 스크롤해도 비디오의 위치는 고정되어있다.
* 타이틀 
	* 화살표 모양 아이콘을 클릭하면 생략된 동영상의 정보를 모두 확인할 수 있다. 
* 반응형 
  * 특정 크기에서 레이아웃의 재배치가 형성된다. 

---

## 결과물
:sparkles: 영상보기 :sparkles:
[Box model](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing "Box model")

---

## 구동방법
1. `git clone`
1. `npm init`
1. `client` 폴더에서 `npm start` -> 클라이언트 서버 구동
1. `server` 폴더에서 `nodemon` -> 백엔드 서버 구동
