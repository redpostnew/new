# 레드포스트 NAS
## NAS(Network Attached Storage)

**NAS**는 네트워크에 연결된 대용량 저장 장치로, 인터넷을 통해 언제 어디서나 접속 가능한 **개인용 클라우드 서버**임.

---

### 1. 주요 특징 및 기능
* **원격 접속:** 장소에 구애받지 않고 스마트폰, 노트북 등으로 파일 접근 및 편집 가능함.
* **대용량 확충:** 다수의 HDD 슬롯을 통해 테라바이트(TB) 단위의 저장 공간 확보 용이함.
* **자동 백업:** 모바일 사진 및 PC 데이터를 설정된 주기에 따라 자동 저장함.
* **데이터 공유:** 링크를 통한 대용량 파일 전송 및 팀 단위 공동 작업 환경 제공함.
* **스트리밍:** 저장된 미디어(영화, 음악)를 스마트 TV나 태블릿에서 실시간 재생함.

### 2. 서비스 비교 (클라우드 vs NAS)

| 구분 | 퍼블릭 클라우드 (구글, iCloud) | 개인용 NAS |
| :--- | :--- | :--- |
| **비용** | 월간/연간 구독료 지속 발생 | 초기 장비 구매 비용 발생 (유지비 저렴) |
| **용량** | 추가 용량 비례 비용 상승 | 하드디스크 추가로 자유롭게 확장 가능함 |
| **보안** | 업체 서버에 의존함 | 사용자가 직접 물리적 보관 및 관리함 |
| **관리** | 업체에서 일괄 관리함 | 초기 설정 및 유지보수 관리 필요함 |

### 3. 주요 활용 대상
* 스마트폰 저장 공간 부족으로 실시간 사진 백업이 필요한 경우
* 클라우드 서비스의 고정 지출 비용을 절감하고자 하는 경우
* 대용량 미디어 라이브러리를 구축하고 스트리밍하려는 경우
* 업무용 데이터의 보안 유지 및 팀 간 빠른 파일 공유가 필요한 경우

------

## 탐색기에 NAS 폴더 넣기 -1
### raidrive 설치
1. https://www.raidrive.com/
2. 컴퓨터 OS에 맞는 버전을 설치
3. NAS 연결 방법
<img src="https://i.ibb.co/ZzXtPYJG/Snipaste-2025-12-05-11-26-30.png" alt="Snipaste-2025-12-05-11-26-30" border="0">

<img src="https://i.ibb.co/JR8xSf6v/Snipaste-2025-12-05-11-26-50.png" alt="Snipaste-2025-12-05-11-26-50" border="0">

<img src="https://i.ibb.co/SX2TcCbP/Snipaste-2025-12-05-11-27-30.png" alt="Snipaste-2025-12-05-11-27-30" border="0">


* 추가할 주소: 211.252.91.167
* 포트: 5006
* 계정: NAS ID와 비밀번호 입력 + 항상 로그인 체크
  
----
## 탐색기에 NAS 폴더 넣기 -2
1. <img src="https://i.ibb.co/C5w6GSDV/2026-01-13-13-34-40.png" alt="2026 01 13 13 34 40" border="0">
2. <img src="https://i.ibb.co/bRWCmBKG/Snipaste-2026-01-13-13-23-20.png" alt="Snipaste 2026 01 13 13 23 20" border="0">
3. <img src="https://i.ibb.co/SXjDTtzJ/Snipaste-2026-01-13-13-23-52.png" alt="Snipaste 2026 01 13 13 23 52" border="0">

* 추가할 주소: https://redpost.myds.me:5006
* 로그인할 때 다시 연결, 다른 자격증명을 사용하여 연결 모두 체크
* NAS ID와 비밀번호 입력 + 항상 로그인 체크

-------
## 처음 접속하실 때에는 비밀번호를 변경해야 합니다
- ID는 이름
- 초기 비밀번호는 ****

## File Station
- Dropbox <-> NAS와 실시간 동기화
- 중국직원: Redpost
- 한국직원: 한국사무실

## 비밀번호를 잃어버렸을 경우
- NAS 로그인 페이지에 표시되는 '패스워드를 잊으셨습니까?'를 클릭 >사용자 이름 입력 > 
- 비밀번호 패스워드 재설정 링크가 포함된 이메일이 발송됩니다.
- 이메일이 가지 않는다면, SMTP 이메일 알림을 활성화했는지 확인 → 제어판 > 알림 > 이메일
- 관리자가 사용자 비밀번호를 재설정했을 경우 사용자가 다시 패스워드를 수정해야 함
- 비밀번호 설정하는 강도는 우선 약하게 했음

