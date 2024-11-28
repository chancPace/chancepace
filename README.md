# CHANS'PACE 🚀

## 프로젝트 개요  
**CHANS'PACE**는 공간 대여를 중심으로 한 플랫폼으로, 사용자가 원하는 공간을 쉽고 빠르게 검색하고 예약할 수 있는 서비스를 제공합니다.  
호스트와 게스트, 그리고 관리자를 위한 맞춤형 기능을 통해 편리하고 체계적인 공간 대여 경험을 제공합니다.

---

## 👥 팀원  
| [PL] 윤석찬    | 최재혁    | 한송이    |  
|----------------|-----------|-----------|  
| <div align="center">**Back-End**</div>  | <div align="center">**Front-End**</div> | <div align="center">**Front-End**</div> |  
| <div align="center"><img src="https://github.com/user-attachments/assets/fe8aae5b-9175-4df3-b580-b561d292e0f9" width="100" height="100"></div> | <div align="center"><img src="https://github.com/user-attachments/assets/9e33bcaf-a147-42f2-ac20-05969de65915" width="100" height="100"></div> | <div align="center"><img src="https://github.com/user-attachments/assets/b1b931ec-d5f4-44f4-80b0-3a7ffb3d2a78" width="100" height="100"></div> |  
| <div align="center">[![GitHub](https://img.shields.io/badge/GitHub-윤석찬-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YoonSeokChan98)</div> | <div align="center">[![GitHub](https://img.shields.io/badge/GitHub-최재혁-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/scn2930)</div> | <div align="center">[![GitHub](https://img.shields.io/badge/GitHub-한송이-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/songyiiii)</div> |


## 📅 프로젝트 기간  
- **시작일**: 2024년 10월 14일  
- **종료일**: 2024년 11월 20일  

---

## 🔑 주요 기능  

### 🧳 게스트  
- 원하는 공간을 선택해 대여할 수 있는 서비스 제공  
- 공간 찜하기 및 리뷰 작성 기능 지원  
- 결제 및 예약 완료 후 이메일을 통한 공간 안내 제공  

### 🏠 호스트  
- 자신의 공간을 등록하고 수정 가능  
- 예약 리스트를 날짜별로 확인하며 공간 예약 상태 관리  
- 현재 매출 및 정산 받을 금액 실시간 확인  

### 🛠 관리자  
- 게스트 및 호스트 회원 관리  
- 호스트 신청 및 공간 등록 승인  
- 쿠폰 생성, 발급 및 이벤트 관리 기능 제공  

---

## 🛠 기술 스택  

**Frontend**  
- ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)  
- ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)  
- ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)  
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)  
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)  
- ![Styled Components](https://img.shields.io/badge/Styled%20Components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)  

**Backend**  
- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)  
- ![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)  
- ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)  
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white)  

**외부 API & 라이브러리**  
- Kakao Map API  
- TossPayments  
- Nodemailer  

---

# ✨ CHANS'PACE 기능 소개  
## 게스트 기능

### 1. **공간 검색 및 대여**
사용자가 원하는 지역과 날짜를 입력하면 조건에 맞는 대여 가능한 공간 목록을 확인할 수 있습니다. 클릭 한 번으로 간편하게 예약과 결제를 진행할 수 있습니다.

---

