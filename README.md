![thumbnail](./image/main.png)
[Cascadia Code](https://github.com/microsoft/cascadia-code/)를 기반으로 [NanumSquare Neo](https://campaign.naver.com/nanumsquare_neo/)의 한글 글리프를 병합했습니다. 기본적으로 Cascadia Code에 있는 모든 기능을 지원합니다.

## 구성
- Casquare Code: Ligature를 지원하는 기본 버전입니다.
- Casquare Mono: Ligature를 지원하지 않는 모노스페이스 버전입니다.
- Casquare (Code|Mono) PL: 파워라인 기호를 포함하는 버전입니다.
- Casquare (Code|Mono) NF: Nerd Font 기호를 포함하는 버전입니다.
- Casquare (Code|Mono) (∅|PL|NF) Std: 기본 Cascadia Code와 라틴 글리프의 자폭이 동일하고, 한글 글리프의 자폭이 반각 문자의 두 배인 글꼴입니다.
- Casquare (Code|Mono) (∅|PL|NF) 1080: 기본 Cascadia Code의 라틴 글리프의 자폭이 90%로 축소된 1080이고, 한글 글리프의 자폭이 반각 문자의 두 배인 글꼴입니다.
- Casquare (Code|Mono) (∅|PL|NF) 35: 기본 Cascadia Code와 라틴 글리프의 자폭이 동일하고, 한글 글리프의 자폭이 반각 문자의 5/3배인 Wide 버전의 글꼴입니다.

본래 힌팅을 위해 ttfautohint를 사용하였으나, 합자 등의 부분에서 오토힌팅이 문제를 일으키고 한글과 조화롭게 보이지 않아 배제했습니다. Cascadia Code/나눔스퀘어 네오의 힌팅을 직접 적용할 수 있는 방법이 존재하거나 수동 힌팅을 하지 않는 한 힌팅을 다시 복구할 계획은 없습니다. 이는 [Reflex KR](https://github.com/Cywohoy/ReflexKR)도 마찬가지입니다.

## 갤러리
![image](./image/image.png)

## 라이선스
Casquare Code 시리즈는 SIL Open Font License 1.1에 따라 배포됩니다.

이 프로젝트는 다음의 원본 폰트들을 기반으로 제작되었습니다:
 * Cascadia Code: Copyright (c) 2019 - Present, Microsoft Corporation, with Reserved Font Name Cascadia Code. (OFL 1.1; https://github.com/microsoft/cascadia-code/blob/main/LICENSE)
 * Nanumsquare Neo: Copyright (c) 2010, NAVER Corporation (https://www.navercorp.com/) with Reserved Font Name Nanum, NanumSquareNeo (OFL 1.1; https://help.naver.com/service/30016/contents/18088)

허용 범위
 - 개인 및 상업적 용도: 웹사이트, 인쇄물, 로고, 소프트웨어 등에 자유롭게 사용 가능합니다.
 - 수정 및 재배포: 폰트의 글리프를 수정하거나 다른 폰트와 병합하여 재배포할 수 있습니다.

제한 사항
 - 폰트 파일(.ttf / .otf) 자체를 유료로 판매하는 행위는 엄격히 금지됩니다.
 - 수정 및 재배포 시 원본 폰트 제작자의 저작권 고지문을 반드시 포함해야 합니다.

## 업데이트
### 1.001
- 폰트 굵기 조정
- 한글 글리프를 10% 확대

### 1.002
- 한글 글리프 및 라틴 글리프의 크기 조정
- 힌팅 조정
- 1080 패밀리의 라틴 글리프의 폭 확대

### 1.003
- 힌팅 제거 및 전반적 재조정