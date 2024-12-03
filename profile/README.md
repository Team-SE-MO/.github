![image](https://github.com/user-attachments/assets/adab8dfe-1bd2-42be-a4dc-877220e7f289)

# 👩🏻‍👧🏻‍👦🏻 팀원 소개

<table>
<tbody>
<tr>
<tr>
<td align="center">Project Leader</td>
<td align="center">FrontEnd Leader</td>
<td align="center">Member</td>
<td align="center">Member</td>
<td align="center">Member</td>
</tr>
<tr>
<td align="center"><a href="https://github.com/IToriginal"><img src="https://avatars.githubusercontent.com/u/117193889?v=4" width="100px;" alt=""/></td>
<td align="center"><a href="https://github.com/taeyeon721"><img src="https://avatars.githubusercontent.com/u/109333511?v=4" width="100px;" alt=""/></td>
<td align="center"><a href="https://github.com/juneheel"><img src="https://avatars.githubusercontent.com/u/131724311?v=4" width="100px;" alt=""/></td>
<td align="center"><a href="https://github.com/dabeen-jung"><img src="https://avatars.githubusercontent.com/u/71184046?v=4" width="100px;" alt=""/></td>
<td align="center"><a href="https://github.com/smuhsh"><img src="https://avatars.githubusercontent.com/u/49484645?v=4" width="100px;" alt=""/></td>
</tr>
<tr>
<td align="center"><a href="https://github.com/IToriginal">헌욱</td>
<td align="center"><a href="https://github.com/taeyeon721">태연</td>
<td align="center"><a href="https://github.com/juneheel">준희</td>
<td align="center"><a href="https://github.com/dabeen-jung">다빈</td>
<td align="center"><a href="https://github.com/smuhsh">석현</td>
</tr>
<tr>
<td align="center">프로젝트 총괄</br>백엔드 서버 총괄 </br> 데이터 수집 서버 개발</td>
<td align="center">프론트엔드 총괄</br>UI/UX 총괄</td>
<td align="center">사용자 인증/인가</br>서버 성능 개선</br> 데이터 관리 서버 개발</td>
<td align="center">서비스 API 서버 개발</br>배치 모니터링 개발</td>
<td align="center">이메일 전송 구현</br>인증 처리</td>
</tr>
</tr>
</tbody>
</table>

# ✨ 프로젝트 소개
이 프로젝트는 Oracle 데이터베이스의 **V$SESSION 뷰**를 활용하여 실시간 세션 데이터를 수집하고, 이를 기반으로 **시계열 데이터**를 구축하여 이를 차트로 시각화한 세션 모니터링 어플리케이션입니다. </br>
</br> 주요 목표는 데이터베이스 세션의 상태와 성능을 직관적으로 파악할 수 있는 시스템을 개발하여 **운영 및 관리의 효율성**을 높이는 데 있습니다.

## 💁🏻‍♂️ 프로젝트 주요 기능 및 특징
### 🎯 주요 기능
> 1. **데이터 수집 및 분석**:
>     - V$SESSION 뷰에서 세션 정보(사용자, 상태, 대기 이벤트 등)를 실시간으로 수집.
>     - 수집된 데이터를 시계열 형태로 가공하여 분석 가능.
> 2. **시각화 대시보드**:
>     - 세션 수, 대기 이벤트, 사용자별 활동 등을 직관적으로 표현한 차트 및 그래프 제공.
>     - 이상 징후를 빠르게 파악할 수 있는 알림 기능 지원.

### 🎯 서비스 특징
> 1. **실시간 모니터링**
>     - Oracle V$SESSION 데이터를 기반으로 데이터베이스 세션 상태를 **실시간으로 모니터링**.
>     - 세션 수, 대기 이벤트, 사용자 활동 등의 정보를 대시보드에서 직관적으로 확인 가능.
> 2. **과거 데이터 관리**
>     - 수집된 데이터를 시계열 데이터로 저장하여 **CSV 파일** 형태로 관리 가능.
>     - 과거 데이터 분석 및 레포트 작성에 용이.
> 3. **권한별 맞춤형 서비스 제공**
>     
>     사용자 권한에 따라 제공되는 기능이 달라져 역할별 효율적인 관리 가능:
>     
>     ![image](https://github.com/user-attachments/assets/0bd83b6c-a3f2-4291-b026-9a07c62ed442)
>     
>     - **슈퍼 관리자(Super Admin)**:
>         - 회원가입 요청 관리 기능 제공.
>         - 데이터베이스 배치 작업의 상태 모니터링 가능.
>     
>     ---
>     
>     ![image](https://github.com/user-attachments/assets/39646570-3664-432b-b576-85b5d289fc6f)
>     
>     - **관리자(Admin)**:
>         - 데이터베이스 모니터링 및 유저 계정, 데이터베이스 정보 관리 기능.
>     
>     ---
>     
>     ![image](https://github.com/user-attachments/assets/da508d62-c957-4822-9d04-c422c936c1cf)
>     
>     - **일반 사용자(User)**:
>         - 본인이 사용 중인 데이터베이스 세션 및 관련 정보를 모니터링.

# ⌨️ 프로젝트 기술 스택
![image](https://github.com/user-attachments/assets/3c8645a8-b498-4698-be6b-fc0eb69b1d7d)

# 🆔 ERD
![image](https://github.com/user-attachments/assets/23f01912-b372-4872-9015-9207bdca14c3)

# 🚀 시스템 아키텍처 구조
![image](https://github.com/user-attachments/assets/312d7dbe-93e2-47d8-b68d-17cea68377b2)
![image](https://github.com/user-attachments/assets/4e041587-0c39-482c-b748-3597c7b57f4d)
![image](https://github.com/user-attachments/assets/72c4ca1c-870b-4232-a187-37ac5f5bbe1b)

# 🗂️ 멀티모듈 적용
![image](https://github.com/user-attachments/assets/84ffa3b5-c2e6-4b52-b8bd-3091fed7dbbc)

# 👾 주요 서비스 소개
## 1️⃣ 장비 요약 페이지
![image](https://github.com/user-attachments/assets/9f505d39-b9ac-456c-bf63-40db7764518a)

### [1]  회사 장비 상태
![image](https://github.com/user-attachments/assets/dbfce8c5-34dc-4afa-b63d-3bd50a01393e)
> 등록된 장비 상태 요약 : 3가지 상태를 통해 확인 가능하다. 
> - `ACTIVE` : 정상 연결되어있는 상태. 
> - `BLOCKED` : 정상 연결 상태이지만 주의가 필요한 상태.
> - `INACTIVE` : 현재 연결이 되어있지 않은 상태.
> 
> 상태별 순위 요약 : 다음과 같은 정보를 제공한다. 
> - 현재 가장 많이 사용되고 있는 장비
> - 주의요망 장비 
> - 오래된 장비  

### [2] 장비별 정보
![image](https://github.com/user-attachments/assets/12452139-4aad-4f41-9ada-9208d154711e)
> 장비의 상태 및 정보를 확인 가능하다.</br>
> 상단에서 원하는 DB를 검색할 수 있으며, 클릭하여 상세 모니터링 기능을 제공한다.

### [3] CSV 파일 기능
![image](https://github.com/user-attachments/assets/c3241080-3468-415f-85fc-f17c8b4347ce)
> 원하는 일자를 검색하여, 해당 일자에 수집된 전체 기기 데이터를 CSV 파일로 저장 가능하다.

## 2️⃣ 대시보드 페이지
### [1] 세션 데이터 모니터링
![image](https://github.com/user-attachments/assets/3f03867f-24c9-413b-a20b-7fe99e3153f2)
> **웹소켓**을 사용하여 클라이언트와 서버간 통신을 이룬다.
> **5초 주기**로 데이터를 서버로 부터 응답받아 차트를 최신 상태로 시각화 한다. 
> 1. `Active / Total Session Monitoring`: 시스템 세션 사용량 확인
> 2. `Blocking / Wait Session Monitoring`: 시스템 가용성 확인
> 3. `Session Count Group By User`: 시스템 사용 유저별 점유 세션 수
> 4. `Session Count Group By Type`: 시스템 사용 타입별 리소스 점유율
> 5. `Session Count Group By Command`:  사용중인 명령어
> 6. `Session Count Group By Machine`: 실행 중인 머신별 연결 현황 및 자원 분포 확인

### [2] 그리드 데이터 모니터링
![image](https://github.com/user-attachments/assets/a0bf54d0-15db-4985-9d00-5de9c2bd4c00)
> `V$SESSION` 뷰의 세션 데이터의 세부정보(`SID`, `SERIAL#`, `USERNAME`, `COMMAND`, `LOCKWAIT`, `COMMAND_NAME`, `STATUS`, `SCHEMANAME` 등)를 **새로고침** 버튼을 통하여 확인이 가능하다.

### [3] 회사 장비별 CSV 다운로드
> 현재 일자에 해당되는 회사의 해당 장비의 세션 데이터 세부정보를 CSV 파일로 제공한다.

## 3️⃣ 배치 모니터링
![image](https://github.com/user-attachments/assets/c98655f5-8be1-481e-b19f-a03915395b33)

### [1] 데이터 수집 시스템 작업 시간 차트
![image](https://github.com/user-attachments/assets/16558aef-ede8-4115-afd5-2c81e6ecb377)
> 세션 데이터 수집 작업에 소요되는 시간을 나타내며 성능을 확인할 수 있다. </br> 이 작업이 5초 안에 이루어져야되기 때문에 기준선을 표시하여 작업이 원활하게 이뤄지는지 한 눈에 확인 가능하다.

### [2] 데이터 관리 시스템 작업 시간 차트
![image](https://github.com/user-attachments/assets/b7a1c9e5-e9ca-4efe-90fe-ef64fa79aff1)
> csv 파일을 s3에 업로드 하는 작업의 시간과 데이터 삭제 작업의 시간을 나타내는 차트를 통해 하루 한 번 실행되는 작업의 소요 시간을 확인할 수 있다.

## 4️⃣ 회원가입
> 어드민은 회원 가입 요청 폼을 작성해서 관리자(Admin)는 서비스 가입을 위해 회원가입 요청 폼을 작성하여 제출할 수 있다. </br>
> 회원가입 요청 시, 자신의 소속 회사 정보가 시스템에 등록되어 있지 않은 경우, 회사 등록 요청 기능을 활용할 수 있다.

### [1] 회원가입 요청 폼 작성 및 제출
> 이름, 이메일, 소속 회사 등 필요한 정보를 입력한 후 회원가입 요청을 제출. </br>
> 요청 상태는 슈퍼 관리자 페이지에서 확인 가능.

### [2] 회사 등록 요청 모달
> 회사명, 사업자 등록 번호 등 필수 정보를 입력하여 회사 등록 요청 제출. </br>
> 요청된 회사 정보는 슈퍼 관리자가 검토 및 승인 후 등록.

## 5️⃣ 비밀번호 재설정
> 초기 비밀번호는 ‘`0000`’으로 이후로 변경되지 않을 경우, 로그인 시 비밀번호 재설정 화면으로 전환된다. </br>
> 이메일로 인증번호를 발송 및 인증번호를 확인하여 비밀번호를 재설정 할 수 있다.

## 6️⃣️ 장비 관리 페이지
![image](https://github.com/user-attachments/assets/140360b0-2888-46e8-9a6f-3062a71dd0fa)

### [1] 장비 등록, 수정
![image](https://github.com/user-attachments/assets/232c3e96-4087-43cf-b4c1-3e2afc980a85)
> 다음과 같은 정보들을 입력하고 장비 등록/수정이 가능합니다. </br>
> - `DB 유형`
> - `DB 별칭`
> - `IP`
> - `PORT`
> - `SID`
> - `USERNAME`
> - `PASSWORD`

입력 후 연결 확인을 진행해야 등록이 가능하며, 등록 및 수정된 이후부터 정상적으로 세션 데이터가 수집된다.

### [2] 장비 삭제
> 원하는 장비를 선택하여 삭제가 가능하며, 삭제 전 유의 문구와 경고를 확인 후 삭제 가능하다.

## 6️⃣️ 요청 관리 페이지
### [1] 회원 가입 요청 관리
> 관리자는 제출된 회원 가입 요청을 조회하고, 상세 정보를 확인할 수 있다. </br>
> 각 요청에 대해 승인 또는 반려 처리를 할 수 있으며, 상태 변경 시 신청자에게 결과가 자동으로 전달된다.

### [2] 회사 등록 요청 관리
> 관리자는 신규 회사 등록 요청을 조회하고, 요청된 회사 정보의 적합성을 검토할 수 있다.</br>
> 회사 등록 요청에 대해 승인 또는 반려 처리를 진행할 수 있으며, 승인된 회사는 시스템 내에 등록된다.
