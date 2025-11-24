# 쿠팡 쉽먼트 ->사방넷 PDF 자동화 및 업무설명

## 1. 쿠팡 써플라이 허브 접속
   - https://supplier.coupang.com
   - Home>물류>쉽먼트
     - <img src="https://i.ibb.co/DfPdkJBs/Snipaste-2025-11-24-15-53-58.png" alt="Snipaste-2025-11-24-15-53-58" border="0">
   - 쉽먼트>택배 쉽먼트에서 [내역서]를 클릭하면 PDF 자동 다운로드
     - <img src="https://i.ibb.co/39g3wFKT/Snipaste-2025-11-24-16-17-17.png" alt="Snipaste-2025-11-24-16-17-17" border="0">
   - PDFS는 예)shipment_ManiFest_document(41301642)_2025_11_20.pdf 제공
   - 로그인 및 파일 다운로드 자동화는
       - 2차 인증을 하고 있어 사실상 어려움
## 2. 다운로드 받은 PDF를 지정한 폴더로 이동
   - 담당자가 지정한 폴더로 PDF 파일들을 이동
   - 쉽먼트 현황 [자동화 리스트.xlsx] 파일을 열고
   - 해당 표에 [오른쪽 마우스] -> 새로고침
   - 엑셀의 [파워쿼리]를 사용하여 데이터를 자동으로 가져오는 구조임
   - 해당 표(데이터)가 자동 업데이트 됨
## 3.  데이터를 피벗 및 피벗 차트로 활용
   - 데이터는 PDF 품질이 제각각으로 일정하게 엑셀로 들어오지 않음
   - 예)
   - <img src="https://i.ibb.co/X1w9v0v/Snipaste-2025-11-24-16-23-19.png" alt="Snipaste-2025-11-24-16-23-19" border="0">
   - 데이터 항목
       - 쉽먼트번호
       - 쉽먼트 바코드
       - 물류센터
       - 박스번호
       - 택배 송장번호
       - SKU 이름
       - SKU ID
       - SKU Barcode
       - 상품이름
       - 옵션
       - 수량
   - SKU ID를 조회하여 상품명과 옵션을 가져옴
   - <img src="https://i.ibb.co/X1w9v0v/Snipaste-2025-11-24-16-23-19.png" alt="Snipaste-2025-11-24-16-23-19" border="0">
   - 옵션은 색상+사이즈로 가져오는데 사방넷은 1개만 필요하여 [색상+사이즈] 조합으로 재구성
     - <img src="https://i.ibb.co/4cVKffR/Snipaste-2025-11-24-14-50-58.png" alt="Snipaste-2025-11-24-14-50-58" border="0">
     - <img src="https://i.ibb.co/dJKYjTrN/Snipaste-2025-11-24-16-22-26.png" alt="Snipaste-2025-11-24-16-22-26" border="0">
   - 엑셀에서 XLOOKUP으로 재분류 과정을 거침
