# personalized-color-app

퍼스널 컬러 진단 모델을 통한 개인화 앱 서비스의 구현 — 2024년도 학술제

## 폴더 구조

```
docs/
  poster.pptx                  학술제 포스터
  lab-presentation-2024.pptx   2024 학술제 연구실 발표 자료
content/
  personal-color-descriptions.txt   퍼스널 컬러(봄·여름·가을·겨울)별 설명 문구
design/
  app-icon.png                 앱 아이콘
  screens/                     페이지 전체 화면 (메인, 촬영, 사진 확인, 결과, 옷 선택)
  components/                  화면별 구성 요소 (배경, 버튼, 팔레트 등)
  clothes/
    tops/                      상의 아이콘 ({계절}-{종류}-{번호}.png)
    bottoms/                   하의 아이콘
  source/                      Clip Studio 원본 파일 (.clip)
```

## 파일 이름 규칙

| 한글 | 영문 |
| --- | --- |
| 봄 / 여름 / 가을 / 겨울 | spring / summer / autumn / winter |
| 긴팔티 / 목티 / 반팔티 / 셔츠 | longsleeve / turtleneck / tshirt / shirt |
| 바지 / 반바지 / 스커트 / 미니스커트 | pants / shorts / skirt / miniskirt |
| 메인 / 사진 촬영하기 / 사진 확인 / 결과 / 옷 선택 | main / camera / photo-confirm / result / outfit-select |
