# 안드로이드 어플리케이션 세번째 프로젝트

## 1. 간단한 설명
간단한 일기 어플리케이션으로 그날의 감정을 날씨로 표현하여 기록하는 서비스

## 2. 서비스 설명
1) 매일 매일 일기를 쓰는 어플리케이션입니다.
2) 일기를 쓰게 되면 그날의 기분을 날씨 이모티콘 중에서 고릅니다.
3) 또한, 그날의 감정을 최고온도, 최저 온도로 표현해 줍니다.
4) 그렇게 쌓여가는 일기에 기록된 내 감정을 기반으로 전반적인 나의 계절을 이미지로 보여줍니다.

## 3. 프로젝트 기간
2020.07.20 ~ 2020.8.3(안드로이드 마켓 출시 날짜)

## 4. 개발 언어
JAVA

## 5. 활용 서버
서버를 사용하지 않고 안드로이드 내부 데이터를 사용하였습니다.

## 6. 내부 데이터(내장 DB)-1
안드로이드에서 제공하는 SharedPreferences를 사용하였습니다.<br>
사용자 개인 정보를 저장하는데 사용하였습니다.

## 7. 내부 데이터(로컬 DB)-2
NoSQL 데이터베이스를 지향하는 Realm를 사용하였습니다.<br>
사용자가 기록하는 일기를 저장하기 위해 사용하였습니다.

## 8. 이미지 처리
Glide를 사용하였습니다.<br>
날씨 이모티콘 이미지, 계절 이미지를 띄우기 위해 사용하였습니다.

## 9. 앱 이미지
* 홈 화면(전반적 감정을 계절로 표현)<br>
![guide1](https://user-images.githubusercontent.com/17876424/106134052-6104bd80-61a9-11eb-9f8a-17dfecedc943.png)<br>
* 일기 작성 전 날씨 이모티콘 선택<br>
![guide2](https://user-images.githubusercontent.com/17876424/106134191-82fe4000-61a9-11eb-8208-2589036db19a.png)<br>
* 일기 작성 화면<br>
![guide3](https://user-images.githubusercontent.com/17876424/106134236-97423d00-61a9-11eb-8b9d-689a24c9a0ce.png)<br>
* 내 일기 화면<br>
![guide4](https://user-images.githubusercontent.com/17876424/106134258-a32dff00-61a9-11eb-8545-37337b473178.png)<br>

## 10. 전체 이미지
![전체 이미지](https://user-images.githubusercontent.com/17876424/106140400-12a7ec80-61b2-11eb-81a5-19b954f377c6.PNG)

## 11. 마켓 출시 화면
![마켓](https://user-images.githubusercontent.com/17876424/106134449-e5574080-61a9-11eb-9d6a-0d1e8dd8fa94.jpg)<br>
구글플레이 마켓 주소: https://play.google.com/store/apps/details?id=com.aram.weatherdiary
