# Read Me
# 프로젝트 제목
```markdown
Early Bud (얼리 벗)
```

# 프로젝트 정보
```markdown
프로젝트 목적 : 문화예술 얼리버드 티켓 정보 및 얼리버드로 가성비 있는 문화생활을 즐기고자 하는 사람들의 커뮤니티 플랫폼.
프로젝트 개발 기간 : 2024.06.24 ~ 2024.07.18
```
# 기능 소개
### **사용자(User) 필수 기능**

### **1. 회원 관리**

- **회원 가입 및 로그인**: 소셜 로그인, 이메일/휴대폰 번호 가입, 비밀번호 재설정.
- **프로필 관리**: 프로필 작성 및 수정, 관심사 설정.

### **2. 모임 관리**

- **모임 생성 및 수정**: 새로운 모임 생성 및 기존 모임 정보 수정.
- **참가자 관리**: 모임 참가자 목록 확인 및 관리.
- **모임 일정 관리**: 모임 일정 추가, 수정, 삭제.
- **공지사항 게시**: 모임 공지사항 작성 및 게시.

### **3. 모임 참여 및 활동**

- **모임 탐색 및 가입**: 모임 검색 및 탐색, 참여 신청 및 승인.
- **참여 모임 목록**: 현재 참여 중인 모임 목록 확인.
- **모임 일정 확인**: 모임 일정과 이벤트 캘린더 확인.
- **참여 신청 및 취소**: 모임에 참여 신청하거나 취소.

### **4. 소통 및 커뮤니티 기능**

- **게시물 작성 및 조회**: 모임 내 게시물 작성 및 다른 사용자의 게시물 조회.
- **댓글 작성 및 조회**: 게시물에 댓글 작성 및 조회.
- **좋아요 및 리액션**: 게시물과 댓글에 좋아요 및 다양한 리액션 추가.
- **실시간 채팅**: 1:1 채팅 및 그룹 채팅.

### **5. 알림 기능**

- **푸시 알림**: 모임 일정, 메시지, 댓글, 공지사항 등의 실시간 푸시 알림.
- **알림 설정**: 개인별로 알림 설정 및 관리.

# **관리자(Admin) 필수 기능**

### **1. 사용자 관리**

- **사용자 정보 조회**: 모든 사용자의 프로필과 활동 내역 조회.
- **사용자 권한 설정**: 사용자에게 관리자 권한 부여 또는 해제.
- **사용자 제재**: 규정을 위반한 사용자 제재(경고, 차단, 탈퇴).

### **2. 콘텐츠 관리**

- **게시물 검토 및 승인**: 사용자들이 작성한 게시물 검토 및 승인.
- **부적절한 콘텐츠 삭제**: 커뮤니티 가이드라인에 위배되는 콘텐츠 삭제.
- **댓글 관리**: 게시물에 달린 댓글 검토 및 삭제.

### **3. 시스템 설정**

- **보안 설정**: 보안 관련 설정(이중 인증, 암호화 등).

  ## **관리자(Admin) README**

### **주요 기능 및 권한**

---

### **1. 사용자 관리**

- **사용자 정보 조회**
    - **기능**: 모든 사용자의 프로필과 활동 내역 조회.
    - **권한**: 관리자.
- **사용자 권한 설정**
    - **기능**: 사용자에게 관리자 권한 부여 또는 해제.
    - **권한**: 관리자.
- **사용자 제재**
    - **기능**: 규정을 위반한 사용자 제재(경고, 차단, 탈퇴).
    - **권한**: 관리자.

---

### **2. 콘텐츠 관리**

- **게시물 검토 및 승인**
    - **기능**: 사용자들이 작성한 게시물 검토 및 승인.
    - **권한**: 관리자.
- **부적절한 콘텐츠 삭제**
    - **기능**: 커뮤니티 가이드라인에 위배되는 콘텐츠 삭제.
    - **권한**: 관리자.
- **댓글 관리**
    - **기능**: 게시물에 달린 댓글 검토 및 삭제.
    - **권한**: 관리자.

---

### **3. 시스템 설정**

- **보안 설정**
    - **기능**: 보안 관련 설정(이중 인증, 암호화 등) 관리.
    - **권한**: 관리자.
      
# **사용자(User) README**

### **주요 기능 및 권한**

---

### **1. 회원 관리**

- **회원 가입 및 로그인**
    - **기능**: 이메일, 휴대폰 번호 또는 소셜 로그인 옵션을 통해 가입 및 로그인.
    - **권한**: 모든 사용자.
- **프로필 관리**
    - **기능**: 개인 프로필 작성 및 수정, 관심사 설정.
    - **권한**: 모든 사용자.

---

### **2. 모임 관리**

- **모임 생성 및 수정**
    - **기능**: 새로운 모임 생성 및 기존 모임 정보 수정.
    - **권한**: 호스트 및 관리자
- **참가자 관리**
    - **기능**: 모임 참가자 목록 확인 및 관리.
    - **권한**: 호스트 및 관리자
- **모임 일정 관리**
    - **기능**: 모임 일정 추가, 수정, 삭제.
    - **권한**: 호스트 및 관리자.
- **공지사항 게시**
    - **기능**: 모임 공지사항 작성 및 게시.
    - **권한**: 호스트 및 관리자.

---

