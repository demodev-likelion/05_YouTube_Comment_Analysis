# 05_YouTube_Comment_Analysis

Claude Cowork / Claude for Chrome 강의 Chapter 5 결과물입니다. 유튜브 댓글을 수집하고 감정 분석 및 시각화 대시보드 실습에 사용하는 CSV 데이터를 보관하는 자료형 레포입니다.

## 프로젝트 개요

- 목적: 감이 아닌 데이터 기반 의사결정을 위해 유튜브 댓글 데이터를 수집, 분석, 시각화하는 실습
- 학습 포인트: Claude for Chrome, 댓글 수집, CSV 추출, 감정 분류, 아티팩트 대시보드 생성
- 원본 자료 위치: Chapter 5 강의자료

## 포함 파일

```text
data/youtube_comments_supabase_mcp_75.csv
```

## 주요 결과물

- `youtube_comments_supabase_mcp_75.csv`: 유튜브 댓글 수집 및 감정 분석 실습용 CSV 데이터

## 활용 방법

1. CSV 파일을 Claude 또는 Cowork에 업로드합니다.
2. 댓글 감정 비율, 좋아요 분포, 주요 키워드, 시간대별 반응을 분석하도록 요청합니다.
3. 분석 결과를 HTML 아티팩트 대시보드로 시각화합니다.

## 예시 프롬프트

```text
첨부한 유튜브 댓글 CSV를 분석해서 긍정/부정/중립 비율, 좋아요가 많은 댓글, 반복적으로 등장하는 키워드, 시간대별 댓글 흐름을 요약해줘.
마지막에는 비개발자도 볼 수 있는 HTML 대시보드 형태로 시각화해줘.
```

## 강의 활용 포인트

이 레포는 Chapter 5에서 Claude for Chrome과 Cowork를 활용해 웹 데이터를 수집하고, CSV 기반 분석 결과를 아티팩트로 시각화하는 과정을 복습할 때 사용합니다.
