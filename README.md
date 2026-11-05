# 퍼스널 컬러 진단 모델을 통한 개인화 앱 서비스

2024년 CS LAB 학술제 프로젝트의 **디자인 자산과 발표 자료**를 모은 저장소입니다. 얼굴 사진으로 퍼스널 컬러(봄·여름·가을·겨울)를 진단하고, 결과 계절에 맞는 옷 조합을 보여 주는 앱을 목표로 했습니다.

앱 코드(Android, Java)와 모델 파일(ONNX)은 팀 저장소 [dbehdrbs0806/CSPersonal_Color](https://github.com/dbehdrbs0806/CSPersonal_Color)에 있으며, 이 저장소에는 코드가 없습니다.

## 포함된 것

| 경로 | 내용 |
|---|---|
| `docs/poster.pptx` | 학술제 포스터 |
| `docs/lab-presentation-2024.pptx` | 2024 학술제 연구실 발표 자료 |
| `content/personal-color-descriptions.txt` | 계절별 퍼스널 컬러 설명 문구 |
| `design/app-icon.png` | 앱 아이콘 |
| `design/screens/` | 화면 시안 8장 (메인, 촬영, 사진 확인, 결과, 옷 선택) |
| `design/components/` | 화면 구성 요소 26개 (배경, 버튼, 팔레트 등) |
| `design/clothes/tops/`, `bottoms/` | 상의·하의 아이콘 각 48개 (`{계절}-{종류}-{번호}.png`) |
| `design/source/` | Clip Studio 원본 파일 (`.clip`) |

## 파일 이름 규칙

| 한글 | 영문 |
| --- | --- |
| 봄 / 여름 / 가을 / 겨울 | spring / summer / autumn / winter |
| 긴팔티 / 목티 / 반팔티 / 셔츠 | longsleeve / turtleneck / tshirt / shirt |
| 바지 / 반바지 / 스커트 / 미니스커트 | pants / shorts / skirt / miniskirt |
| 메인 / 사진 촬영하기 / 사진 확인 / 결과 / 옷 선택 | main / camera / photo-confirm / result / outfit-select |

## 기여

팀 프로젝트입니다. 이 저장소의 디자인 자산과 문구는 이은정이 올렸고, 팀 저장소에는 이은정 계정으로 모델 파일(`ML/best (2).onnx`)을 올린 커밋이 1건 있습니다. 모델 학습과 앱 구현의 담당 범위는 확인 후 보완할 예정입니다.
