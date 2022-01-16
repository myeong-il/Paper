# 청와대 국민청원 게시판과 포털사이트(네이버, 다음) 뉴스기사 키워드 분석 및 감정분석

## Description
#### 청와대 국민청원 게시판과 '국민청원'을 키워드로 검색한 뉴스기사들을 수집하여 당시 사회적 이슈를 분석 및 국민청원 게시판 대비 뉴스기사들의 감정상태 예측

## 데이터 수집
+ 2021년 1월 4일 ~ 2021년 4월 30일 까지 게시된 데이터 수집
+ 청와대 국민청원 게시판
+ '국민청원'으로 검색된 네이버와 다음 뉴스기사

## Contents

### 분석내용
+ 청와대 국민청원 게시판과 뉴스기사를 크롤링을 통해 수집
+ 텍스트 데이터 전처리 및 한국어 감성사전을 이용한 데이터 라벨링
+ 청원내용과 기사내용을 이용한 키워드 분석
+ LSTM모델을 통한 기사내용의 감정 예측
