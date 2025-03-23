# Resume

### 김준형
**Software Enginer | Backend Developer | 목표를 이루며 성장하고 싶은 개발자**

[뒤처지지 않게 틈틈히 자기계발 하기]


문제를 해결하는 부분에서 뿌듯함을 많이 느낍니다.


Java, Spring, Python, Django, FastAPI 등 다양한 환경의 개발 경험이 있다는 것이 저의 장점입니다.

개인 서버를 구축하여 Git action, docker를 활용하여 배포 자동화 하여 컨테이너 및 리눅스에 익숙해지고 있습니다.

---

📧 **Email:** cosyq1305@naver.com  
📖 **Blog:** [cokes.tistory.com](https://cokes.tistory.com)

---

## 경력

- **플레이뎁** | 2022.06 ~ 
- **라스트일마일** | 2021.08 ~ 2022.05
- **더에스엠씨그룹** | 2021.01 ~ 2021.02 (인턴)
---

## 진행 프로젝트

### 플레이뎁

#### 📌 자사 판매 프로그램
- **개요:** 상품 판매를 위한 프로세스 자동화 및 통합 관리 프로그램
- **기술 스택:** Python, FastAPI, MySQL, Vue.js, PySide6
- **담당 업무:**
  - 상품 정보 수집, 등록, 주문 수집, 운송장 수집, 운송장 업로드, CS문의 수집 등 배치를 개발하여 판매 프로세스 자동화
  - Git lab CI를 활용한 배치 프로그램 자동 배포 및 재실행 
  - 오너클랜 API 활용 상품 카테고리 자동 매칭 기능 배치 개발
  - 외부 상품 엑셀 등록 GUI 프로그램 및 기능 개발
  - 자동 상품 등록 설정 관리자 API, 프론트 개발
- **성과:**
  - 상품 상태 동기화로 주문 취소율 75% 감소
  - 상품, 주문 정보 동기화로 실시간 데이터 관리, 데이터 정확성 향상 및 오류율 감소
  - 판매 프로세스 자동화에 따른 운영 비용 절감 및 업무 효율성 향상
  - 알림기능으로 고객 문의 대응 속도 개선
  - 상품 등록 및 관리 시간 단축으로 생산성 증가

#### 📌 [다팔자](https://ownerclan.com/V2/info_page/dafalza2.php) 서비스 프로그램 등록기 개발
- **개요:** 오너클랜 상품 대량 등록, 품절/단종 등에 따른 상품 동기화 기능 제공
- **기술 스택:** Node.js, TypeScript, Electron, Puppeteer
- **담당 업무:**
  - 신규 서비스 마켓(GS_SHOP, TOSS) 등록기 개발 및 유지보수

#### 📌 [다잡아](https://ownerclan.com/V2/info_page/coupang_winner.php) 서비스 프로그램 고도화
- **개요:** 크롤링 구조개선, 신규 기능, 관리자 기능 추가 
- **기술 스택:** Python(PySide6), Selenium, SQLite, Java(Spring), Vue.js, MySQL, PyUpdater, iwinv cloud service
- **담당 업무:**
  - 셀레니움 크롤링 -> 내부 API 를 통한 구조개선 (상품 리스트 조회, 가격 적용, 위너 확인 등)
  - 상품 1개씩 진행하던 기존 로직 -> 100~500개씩 상품을 진행하도록 수정
  - 배너(광고), 사용기간(유료화 -> 오너클랜 적립금 차감식), 사용자 통계(매출, 위너 상품, 사용로그 등) 기능 추가, 화면 및 API 개발
  - 자동 업데이트 추가
- **성과:**
  - 상품 처리 속도 개선(5시간 → 30분)
  - 셀레니움 -> 내부 API 변경에 따른 안정성 개선
  - 사용자 쿠팡 매출 195%, 주문량 169% 증가

#### 📌 통합 매크로 프로그램 구조개선 및 고도화
- **개요:** 기존 다중 실행 프로그램으로 인한 리소스 과부하, 로컬 PC의 성능 이슈에 따른 구조 개선 및 고도화
- **기술 스택:** Python(PySide6), Selenium, SQLite, MySQL, PyUpdater
- **담당 업무:**
  - 관리자 GUI 프로그램 개발 (프로그램별 매크로 대상 상품 관리 -> 관리자 프로그램으로 상품 관리 통합 및 에이전트 관리 기능 추가)
  - 에이전트 프로그램 개발 (매크로 실행만 담당하여 PC 리소스 과부하, 관리자 기능에 따른 이슈 방지)
  - 셀레니움 서버 분리 (셀레니움 서버를 분리하여 다중 실행에 따른 PC 리소스 과부하 방지)
  - 자동 업데이트 적용
- **성과:**
  - 관리자와 에이전트 분리로 상품 관리 편의성 증가, 매크로 기능 안정성 향상

#### 📌 종합몰 상품 자동 등록 관리 서비스 개발
- **개요:** 종합몰 마켓에 상품 관리를 자동화하기 위한 프로젝트
- **기술 스택:** Python(DRF), MySQL, Vue.js, Selenium
- **담당 업무:**
  - GS SHOP, 홈플러스, Toss 마켓 상품 관리 기능 개발 (셀레니움 크롤링)
  - 관리자 웹 및 API 개발 (자동화 설정, 마켓 관리, 사용자 관리 등)
  - RESTful API 설계와 HTTP 통신 학습을 통해 실무 적용하였으며, 관리자 클라이언트 뿐 아니라 서버 배치 프로그램에서도 사용 가능하도록 JSON 형식의 요청 및 응답 구조를 설계
- **성과:**
  - 자동화에 따른 상품 등록 시간 단축(5분 → 1초), 담당자가 주문 관리만 하게 되어 업무 효율 증가 
  - 품절, 단종, 가격변경에 따른 동기화 적용으로 역마진, 주문 취소율 감소

#### 📌 보드미 상품 정보 수집 프로그램 개발 및 유지보수 (월 사용료 기반 서비스 운영중)
- **개요:** (주)보드미 사에서 판매하는 도매몰 상품을 수집하여 품절, 단종, 가격변경 등을 엑셀로 제공하여 통합 관리가 가능하도록 만든 프로그램
- **기술 스택:** Python(PySide6), SQLite, PyUpdater
- **담당 업무:**
  - 도매 사이트 상품 정보 크롤링 GUI 프로그램 개발·유지보수
  - 신규 사이트 추가 및 요구사항에 따른 수정 개발
  - 자동 업데이트 적용용
  
---

### 라스트일마일

#### 📌 키워드 추출 서비스 개발
- **개요:** 쿠팡, 스마트스토어 상위 판매 키워드를 분석하여 상품명에 따른 키워드를 추출해 추천해주는 서비스
- **기술 스택:** Java(Spring), MySQL, Vue.js
- **담당 업무:**
  - 기존 개별 키워드 추출 기능을 엑셀 파일 업로드 기반 대량 키워드 추출 기능으로 고도화 진행(서버 API 및 프론트엔드 화면 신규개발)
  - 백엔드에서 엑셀파일 업로드, 다운로드 처리 기능을 프론트로 수정하여 JSON으로 백엔드에서 처리 되도록 수정하여 불필요한 I/O 처리를 없애, 백엔드 처리 속도, 데이터 처리 유연성을 향상시킴

#### 📌 다잡아 서비스 프로그램 개발 및 관리자 개발
- **개요:** 쿠팡에 등록된 오너클랜 코드를 가진 상품의 공급가, 마진, 수수료에 따라 역마진이 발생하지 않는 선에서 위너 상품으로 만들어 주문, 판매율을 늘리기 위한 서비스 프로그램 
- **기술 스택:**
  - Python(PySide6), Selenium, SQLite
  - Java(Spring), Vue.js, MySQL, iwinv cloud service
- **담당 업무:**
  - 클라이언트 GUI 프로그램, 기능 개발
  - 관리자 API, 프론트 개발 (사용자 관리, 프로그램 관리)

#### 📌 도매허브 상품 수집 프로그램 개발 및 유지보수
- **개요:** 오너클랜에 도매몰 상품을 등록하기 위해 도매몰 상품을 수집하여 엑셀로 등록할 수 있도록 만든 GUI 프로그램
- **기술 스택:** Python(PySide6), SQLite, Redis, MongoDB
- **담당 업무:**
  - 도매 사이트 상품 크롤링 드라이버 개발
  - GUI 프로그램 개발
  - 엑셀 다운로드 기능 개발 (B2B 오너클랜 대량 상품등록 포맷)

#### 📌 통합 매크로 프로그램 개발
- **개요:** 셀레니움을 이용하여 상품을 구경하듯 자동화하여 상품의 노출도를 상위권으로 향상시키는 GUI 프로그램
- **기술 스택:** Python(PySide6), Selenium, SQLite, MySQL, PyUpdater
- **담당 업무:**
  - GUI 프로그램 개발 및 유지보수
  - 매크로 작업 상품 관리, 매크로 기능 등 전체적인 기능 개발
  - 추가 기능 개발 (다중 실행 기능 등)
  - 자동 업데이트 적용 
    
---

### 더에스엠씨그룹

#### 📌 방구석 연구소 신규 테스트 개발 (짤 뽑기)
- **개요:** 방구석 연구소 새해인사 짤 뽑기 신기능 개발 
- **기술 스택:** PHP, Codeigniter, MySQL
- **담당 업무:**
  - 신규 테스트 (짤 뽑기) 백엔드 서비스 로직 개발 (이미지 관리, 리사이징 등)
  - 프론트 API 연동 및 짤 뽑기 로직(캔버스 이용) 개발
  - 기존 로딩 페이지 개선 (하드코딩 메세지, 테스트 마다에 따른 이동 오류 등)

#### 📌 mrmt 뉴스레터 구독 페이지 개발
- **개요:** 스티비 API 연동하여 구독자에게 뉴스레터 메일 전송 및 구독 환영 메일을 전송을 위한 뉴스레터 구독 웹 개발
- **기술 스택:** PHP, Codeigniter, MySQL
- **담당 업무:**
  - 백엔드 API 개발 및 스티비 API 연동, 구독자 관리자 개발

---
읽어주셔서 감사합니다! 😊 
