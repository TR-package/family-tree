# Family Tree App

## 앱 소개
  **가족 관계도를 만들고 관리하는 앱.**   
  <br>
  나를 기준으로 가족의 이름, 관계(호칭)을 넣어 언제든지 수정, 확인 할 수 있습니다.
  - 직관적인 인터페이스
  - 가족 정보 저장 및 불러오기
  - 관계 시각화
  

## 앱 사용하기전...
  - 본 가족관계도는 부모노드가 2개가 될수 없습니다.
  - 친가, 외가, 친정, 시댁, 처가 등으로 구분 지어 작성을 권합니다.

## 앱 사용방법
  ### 1. 가족 구성원 추가
  **`나`를  클릭하여 나와의 관계를 생성합니다.**
  - 관계 선택 : `나`의 관점에서 노드 관계를 선택합니다.
    + 현재 노드 수정 : 현재 노드를 수정, 등록 합니다. 
    + 부모 : `나`를 기준으로 위에 노드가 생성됩니다.
    + 자식 : `나`를 기준으로 아래 노드가 생성됩니다.
    + 형제/자매: `나`와 동일한 기준으로 노드가 생성됩니다.
      * 손위: `나`를 기준으로 앞에 노드가 생성됩니다.
      * 손아래: `나`를 기준으로 뒤에 노드가 생성됩니다.


  - 이름 : 노드의 이름을 입력합니다. (예: 홍길동) 

  - 성별 : 성별을 선택합니다.

  - 관계 : 나와의 관계(호칭)을 입력합니다. (선택)

  - 생년월일 : 생년월일을 입력합니다. (선택)

  - 배우자 추가 : 배우자가 있으면 선택하여 (이름, 성별, 관계, 생년월일) 등록합니다.   
    *단, 관계 선택이 `현재 노드 수정`일때 활성화 됩니다.*


  ### 2. 저장, 불러오기
  - 등록된 구성원은 json형태로 내기기에 저장, 불러올 수 있습니다.


  ### 3. 편의기능
  - <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-zoom-in" aria-hidden="true"><circle cx="11" cy="11" r="8"></circle><line x1="21" x2="16.65" y1="21" y2="16.65"></line><line x1="11" x2="11" y1="8" y2="14"></line><line x1="8" x2="14" y1="11" y2="11"></line></svg> : 관계도를 확대합니다.

  - <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-zoom-out" aria-hidden="true"><circle cx="11" cy="11" r="8"></circle><line x1="21" x2="16.65" y1="21" y2="16.65"></line><line x1="8" x2="14" y1="11" y2="11"></line></svg> : 관계도를 축소합니다.

  - <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-timer-reset" aria-hidden="true"><path d="M10 2h4"></path><path d="M12 14v-4"></path><path d="M4 13a8 8 0 0 1 8-7 8 8 0 1 1-5.3 14L4 17.6"></path><path d="M9 17H4v5"></path></svg> : 관계도를 기본크기로 만듭니다.

  - <svg width="24px" height="24px" viewBox="0 0 24 24" fill="none" stroke="currentColor"  xmlns="http://www.w3.org/2000/svg"><path class="cls-1" d="M13,22.5,7.82,17.36a2,2,0,0,1-.59-1.43,2,2,0,0,1,2-2,2,2,0,0,1,1.43.59L12,15.82V6.38a2,2,0,0,1,1.74-2,1.87,1.87,0,0,1,1.51.56,1.83,1.83,0,0,1,.57,1.34V12l5,.72a1.91,1.91,0,0,1,1.64,1.89h0a17.18,17.18,0,0,1-1.82,7.71l-.09.18"/><polyline class="cls-1" points="5.32 10.09 1.5 10.09 1.5 6.27"/><polyline class="cls-1" points="6.27 1.5 10.09 1.5 10.09 5.32"/><line class="cls-1" x1="5.32" y1="6.27" x2="1.5" y2="10.09"/><line class="cls-1" x1="6.27" y1="5.32" x2="10.09" y2="1.5"/></svg> : 손가락으로 확대, 축소 할 수 있습니다.
    