## 사용자 그룹
| #  | 이름  | 이메일                    | 팀이름       | 그룹1 | 그룹2           |
| -- | --- | ---------------------- | --------- | --- | ------------- |
| 1  | 조선미 | ceo@redpost.kr         | 대표        | 한국  | CEO           |
| 2  | 이효원 | md@redpost.kr          | 영업기획팀     | 한국  | 영업기획팀         |
| 3  | 오혜미 | hmjk1120@naver.com     | 영업기획팀     | 한국  | 영업기획팀         |
| 4  | 이영래 | book@redpost.kr        | 운영팀       | 한국  | 운영팀           |
| 5  | 서동욱 | planetplama@redpost.kr | 물류팀       | 한국  | 물류팀           |
| 6  | 조미선 | hami99999@naver.com    | 물류팀       | 한국  | 물류팀           |
| 7  | 두효영 | 358830806@qq.com       | 중국 사무실 주관 | 중국  | 중국사무팀         |
| 8  | 강효동 | 465084159@qq.com       | OS        | 중국  | 중국사무팀         |
| 9  | 고원  | 875004125@qq.com       | 중국 실장     | 중국  | COO,중국사무팀,창고팀 |
| 10 | 우청양 | 1918969350@qq.com      | 중국 사무실 직원 | 중국  | 중국사무팀         |
| 11 | 원명기 | 835792110@qq.com       | 중국팀 구매 담당 | 중국  | 중국사무팀         |
| 12 | 小金  | 475820252@qq.com       | CS        | 중국  | 중국사무팀         |
| 13 | 郑宪顺 | 1372293056@qq.com      | 出口资料      | 중국  | 중국사무팀         |
| 14 | 曹华丽 | 1083290525@qq.com      | 仓库职员      | 중국  | 창고팀           |
| 15 | 丛海静 | 1421788227@qq.com      | 仓库职员      | 중국  | 창고팀           |
| 16 | 李丹丹 | 434956874@qq.com       | 仓库职员      | 중국  | 창고팀           |
| 17 | 宋修超 | 1436717127@qq.com      | 仓库职员      | 중국  | 창고팀           |
| 18 | 宋亚群 | 1207875252@qq.com      | 仓库职员      | 중국  | 창고팀           |
| 19 | 魏习习 | 695328864@qq.com       | 仓库班长      | 중국  | 창고팀           |
| 20 | 许志江 | 784275778@qq.com       | 仓库职员      | 중국  | 창고팀           |
| 21 | 王妍妍 | 1069434440@qq.com      | 仓库职员      | 중국  | 창고팀           |
| 22 | 姜静  | j18263119698@qq.com    | 仓库职员      | 중국  | 창고팀           |
| 23 | 邱强  | 1038397692@qq.com      | 仓库职员      | 중국  | 창고팀           |
| 24 | 최승복  | 15698201588@163.com     | 중국 사무실       | 중국  | 중국사무팀         |

# 자료설명



<img src="https://i.ibb.co/ccT8d0gT/Redpost-NAS-Manual-01.png" alt="Redpost-NAS-Manual-01" border="0">
<img src="https://i.ibb.co/Q7TjGvNy/Redpost-NAS-Manual-02.png" alt="Redpost-NAS-Manual-02" border="0">
<img src="https://i.ibb.co/QjP9qbg0/Redpost-NAS-Manual-03.png" alt="Redpost-NAS-Manual-03" border="0">
<img src="https://i.ibb.co/XfN0QYgq/Redpost-NAS-Manual-04.png" alt="Redpost-NAS-Manual-04" border="0">
<img src="https://i.ibb.co/LXrwx7Hk/Redpost-NAS-Manual-05.png" alt="Redpost-NAS-Manual-05" border="0">
<img src="https://i.ibb.co/8n8Bv4vV/Redpost-NAS-Manual-06.png" alt="Redpost-NAS-Manual-06" border="0">
<img src="https://i.ibb.co/zY9xqcQ/Redpost-NAS-Manual-07.png" alt="Redpost-NAS-Manual-07" border="0">
<img src="https://i.ibb.co/Nn60dbsh/Redpost-NAS-Manual-08.png" alt="Redpost-NAS-Manual-08" border="0">
<img src="https://i.ibb.co/zhGdYLD3/Redpost-NAS-Manual-09.png" 
alt="Redpost-NAS-Manual-09" border="0">
<img src="https://i.ibb.co/9k4Py8Kt/Redpost-NAS-Manual-10.png" alt="Redpost-NAS-Manual-10" border="0">
<img src="https://i.ibb.co/B2Nmc6Lw/Redpost-NAS-Manual-11.png" alt="Redpost-NAS-Manual-11" border="0">
<img src="https://i.ibb.co/B53mK5fT/Redpost-NAS-Manual-12.png" alt="Redpost-NAS-Manual-12" border="0">
<img src="https://i.ibb.co/jvFkqL9g/Redpost-NAS-Manual-13.png" alt="Redpost-NAS-Manual-13" border="0">
<img src="https://i.ibb.co/n8B3fKv5/Redpost-NAS-Manual-14.png" alt="Redpost-NAS-Manual-14" border="0">
<img src="https://i.ibb.co/67BhMxsP/Redpost-NAS-Manual-15.png" alt="Redpost-NAS-Manual-15" border="0">



