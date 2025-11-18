# 레포에 맞는 NAS 고르기
## 주요 사양 비교

| 항목 | **DS925+** | **DS425+** | **DS1525+** |
|------|------------|------------|-------------|
| 드라이브 베이 | 4 (최대 9, DX525 확장 시) | 4 | 5 (최대 15, DX525 2개 확장 시) |
| CPU | AMD Ryzen V1500B (4코어, 2.2GHz) | Intel Celeron J4125 (4코어, 2.0~2.7GHz) | AMD Ryzen V1500B (4코어, 2.2GHz) |
| 메모리(기본/최대) | 4GB DDR4 ECC / 32GB | 2GB DDR4 / 6GB | 8GB DDR4 ECC / 32GB |
| M.2 NVMe SSD 슬롯 | 2개 | 2개 | 2개 |
| 네트워크 | 2 x 2.5GbE | 1 x 2.5GbE, 1 x 1GbE | 2 x 2.5GbE, PCIe Gen3 x |
| 확장성 | DX525 1개(최대 9베이) | 확장 불가 | DX525 2개(최대 15베이) |
| SMB 최대 동시 연결 | 40 | 10 | 40 |
| SMB HDD 순차 읽기/쓰기 | 525 / 564 MB/s | 282 / 283 MB/s | 696 / 862 MB/s |
| 지원 RAID | SHR, Basic, JBOD, RAID 0/1/5/6/10 | SHR, Basic, JBOD, RAID 0/1/5/6/10 | SHR, Basic, JBOD, RAID 0/1/5/6/10 |
| 공식 파일 프로토콜 | SMB, AFP, NFS, FTP, WebDAV, Rsync | SMB, AFP, NFS, FTP, WebDAV, Rsync | SMB, AFP, NFS, FTP, WebDAV, Rsync |
| 로컬 계정/공유폴더 | 512 / 128 | 512 / 128 | 1,024 / 256 |
| 전력 소모(액세스/대기) | 37.9W / 12.3W | 28.3W / 6.1W | 44.6W / 13.6W |
| 크기/무게 | 166×199×223mm / 2.26kg | 166×199×223mm / 2.18kg | 166×230×223mm / 2.67kg |
| 보증 | 3년(최대 5년 연장 가능) | 3년(최대 5년 연장 가능) | 3년(최대 5년 연장 가능) |
|다나와 최저가| 789,000원 | 777,990원 | 999,000원 | 

## 파일서버 용도별 특징 및 추천

### DS1525+
- 가장 강력한 성능  
  - SMB 동시 연결 40개  
  - HDD: 696/862MB/s  
  - SSD: 1,181/1,179MB/s  
- 확장성 우수: 최대 15베이  
- 8GB ECC 기본 탑재(최대 32GB)  
- 2.5GbE 듀얼 + 10GbE 업그레이드 지원  
- **대규모·고성능·다수 사용자 환경에 최적**

### DS925+
- 균형 잡힌 성능  
  - SMB 동시 연결 40개  
  - HDD: 525/564MB/s  
- DX525 확장으로 최대 9베이  
- 4GB ECC 기본(최대 32GB)  
- **중소규모 사무실, 팀 단위 파일서버에 적합**

### DS425+
- 기본 파일 서버 용도  
  - SMB 동시 연결 10개  
  - HDD: 282/283MB/s  
- 2GB 메모리(최대 6GB)  
- 확장 불가  
- **소규모 사무실, 가정용에 추천**

## 결론 및 선택 가이드

1. **동시 접속 많음 / 고속 전송 / 확장성 중요 → DS1525+**
2. **가성비 + 준수한 성능 + 확장성 → DS925+**
3. **소규모 / 예산 중시 → DS425+**

- https://www.synology.com/ko-kr/products/DS925+
- https://www.synology.com/ko-kr/products/DS425+
- https://www.synology.com/ko-kr/products/DS1525+
