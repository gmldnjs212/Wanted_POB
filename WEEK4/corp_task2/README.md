### 기업과제2
---
#### 개발계획
- 뷰 개발
  - 헤더
    - 금액이 입력되는 Input 필드 (x1)
    - 다양한 통화를 선택할 수 있는 드롭다운메뉴 (x1)
  - 메인
    - 다양한 통화를 탭 형식으로 보여줌 (x1)
      - 단, 드롭다운메뉴에서 선택한 통화는 제외
      - 특정한 탭 클릭시 Input 필드에 입력한 금액에 대한 실시간 환율정보(금액) 출력
      - 정해진 포맷에 따라 기준일이 언제인지 출력

- 네트워크
    - 주어진 api활용을 위해서는 필요함
    - axios 활용예정

- 라우팅
  - 불필요
---
#### 개발순서
1. 뷰 개발
2. api, 네트워크 개발
3. 받아오는 데이터 Redux를 통해 저장
4. 뷰에 필요한 데이터 출력
5. 입력필드에 입력되는 값 쉼표추가 함수 개발
6. 개선이 필요한 부분 파악 및 개선
