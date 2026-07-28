# 일별 CSV 대시보드 샘플

## 구조
- index.html
- source/manifest.csv
- source/YYYY-MM-DD.csv

## 일별 CSV 형식
date,temperature,humidity,pressure,event_count,processing_count

새 파일을 추가할 때:
1. source/YYYY-MM-DD.csv 추가
2. source/manifest.csv 마지막 줄에 YYYY-MM-DD,YYYY-MM-DD.csv 추가
