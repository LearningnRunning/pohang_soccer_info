# ⚽ 포항 축구 구장 대진표

2026 시즌 포항 축구 구장 대진표를 확인하고 팀별 일정·구장 이용 통계를 볼 수 있는 Streamlit 앱입니다.

## 기능

- **이번 주 구장 현황**: 월별 선택, 구장별 팀 배치, 휴식 팀 표시
- **팀별 경기 현황**: 팀 선택 시 전체 일정 테이블
- **구장 이용 통계**: 팀별 경기 수, 구장별 사용 횟수, 공정성 분석

## 실행 방법

```bash
# uv로 가상환경 생성 및 의존성 설치
uv sync

# 앱 실행
uv run streamlit run pohang_soccer_info.py
```

또는 기존 방식:

```bash
pip install -r requirements.txt
streamlit run pohang_soccer_info.py
```

## 기술 스택

- Python 3
- Streamlit
- Pandas, Plotly
- kr_holidays (한국 공휴일)

## 라이선스

MIT