### 2. **예약 및 결제 취소**
![예약 및 결제 취소](https://github.com/user-attachments/assets/a6459077-9a29-49d8-bee4-bcd28ce4f09d)
예약을 취소하면 결제 건도 자동으로 취소됩니다. 사용자는 마이페이지에서 간편하게 취소를 진행할 수 있습니다.

---

### 3. **리뷰 작성 및 삭제**
- **작성**: ![리뷰 작성](https://github.com/user-attachments/assets/f65228cf-17c5-49db-a015-03887f068a6f)  
  공간 이용 후 리뷰와 별점을 남길 수 있습니다. 작성된 별점은 해당 공간의 평균 점수로 반영됩니다.  
- **삭제**: ![리뷰 삭제](https://github.com/user-attachments/assets/e8a58b4c-1568-45bb-a2dd-38a7b52d4373)  
  작성한 리뷰는 언제든 삭제할 수 있습니다.

---

### 4. **비밀번호 변경**
![비밀번호 변경](https://github.com/user-attachments/assets/8e355d93-c570-4dba-ac06-654ea1eb183d)  
비밀번호를 잊어버린 경우, 이메일 인증을 통해 비밀번호를 재설정할 수 있습니다. `nodemailer` 라이브러리를 활용하여 안전하게 이메일을 발송합니다.

---

### 5. **호스트 신청**
게스트는 "호스트 문의하기" 버튼을 눌러 호스트 권한을 신청할 수 있습니다. 관리자가 신청서를 확인 후 승인을 진행합니다.

---

### 6. **공간 찜하기**
![공간 찜하기](https://github.com/user-attachments/assets/a87fecf0-4c22-4190-bf35-b6eee44d90a4)  
마음에 드는 공간을 찜 목록에 저장하여 나중에 편리하게 다시 확인할 수 있습니다.

---

## 호스트 기능

### 1. **공간 등록 및 수정**
![공간 등록](https://github.com/user-attachments/assets/sample-host-register.gif)  
호스트는 자신의 공간 정보를 등록하고, 필요 시 수정할 수 있습니다.  
`kakao map API`를 활용하여 주소 입력 및 위치 설정이 가능합니다. 등록 후 관리자의 승인을 받으면 공간이 플랫폼에 노출됩니다.

---

### 2. **예약 리스트 관리**
호스트는 자신의 공간에 대한 예약 리스트를 한눈에 확인할 수 있습니다. 예약된 날짜와 상태를 확인하여 공간 스케줄을 효율적으로 관리할 수 있습니다.

---

### 3. **매출 조회**
![매출 조회](https://github.com/user-attachments/assets/dcba1ed3-c8b0-484e-9fd9-944474eaf2e9)  
연도별, 월별로 매출 데이터를 그래프로 시각화하여 정산 금액 및 매출 상태를 확인할 수 있습니다.

---

## 관리자 기능

### 1. **호스트 신청 관리**
호스트 신청 내용을 확인 후, 해당 사용자의 권한을 수정합니다. 신청이 승인되면 결과를 사용자에게 알립니다.

---

### 2. **공간 승인 관리**
![공간 승인](https://github.com/user-attachments/assets/378b5d78-24ec-46e6-92da-26a940769999)  
호스트가 등록한 공간을 검토하여 승인 또는 반려합니다. 승인된 공간은 게스트가 검색 및 대여할 수 있습니다.

---

### 3. **호스트 대신 공간 등록**
관리자가 직접 호스트를 대신하여 공간을 등록하거나 수정할 수 있습니다. 이를 통해 바쁜 호스트를 지원합니다.

---

### 4. **카테고리 관리**
![카테고리 관리](https://github.com/user-attachments/assets/e5143c6c-89e5-4153-8929-d341587359ea)  
공간의 분류를 위한 카테고리를 추가하거나 수정할 수 있습니다. 더 세분화된 카테고리를 제공하여 사용자 편의를 높입니다.

---

### 5. **쿠폰 생성 및 발급**
![쿠폰 생성](https://github.com/user-attachments/assets/f69d5406-1d53-4067-a851-d1267cdaeadc)  
관리자는 다양한 이벤트를 위해 쿠폰을 생성하고, 사용자에게 발급할 수 있습니다.

---

### 6. **쿠폰 수정 및 삭제**
![쿠폰 수정 및 삭제](https://github.com/user-attachments/assets/74ee2ea6-cc99-42a0-a95a-6167542bcfea)  
쿠폰 정보를 수정하거나 불필요한 쿠폰을 삭제하여 이벤트를 관리합니다.

---

