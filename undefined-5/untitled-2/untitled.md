# 컴포넌트 사용하기: 사용자 - 고객지원 \| 이폼사인

![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/sample-of-using-user-component.gif)사용자 컴포넌트 사용 예시 \(문서 작성자 이름 자동 입력\)

## 언제 사용하나요?

![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/form-builder-components_user.png)

문서를 작성 또는 수정한 멤버의 정보가 문서에 자동으로 입력되게 할 때 사용합니다.

설정에 따라 이름, 연락처와 같은 멤버의 기본 정보 또는 사용자 정의 필드 정보가 사용자 컴포넌트에 자동으로 입력됩니다.

## 속성 설정하기

![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/user-component-properties-.png)

### ① ID

사용자 컴포넌트의 ID를 입력합니다.  
\(예를 들어, 문서를 작성한 멤버의 이름을 표시하는 컴포넌트의 ID는 ‘작성자 이름’으로 합니다.\)

### ② 사용자 표시 유형

* 만든 사람: 문서를 최초로 작성한 멤버의 정보를 표시합니다.
* 액세스한 사람: 문서를 가장 최근에 열람하거나 수정한 멤버의 정보를 표시합니다.
* 입력 값을 수정한 사람: 특정 컴포넌트에 내용을 입력한 멤버의 정보를 표시합니다.

  ![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/user-input-certain-component.png)

  입력 값을 수정한 사람을 선택하면, 입력 컴포넌트 ID 입력란이 나타납니다. 여기에 연결할 컴포넌트 ID를 입력합니다.

  예\) 담당자 서명란에 서명한 담당자의 이름을 자동으로 입력하게 할 경우:

  1. 담당자 서명란 서명 컴포넌트의 ID를 ‘담당자 서명’으로 지정합니다.
  2. 담당자 이름이 입력될 사용자 컴포넌트를 생성합니다.
  3. 사용자 컴포넌트의 사용자 표시 유형 속성을 ‘입력 값을 수정한 사람’으로 선택합니다.
  4. 입력 컴포넌트 ID 입력란에 ‘담당자 서명’을 입력합니다.

### ③ 사용자 표시 정보

멤버의 정보 중 어떤 정보를 표시할지 선택합니다. 멤버 기본 정보 또는 사용자 정의 필드에 추가로 입력한 정보들 중 원하는 정보를 선택합니다.

* 멤버 기본 정보 종류: 이름, ID, 부서, 직책, 휴대폰, 전화번호
* 멤버 기본 정보 수정하는 방법 \([회사 관리 권한](https://www.eformsign.com/kr/support/manual/types-of-permissions/company-management/)이 필요합니다.\)
  1. 이폼사인에 로그인합니다.
  2. 회사 관리 &gt; 구성원 관리 메뉴로 이동합니다.
  3. 멤버 목록에서 멤버를 선택합니다.
  4. 화면 오른쪽의 상세 보기 영역의 정보를 수정합니다.
  5. ‘저장’ 버튼을 클릭합니다.

