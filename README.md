cat << 'EOF' > README.md
# 🧾 영수증 관리기 (Receipt Manager)

연구실 내 영수증 정리를 자동화하는 간단한 Python & Jupyter 도구입니다.  
파일명을 분석하여 금액·신청자·날짜·내용을 추출하고, Excel 요약표와 그래프를 생성합니다.

## 🚀 주요 기능
- 영수증 파일명 자동 파싱  
- Excel 요약(`receipts_summary.xlsx`) 및 시각화(`expense_by_date.png`, `expense_by_person.png`) 생성  
- 한글 파일명 완벽 지원(macOS NFC 정규화)  
- Jupyter Lab에서 간단히 실행