### **3. 모임 참여 및 활동**

- **모임 탐색 및 가입**
    - **기능**: 모임 검색 및 탐색, 참여 신청 및 승인.
    - **권한**: 모든 사용자.
- **참여 모임 목록**
    - **기능**: 현재 참여 중인 모임 목록 확인.
    - **권한**: 모든 사용자.
- **모임 일정 확인**
    - **기능**: 모임 일정과 이벤트 캘린더 확인.
    - **권한**: 모든 사용자.
- **참여 신청 및 취소**
    - **기능**: 모임에 참여 신청하거나 취소.
    - **권한**: 모든 사용자.

---

### **4. 소통 및 커뮤니티 기능**

- **게시물 작성 및 조회**
    - **기능**: 모임 내 게시물 작성 및 다른 사용자의 게시물 조회.
    - **권한**: 모임 참가자.
- **댓글 작성 및 조회**
    - **기능**: 게시물에 댓글 작성 및 조회.
    - **권한**: 모임 참가자.
- **평가**
    - **기능**: 모임 후기 작성 및 평가
    - **권한**: 모임 참가자.
- **실시간 채팅(보류)**
    - **기능**: 1:1 채팅 및 그룹 채팅.
    - **권한**: 모든 사용자.

---

### **5. 알림 기능(보류)**

- **푸시 알림**
    - **기능**: 모임 일정, 메시지, 댓글, 공지사항 등의 실시간 푸시 알림.
    - **권한**: 모든 사용자.
- **알림 설정**
    - **기능**: 개인별로 알림 설정 및 관리.
    - **권한**: 모든 사용자.
 
- 

## 🕰️ 개발 기간



### 🧑‍🤝‍🧑 멤버구성
- 프로젝트 매니저 : 남지혜
- 형상 관리자     : 이민국
- 문서 관리자    : 김진용
- 이슈 관리자   : 김만호, 윤해빈
- DBA         : 임찬울

### ⚙️ 개발 환경
 - NOTION : 시장조사, 유사프로그램 분석, 업무 분석, 요구사항 분석
 - MIRO : 메뉴구조도, 유스케이스 다이어그램
 - FIGMA : UI, 전체업무흐름도
 - DA# : 데이터 모델링
 - MYSQL : 데이터베이스 관리
 - INTELLIJ(JAVA Spring Boot) : 기능 구현

# 팀 소개
![image](https://private-user-images.githubusercontent.com/157683242/333201333-3c2da393-cb46-4292-9f31-af3cca21d9a3.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTY0OTUxODYsIm5iZiI6MTcxNjQ5NDg4NiwicGF0aCI6Ii8xNTc2ODMyNDIvMzMzMjAxMzMzLTNjMmRhMzkzLWNiNDYtNDI5Mi05ZjMxLWFmM2NjYTIxZDlhMy5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNTIzJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDUyM1QyMDA4MDZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mMTgxZGQ0MTVkZDkxYWIxNDIxOWM2M2M2YjNmNTkxODdiNGEyMDE5NmNkZGJiMmM4NGY0NmRhMmE4NGI1ZTQwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.vAQHRghrp4dui5xK07DfvWpZCCICgVpoIDh856uI4VI)

<pre>
<code>
<div align="center">
  <table>
    <tr align="center">
      <td height="200px" width="200px"><img src="https://github.com/BlizzaB/.github/assets/157683242/72c8c7bc-05aa-41b4-8869-ff41727a0552" alt="image" border="0"></td>
      <td height="200px" width="200px"><img src="https://github.com/BlizzaB/.github/assets/157683242/92d17fa1-31fb-457f-9065-620ee07eab36" alt="image" border="0"></td>
      <td height="200px" width="200px"><img src="https://github.com/BlizzaB/.github/assets/157683242/5a0c1be6-b93b-4b58-933d-1629ff50ce45" alt="image" border="0"></td>
    </tr>
    <tr colspan="2" align="center">
      <td><strong>남지혜</strong></td>
      <td><strong>이민국</strong></td>
      <td><strong>김만호</strong></td>
    </tr>
    <tr colspan="2" align="center">
      <td><i>Project manager</i></td>
      <td><i>Configuration Manager</i></td>
      <td><i>Test & Issue Manager</i></td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr align="center">
      <td height="200px" width="200px"><img src="https://github.com/BlizzaB/.github/assets/157683242/7e480587-b7dc-42e9-b292-1b93f6486738" alt="image" border="0"></td>
      <td height="200px" width="200px"><img src="https://github.com/BlizzaB/.github/assets/157683242/809dec29-151a-47c6-95dc-b3c4f5d9e114" alt="image" border="0"></td>
      <td height="200px" width="200px"><img src="https://github.com/BlizzaB/.github/assets/157683242/77a76aa5-ed00-4949-99a7-f66faf05b9c8" alt="image" border="0"></td>
    </tr>
    <tr colspan="2" align="center">
      <td><strong>임찬울</strong></td>
      <td><strong>김진용</strong></td>
      <td><strong>윤해빈</strong></td>
    </tr>
     <tr colspan="2" align="center">
      <td><i>DataBase Manager</i></td>
      <td><i>Document Manager</i></td>
      <td><i>Test & Issue Manager</i></td>
    </tr>
  </table>
</div>
</code>
</pre>