# NAS 운영 가이드 (물류회사용)

## 1. NAS 사용 규칙

1. **사용 권한 분리**
   - 한국
   - 중국

2. **동기화 규칙**
   - 한국 NAS ↔ 중국 NAS 주 1~2회 정기 동기화
   - 급한 경우 실시간 동기화 가능, 충돌 시 **버전 관리** 준수

4. **버전 관리**
   - 문서, 엑셀, CAD 등 수정이 잦은 파일은 **버전 번호** 포함
   - 예: `_v01`, `_v02` 등

5. **백업 정책**
   - 매일/주간 백업 → 별도 외부 HDD 또는 클라우드
   - 중요 데이터는 최소 2중 백업

---

## 2. NAS 권한 규칙 예시

| 폴더 | 권한 | 설명 |
|------|------|------|
| Korea | R/W (물류팀, 회계팀) | 한국 사무실 전용 문서 |
| China | R/W (물류팀, 회계팀) | 중국 사무실 전용 문서 |
| Shared/SOPs | R (모든 팀) | 표준작업지침, 매뉴얼 |
| Shared/Templates | R/W (물류팀, 관리팀) | 각종 템플릿 문서 |
| Shared/Projects/Project_A | R/W (한국·중국 프로젝트 담당자) | 프로젝트 문서, 계획, 보고서 |
| Archive | R (모든 팀) | 완료된 자료, 과거 문서 |

---

## 3. NAS 폴더 구조 예시

> ⚠️ 주의사항
> - NAS에서 직접 폴더 이동/삭제 시 **권한을 반드시 확인**
> - 동시 편집 파일은 버전 충돌 방지 위해 체크인/체크아웃 시스템 활용
> - 주기적으로 백업 확인

---
## NAS 상세

### 1. 중앙 집중식 파일 공유 및 관리

가장 핵심적인 기능으로, 모든 파일과 문서를 한 곳에 저장하고 관리하게 해줍니다.

* **공유 폴더:** 한국 및 중국 사무실 직원들이 어디서든 접속하여 파일을 **업로드, 다운로드, 공동 작업**할 수 있는 중앙 허브 역할을 합니다.
* **접근성:** 인터넷만 연결되면 PC, 노트북, 스마트폰 등 다양한 장치에서 접속할 수 있습니다.
* **용량 확장:** 내부 디스크 교체나 증설을 통해 스토리지 용량을 유연하게 확장할 수 있습니다.

---

### 2. 보안 및 권한 제어 (액세스 관리)

데이터의 보안과 사용자별 접근 통제를 철저하게 관리합니다.

* **사용자/그룹 권한 설정:** 한국, 중국 등 **팀별 또는 사용자별로 접근 권한**($R/W$ 또는 $R$)을 다르게 설정하여 중요한 데이터의 무단 접근 및 수정을 방지합니다.
* **보안 연결:** 외부에서 접속 시 **암호화된 연결($VPN$ 또는 $HTTPS$)**을 사용하여 데이터를 안전하게 보호합니다.

---

### 4. 데이터 백업 및 보호

가장 중요한 기능 중 하나로, 업무 연속성과 데이터 안정성을 보장합니다.

* **자동 백업:** PC나 서버에 있는 데이터를 **NAS로 자동 백업**하도록 설정하여 데이터 손실을 방지합니다.
* **버전 관리:** 파일이 수정될 때마다 이전 버전을 보관하여, 실수로 파일을 덮어쓰거나 랜섬웨어에 감염되었을 때 **특정 시점으로 데이터를 복원**할 수 있습니다.
* **외부 백업:** NAS에 저장된 데이터를 외부 하드 드라이브나 클라우드 서비스로 **이중 백업**할 수 있게 합니다.

---

### 5. 원격 접속 및 동기화

지리적으로 떨어진 사무실이나 출장 중에도 업무를 지속할 수 있게 돕습니다.

* **원격 접속:** 외부 네트워크를 통해 NAS에 접속하여 파일에 접근할 수 있습니다.
* **사무실 간 동기화:** 한국 NAS와 중국 NAS 간에 **정기적인 파일 동기화**를 수행하여 양쪽 사무실이 최신 정보를 공유하도록 합니다 (미러링).

* **클라우드 서비스 통합:** 구글 드라이브, 드롭박스 등 **외부 클라우드 서비스와 연동**하여 백업 또는 동기화 목적으로 활용할 수 있습니다.
