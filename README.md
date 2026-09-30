# 삼성전자 DART 재무분석

삼성전자(005930)의 OpenDART 공시를 기반으로 2016~2025년 10개년 연결 재무데이터를 수집하고 재무비율을 분석합니다.

## 분석 기준
성장성, 수익성, 현금흐름, 재무안정성, 활동성, 자본효율 지표를 동일한 기준으로 계산합니다.

## 데이터 출처
- 금융감독원 DART / OpenDART
- 회사 고유번호: `00126380`
- 종목코드: `005930`

## 실행
1. GitHub Actions Secret에 `DART_API_KEY` 등록
2. GitHub Actions에서 `DART data update and GitHub Pages dashboard` 실행
3. 생성된 GitHub Pages에서 대시보드 확인

API 키는 저장소에 직접 저장하지 않습니다.
