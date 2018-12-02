# R-code-for-finance
R code for finance <br>
주식, 재무표, 데이터를 위해 만든 repo입니다. 

# 2018.12.01 UPDATE
1. 마감시황 업데이트 되었습니다<br>
- 주말에 지난주 금요일 시황이 뜨도록 수정하였습니다.<br>
- 미국 및 WTI의 금요일 시황은 월요일에 업데이트 됩니다.<br>
- 시황은 인포스탁, 이미지는 네이버를 참고하였습니다 <br>

2. 현재 KRX데이터 및 재무제표 사용이 불가한 상태입니다 (홍콩,중국 제외) <br>
하루빨리 업데이트 하도록 하겠습니다. <br>

# 코드 이용방법
- 홍콩주식과 중국주식은 홍콩재무제표, 중국재무제표를 나타냅니다. <br>
- 중국주식 이용방법 : cn_fs('코드번호') ex) cn_fs('000002') <br>
- 재무재표는 한국재무재표를 나타냅니다. 이용방법 fs('기업명'), ex) kr_fs('삼성전자')
- SUPERTREND는 '코스닥종목'에 사용하지 않은 것을 추천합니다. 야후 파이낸스를 기반으로 데이터를 불러 오는데, 코스닥 종목은 누락된 데이터가 너무 많아 정확한 계산도출이 되지 않습니다. 추후에 한국주식 데이터베이스를 추가하도록 하겠습니다. 
