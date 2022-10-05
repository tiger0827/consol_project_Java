## 학교 데이터관리 프로그램  ✏️   

* * *

#### 1. 기획 목적 🔥
- 코로나로 인한 학생 관리의 어려움
- 비대면 수업으로 인한 학급 구성원의 소통이 어려움
- 교사 사생활 보장으로 인한 퇴근시간 이후 연락의 어려움

#### 2. 개발 환경 ⚙️
<img width="963" alt="스크린샷 2022-10-05 오후 8 45 28" src="https://user-images.githubusercontent.com/75536654/194053009-eac0b9be-0860-44b4-945a-fc6abf5b1eaf.png">

#### 3. 팀원 소개 및 업무 분담 👨‍👨‍👧‍👦
<img width="772" alt="스크린샷 2022-10-05 오후 8 47 13" src="https://user-images.githubusercontent.com/75536654/194053279-9a696cd8-c93e-49df-996b-901951fd461f.png">

#### 4. 개발 일정 ⏰
<img width="996" alt="스크린샷 2022-10-05 오후 8 48 09" src="https://user-images.githubusercontent.com/75536654/194053459-f58c3b1d-da04-4411-91f0-7bb53630da3f.png">

#### 5. 기능 설명 📚
<img width="477" alt="메인 화면" src="https://user-images.githubusercontent.com/75536654/194057225-f6773dd6-167e-4775-8778-2c891813b95e.png">

* 로그인 기능
  * 학생: s + 숫자 4자리
  * 교사: t + 숫자 2자리
* 교사 페이지
  * 로그인한 교사의 정보를 출력 (담당 학년, 반, 직급, 이름)
  * 담당 학년과 반이 없을 경우 직급만 출력
  * [1] 정보 조회
    * 학생 정보 조회: 학생 이름 입력 시 학년, 반, 번호, 이름, 고유번호, 성별, 생년월일, 연락처, 주소 출력
    * 교사 정보 조회: 교사 이름 입력 시 직급, 이름, 학년, 반, 담당 과목, 연락처, 생년월일 출력, 데이터가 없을 경우 '-' 출력
  * [2] 학생 정보 관리
    * [2-1] 학생 정보 추가: 추가를 원하는 학생의 정보를 입력, 학생의 학급 번호는 해당 반의 가장 큰 번호로 자동 입력
    * [2-2] 학생 정보 수정: 수정을 원하는 학생의 정보를 새로 입력해 수정, 해당 학급에 같은 번호가 존재하면 "해당 학급에 같은 번호를 가진 학생이 존재합니다." 메시지 출력
    * [2-3] 학생 성적 수정: 학생 ID를 입력 후 학생의 성적을 수정
    * [2-4] 학생 정보 삭제: 학생 ID를 입력 후 학생 정보 삭제
  * [3] 시간표 열람: 담당 반이 없을 경우 "담당 학급이 존재하지 않습니다." 메시지 출력
  * [4] 학급 관리
    * [4-1] 학급 게시판 관리
      * [4-1-1] 공지사항: 해당 학급의 공지사항 작성, 작성된 최신순으로 최대 5개만 출력
      * [4-1-2] 한 줄 게시판: 해당 학급의 학생들이 작성한 한 줄 게시판 조회
    * [4-2] 학급 구성원 조회: 담당반의 학생 구성원 정보 조회
  * [5] 코로나 병결 신청 확인
    * [5-1] 코로나 확진 학생 명단
    * [5-2] 코로나 의심 학생 명단
  * [6] 조직 구성도: 모든 교직원 정보 출력
* 학생 페이지
  * 로그인한 학생의 정보를 출력 (학년, 반, 이름)
  * [1] 정보 조회
    * 학생 정보 조회: 학생 이름 입력 시 학년, 반, 번호, 이름 출력(타 학생의 개인정보 보호를 위해 출력 정보 제한)
    * 교사 정보 조회: 교사 이름 입력 시 이름, 담당 과목, 직급 출력 (교사의 개인정보 보호를 위해 출력 정보 제한), 데이터가 없을 경우 '-' 출력
  * [2] 개인 성적 조회: 학기 입력 시 해당 학기의 성적, 반 석차, 전교 석차 출력
  * [3] 교사 수업 평가
  * [4] 학급 게시판
    * [4-1] 공지사항 조회: 담임 선생님이 작성한 공지사항 조회
    * [4-2] 한 줄 게시판 작성: 해당 학급의 학생들이 자유롭게 작성, 작성된 게시판 내용 출력, 최신순으로 최대 5개만 출력
    * [4-3] 학급 시간표 열람
  * [5] 코로나 병결 신청
    * [5-1] 코로나 확진 병결 신청: 확진 날짜와 수업 참여 방식(실시간, 영상)을 입력, 격리 기간은 확진 날짜에 맞춰 자동 입력
    * [5-2] 코로나 의심 병결 신청: 증상, 체온, 수업 참여 방식(실시간, 영상)을 입력

  



